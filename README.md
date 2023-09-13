# Demonstration-of-Artificial-Neural-Network
Creating a Model using Artificial Neural Network for digit prediction using mnist dataset of keras.

Important commands used:
1.(X_train,y_train),(X_test,y_test)=keras.datasets.mnist.load_data() to load the mnist dataset
2.plt.matshow(X_train[0]) for visual representation of the first image of X_train.
3.model1=keras.Sequential([keras.layers.Dense(10,input_shape=(784,),activation='sigmoid')]) to create a ann 
4.model1.compile(optimizer='adam',loss='sparse_categorical_crossentropy',metrics=['accuracy']) for compiling we mention values of optimizer,loss type and metrics.
5.model1.fit(X_train_flattened,y_train,epochs=5) Fitting
