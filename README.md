# Learning Human Preferences Over a Human-Robot Collaboration Based on Explicit and Implicit Human Feedback

There is significant interest in enabling robots to learn to perform tasks directly from interactions with non-expert users. Typically, a human serves as a teacher whose only task is to provide feedback to a robot learner. However, in real-world human-robot collaborations, the human often assists with the task while also offering feedback. Our key insight is that we can extract additional, implicit feedback from the human’s actions in the collaboration to augment the robot learning process. Under the assumption of fixed-role assignments, we first propose to formalize human preferences over a human-robot collaboration as a shared set of parameters encoding alignment between two reward functions: one that drives human behavior, and another that should direct robot behavior. This allows us to extract implicit feedback from an interaction by reasoning about the human’s actions in the task as actions that reveal the human’s preferences. Then, we combine this implicit feedback with traditional explicit human feedback to facilitate estimating the human’s preferences. We evaluated our proposed approach for Preference learning from Implicit and Explicit feedback (PIE) in simulations and with real users in a cooking scenario. Our simulation results indicate that combining multiple modalities of human feedback improves a robot’s ability to estimate human preferences over the collaboration, with a similar trend observed in real-world evaluations. Practically, these findings highlight a promising direction for more seamless interactions by enabling robots to adapt to a user’s preference model more quickly, thereby reducing the amount of time a person must spend teaching a robot collaborator.

<table>
  <tr>
    <td>
      <img src="https://github.com/user-attachments/files/24510216/overview.pdf" width="500">
    </td>
    <td width="250">
      <strong>Figure 1:</strong><br>
      We study the problem of learning human preferences over human-robot collaborations. We propose to leverage human actions as implicit feedback that can help the robot learn preferences over the collaboration, alongside traditional explicit feedback. We evaluate this idea in a laboratory, where participants assemble pizzas with a robot and can give explicit feedback by pressing buttons.
    </td>
  </tr>
</table>


Please see our paper for additional details.

**Citation**

Kate Candon, Qiping Zhang, Alexander Lew, Houston Claure, Lena Qian, Alyssa Quarles, Chayan Sarkar, and Marynel Vázquez. 2026. **Learning Human Preferences Over a Human-Robot Collaboration Based on Explicit and Implicit Human Feedback**. In *Proceedings of the 21st ACM/IEEE International Conference on Human-Robot Interaction (HRI ’26)*, March 16–19, 2026, Edinburgh, Scotland Uk. ACM, New York, NY, USA, 10 pages. https://doi.org/10.1145/3757279.3785630
