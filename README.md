# FLiText
Chaged **epoch** from 10 to 50 for a better fitting.

According to the max accuracy in original experiment record's, we chage the defult **loss** form "hard" to "logit" in imdb task, and **cnn_kernel_size** as well as the **transformer_layers** are also chaged from [2,3,4,5],[5,7,9,11] to [0,1,2,3,4,5],[1,3,5,7,9,11].

In **20** labels, IMDB task reached **90.498** at 33rd epoch under the current setting.

In **500** labels, IMDB task reached **90.494** at 39rd epoch, but the CNN_kernel_size and Transformer_layers are set as [2,3,4,5] and [5,7,9,11] respectively.

In **2500** labels, IMDB task reached **90.54** at 50th epoch.
