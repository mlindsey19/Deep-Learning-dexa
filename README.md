# Deep-Learning-dexa


Training time was much longer with smaller batch size. Batch normilazation increased error on small btach size as well. With a batch size of 8 and no batch normilazaition, similar results were observed but with much longer training times.

Summary
The Final achetechure of RNN is 10 residual loops - this seemed maximize R² and minimize MSE. The firrst two layers work best with 15 - 16 nodes, reducing or increasing these layers increased MSE. After leanring from those, larger dense layers seem to help increase R².

A module of the following study used simliar data points to predect fat mass, free fat mass, truckfat and weight. Linear regession was used. The results are not directly comparable and their results were used in a diebeties predition model so this is not a good bench mark. Anthropometric Variables Accurately Predict Dual Energy X-Ray Absorptiometric-Derived Body Composition and Can Be Used to Screen for Diabetes

However, a simple linear regression was used with the same data set. Without optimizing the regresion model, the RNN has a higher R² score and a lower mean squared error. Even the first NN out performed simple linear regression.
