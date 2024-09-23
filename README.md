# ml_work
a custom activation function 

In this paper, we propose a custom activation function designed for multiclass classification tasks, particularly suited for datasets like Iris, which contains non-linearly separable classes. The custom function is a combination of a linear term k_0∙x and a non-linear exponential decay term α∙e^(〖-x〗^2 ), providing flexibility in balancing linear and non-linear responses. This activation function addresses the need for gradient stability, allowing effective learning without vanishing or exploding gradients, and proves to be particularly beneficial for multiclass problems. Experimental results on the Iris dataset show that this function performs effectively in capturing both linearly separable and non-linearly separable classes.
