# deep-learning
first projrct. convert c to f
import tensflow as tf
import numpy as np
c=np.array([0,32,40,50])
f=np.array([32,89,104,122])

10=tf.keras.layers.Dense(unit=1,input_shape=[1])
model=tf.keras.sequential([10])
model.compile(loss='mean_squared_error',optimizer=tf.keras.optimizers.Adem(0.1))
model.fit(c,y,epochs=500,verbose='False')
