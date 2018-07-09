# Chicken Wing vs Chicken Nugget Identifier
A deep learning CNN that identifies an image as either a deep fried chicken wing or a chicken nugget. Although seeming pointless, it's one step closer for me to create my own rock classifier.

#### Sources of Error
Images were collected accross 4 different search engines meaning that some images may have been duplicates resulting in over-filling. Over-filling may also have been caused by the extremly low sample size I was able to provide. To account for this less epochs were used and distortions were applied but to no availe. This is seen in the *99%* evaluation accuracy that the model ended with.

Adding a drop-out layer to disable some neurons during training may aleviate the over-filling and will be taken note of in future projects. Drop-out was not initially used because of the small dataset I was expecting a lower learning rate.
#### Training Settings
Optimizer: adam

Loss: binary corssentropy
#### Libraries
>Keras

>Tensorflow
