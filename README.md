# AdversarialAttack_RL


Supervised learning using cross-entropy loss has
achieved excellent results in classification tasks.
However, it has the disadvantage of overly depending on the labeled data such that adversarial samples can make the trained model to have mistakes.
Our study shows that using reinforcement learning
for classification tasks can achieves better robustness against adversarial attacks without sacrificing
accuracy. A policy loss in reinforcement learning
deforms the landscape of the overall loss, which
leads to various advantageous searches in the policy
search space. In addition, in order to use reinforcement learning for multiclass classification tasks, we
propose a new training strategy in which a derived
policy loss function is used to improve the accuracy
and robustness of the model against adversarial attacks. Evaluations regarding flatness and adversarial defense on the MNIST and CIFAR-10 datasets
give promising results, in which the model trained
by a policy loss becomes robust to an adversarial
attack.
