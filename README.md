# VEHICLE-DAMAGE-INSURANCE-CLAIM-VERIFICATION-USING-CONVOLUTIONAL-NEURAL-NETWORKS

This study presents the development of a Convolutional Neural Network (CNN) designed to
classify various types of vehicle damages based on image data. The model is trained to iden�fy
six distinct damage categories: crack, scratch, flat tire, dent, glass shater, and broken lamp.
The CNN architecture consists of multiple convolutional layers, pooling layers to reduce spatial
dimensions progressively, and dense layers with ReLU actvaton functions, followed by a
softmax output layer for multi-class classificaton. To enhance the model's generalization
capabilites and prevent overfitng, regularizaton techniques such as dropout and data
augmentaton were applied. Hyperparameter tuning, including learning rate and batch size
adjustments, was conducted to optmize model performance. The model was trained using
the Vehicle Damage Insurance Verificaton dataset from Kaggle, achieving a weighted average
F1-score of 0.91 and an overall accuracy of approximately 91%. The study emphasizes the
importance of the chosen architecture, training strategies, and evaluaton results, oﬀering
insights into areas for future improvements, such as dataset augmentaton and the
exploraton of advanced CNN architectures. This work provides a foundaton for automated
insurance claim verificaton systems.
