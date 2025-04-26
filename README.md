# cs590-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [CS590 Assignment 3 Solved](https://www.ankitcodinghub.com/product/cs590-gavin-witsken-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;131843&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS590 Assignment 3 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
Assignment 3 Responses

1. Shallow neural networks are simple and typically contain only a single hidden layer between input and output, but deep neural networks can contain many more hidden layers that perform different transforma6ons and opera6ons on the data before reaching the output layer.

2. In neural networks, training occurs as a series of steps. First is the process of forward propaga2on, where data is fed into the input layer, through a series of hidden layers, where weights, biases, and ac6va6ons are applied. Upon reaching the output layer, the predic6on is made and forward propaga6on has completed.

Then, the process of back propaga2on occurs where a loss func6on is used to determine how erroneous the predic6on was. The gradient of the loss func6on is calculated with regard to the weights and biases of the network. Some kind of op6miza6on algorithm like gradient descent, stochas6c gradient descent, or Adam is used to update the pervious values of the weights and biases so the network can “learn” from its errors. This process of the forward propaga6on followed by back propaga6on will iterate un6l an acceptable end state is reached.

3. Ac6va6on func6ons are used to introduce some non-linearity to the output of the neurons to bePer represent curves of real data as well as controlling which data actually gets sent through the network.

4. Some common hyperparameters include learning rate, epoch, batch size, ac6va6on func6on, loss func6on, regulariza6on func6ons/techniques.

5. OverfiVng is when the model is too complex and fits too closely to the (usually training) data, meaning that it will not work well on new data and will have high variance (very nonlinear). UnderfiVng is the opposite, where the model is too biased toward a simple paPern cannot effec6vely represent nonlinear rela6onships within the data.

6. OverfiVng is o[en mi6gated through techniques like regulariza6on and dropout, to help ensure that the model does not fit too closely to the training data.

7. The vanishing gradient problem is a scenario where the loss gradients get very small, almost to zero, during backpropaga6on. This happens o[en in networks with many layers, rapidly shrinking the shape of the data from input to output. This can be mi6gated through using ac6va6on func6ons like ReLU to restrict which informa6on passes through the network.

The exploding gradient problem is the opposite scenario, where the loss gradients get very large, and the model becomes very unstable. Techniques like gradient clipping to clamp the values of gradients help mi6gate this unstable growth behavior.

8. Batch normaliza6on is a technique which helps improve the efficiency of the training process of neural networks. This opera6on is applied to individual layers of the network. Each mini-batch is normalized, then scaled and shi[ed according to learned scaling and shi[ing parameters. This allows for efficient learning with higher learning rates, lower internal covariate shi[, mi6ga6on of exploding and vanishing gradient problems, and reduced need for other regulariza6on techniques.

9. A Convolu6onal Neural Networks consists of a series of different types of layers, each type performing a certain role.

The convolu6onal layer is the namesake of this type of neural network, which performs the convolu2on opera6on, which slides some number of kernels (filters) over the input data, crea6ng a feature map. It u6lizes parameters like kernel size, stride, and padding.

The pooling layer is another type of layer in a CNN which is used to effec6vely compress the input data into a smaller representa6on (output data). This makes computa6ons more efficient and some6mes removes unwanted noise. These are o[en placed between consecu6ve convolu6on layers.

The fully-connected layer is another type of layer which will typically occur near the end of the Network. These work on a flaPened version of the previous data, and are used to effec6vely make the higher-level predic6ons that we want the network to perform.

11. Convolu6onal neural networks can generally perform image processing tasks more efficiently than tradi6onal image processing techniques because they require less pre-processing and are automa6cally able to learn hierarchical feature representa6ons and can operate largely unsupervised by humans.

12. Different techniques can be used to effec6vely ini6alize values in a network. O[en, some sort of randomized distribu6on is a bePer star6ng point than just star6ng everything at zero. However, the proper ini6aliza6on technique depends heavily on the task at hand and the types of opera6ons the network is performing.

13. Some popular CNN architectures include AlexNet, VGG, and ResNet. Each of these model architectures were designed for different tasks and involve different combina6ons of convolu6on, pooling, and fully-connected layers.

14. Batch size is the number of training examples which are used in calcula6ng the loss func6on gradient before propaga6ng the informa6on back and upda6ng the weights of the model. In theory, larger batch sizes will give a more accurate es6mate of the loss func6on gradient, they will o[en realis6cally perform worse in generaliza6on to new data compared to smaller batch sizes.

15. When choosing the op6mal batch size, various things must be considered like capability of the hardware, learning stability, and model generaliza6on. Hyperparameter tuning techniques like grid search or Bayesian op6miza6on are o[en used to determine this ideal batch size.

16. Some common use cases for CNNs aside from image classifica6on are natural language processing, speech recogni6on, and 6me series analysis. We used it in class for DNA accessibility classifica6on.

17. Some techniques o[en used in hyperparameter tuning are grid search, random search, Bayesian op6miza6on, or simulated annealing. Similar to tuning of hyperparameters themselves, choosing the ideal op6miza6on techniques depends on various factors like hardware capability, necessary opera6ons, and scale of data.

18. Early stopping involves the use of a valida6on set during training, which is used to mi6gate overfiVng in the model based on some desired heuris6c(s) for which a stopping point is usually defined.

19. Data transforma6on is the processing of taking some input data and conver6ng into a format which is more easily usable for analysis. This can involve removing unnecessary features associated with the data, enumera6ng features that can be enumerated, aggrega6ng data into summary measures, and much more. This transforma6on is o[en necessary for effec6ve performance in a neural network model.

20. Some common transforma6on techniques include normaliza6on, scaling, encoding, rota6ng, discre6za6on, enumera6on, aggrega6on, imputa6on, and much more.

21. Effec6ve data transforma6on can help to op6mize the data representa6on into a

state which is more meaningful in regard to rela6onships between features, efficiency in training, and far higher quality for solving par6cular tasks. Poor transforma6on can easily do the opposite, adding unnecessary noise or removing poten6ally useful features.

24. DNase-seq is an experimental DNA accessibility assessment technique with u6lizes the DNase I enzyme to selec6vely cleave DNA where it is not protected by nucleosomes or other proteins (meaning it is an open, accessible chroma6n region). ATAC-seq is another technique, but it uses a hyperac6ve Tn5 transposase to essen6ally tag open regions of the chroma6n which will highlight these accessible regions compared to the protected, inaccessible regions.

25. A BED file is a tab-separated-value (TSV) file with a single sequence entry per line. Each entry will contain columns for the name of the chromosome, the start posi6on of the chromosome, and the end posi6on of the chromosome, as well as various other op6onal fields.

26. To create the nega6ve (inaccessible region) BED file, we simply take the range between the end of the original accessible region and the start of the next accessible region for the same chromosome. We must validate that the values follow the proper bed format rules (no invalid ranges), and then we have generated a valid inaccessible region for our new BED file.

27. Bedtools is used to compare our regions against a reference genome and subs6tute the regions indicated in our bedfiles with the actual sequence of nucleo6des which exist in that range within the genome. This is crucial so we can learn the paPern of the data with our model.

28. Nucleo6des are the basic building blocks of DNA. DNA consists of four different types of nucleo6des (Adenine, Thymine, Guanine, Cytosine). There are 23 chromosome base pairs in the human genome.

30. The coding regions of DNA contain the instruc6ons for protein synthesis, which is used to describe how proteins and cells are to be synthesized, which is the basis for growth and development in organisms.

32. Data must be converted to a tensor for use in pytorch because the pytorch library is designed to effec6ve handle parallelized computa6ons, typically leveraging the power

of the GPU’s many simple, focused cores to perform computa6ons. The tensor data structure allows for computa6on to be vectorized, and thus parallelized for great efficiency compared to standard sequen6al computa6on. These kinds of calcula6ons are incredibly common in deep learning.

33. If we ploPed our model’s loss with respect to the epoch, we would ideally no6ce a decreasing trendline (nega6ve slope). This would indicate that our model is performing bePer (less loss, bePer accuracy) as we run consecu6ve training itera6ons.

34. In deep learning, a valida6on set is useful for many kinds of tuning and op6miza6ons that we want to perform with our model. First and foremost, the valida6on set is useful for hyperparameter tuning. By checking performance of different hyperparameter values on a test data set and comparing the results to a valida6on set, the hyperparameter values can be tweaked according to this performance discrepancy to achieve more desirable results from the model.
