# deep_learning_resources

A collection of useful deep learning resources.

## Textbooks

| Book Name                                                    | Author                                            | Year                | Availability                                                 | Comment                                                      |
| ------------------------------------------------------------ | ------------------------------------------------- | ------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Deep Learning                                                | Ian Goodfellow, Yoshua Bengio and Aaron Courville | 2016                | Free at https://www.deeplearningbook.org; Also available on [Amazon](https://www.amazon.com/Deep-Learning-Adaptive-Computation-Machine/dp/0262035618/ref=sr_1_1?ie=UTF8&qid=1472485235&sr=8-1&keywords=deep+learning+book) | Build strong math fundations for Deep Learning               |
| Dive into Deep Learning                                      | Aston Zhang, Zack Lipton, Mu Li and Alex Smola    | 2024 (keep updated) | Open-source at https://d2l.ai                                | Good for hands-on learning: **Interactive** deep learning book with **code**, math, and discussions. Implemented with **PyTorch**, **NumPy/MXNet**, **JAX**, and **TensorFlow** |
| Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow, 3rd Edition | Aurélien Géron                                    | 2022                | Book can be purchased from [Amazon](https://www.amazon.com/_/dp/1098125975?smid=ATVPDKIKX0DER&_encoding=UTF8&tag=oreilly20-20); Code available at https://github.com/ageron/handson-ml3 | Deep Learning in Python using Scikit-Learn, Keras and **TensorFlow 2**. |



## Computational Resources

1. Free
   1. Google Colab (https://colab.research.google.com) gives one Nvidia T4 GPU or a TPU for about 6 hours at a stretch. You can also connect VS Code to your Colab instance and code using standard Python files.
   2. Gradient (https://gradient.paperspace.com) has more generous compute resources (6-hour timeouts and persistent sessions) than Goolge Colab.
   3. Kaggle Notebooks (https://www.kaggle.com/docs/notebooks) are similar to the above two with slightly less resources (~2 hour limit for GPU, 10 hour limit for CPU which is good enough for debugging).
   4. AWS SageMaker Studio Lab (https://studiolab.sagemaker.aws/) is another way to run things for free. An important benefit of this is that unlike the 3 services above, your data is preserved across different sessions.
   5. Google Cloud Project gives $300 of starter credits (https://cloud.google.com/free)

2. Paid
   1. Google Colab Pro (https://colab.research.google.com/signup): a very reasonable $10/month which gives you access to faster GPUs (V100, A100) and less restrictive pre-emption of jobs. A number of people on the internet have complained that it is not much better than the free version but Google keeps improving their system, so you could try for a month or so and check it out.



## References

1. ESE 546 Principles of Deep Learning Syllabus by Pratik Chaudhari (https://pratikac.github.io/)



## Disclaimer

This project is intended for educational purposes only. It is not affiliated with, endorsed by, or officially connected to all resources mentioned above. All product names, logos, and brands are property of their respective owners. Their use in this project is for identification and learning purposes only and does not imply endorsement.