# civil459-homework-3-convolutional-neural-network-solved
**TO GET THIS SOLUTION VISIT:** [CIVIL459 Homework 3-Convolutional Neural Network Solved](https://www.ankitcodinghub.com/product/civil459-homework-3-convolutional-neural-network-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94038&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CIVIL459 Homework 3-Convolutional Neural Network Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Problem Set 3 – Convolutional Neural Network

</div>
<div class="column">
Figure 1: Convolution

</div>
</div>
<div class="layoutArea">
<div class="column">
This time we’ll check out how to build a convolutional network to classify CIFAR10 images. By using weight sharing – multiple units with the same weights – convolutional layers are able to learn repeated patterns in your data. For example, a unit could learn the pattern for an eye, or a face, or lower level features like edges.

Traditionally, convolutional layers are followed by max-pooling, where values in the convolu- tional layer are aggregated into a smaller layer shown in Figure 2. These types of networks become really useful when you stack a bunch of layers, you make the network deeper. Typically you’ll use a convolutional layer to change the depth, ReLU activation, then a max-pooling layer to reduce the height and width.

To finish off the network, you need to flatten the final convolutional layer into a normal fully- connected (dense) layer, then add more fully-connected layers as a classifier. The convolutional layers act as feature detectors that the classifier uses as inputs. Convolutional networks have been massively effective in image classification, object recognition, and even in natural language

1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Figure 2: Convolutional Neural Network

processing applications like speech generation.

Building this new network is pretty much the same as before, but we use nn.Conv2d for the

convolutional layers and nn.MaxPool2d for the max-pooling layer.

What to do

Get the codes from “https://github.com/vita-epfl/DLAV-2022” and implement the convolutional neural network using pytorch in CNN Exercise.ipynb

<ol>
<li>Define the different layers of the neural network. The neural should have at least 2 layers but can be as large as you want.</li>
<li>Set up the forward pass by connecting the different layers of the neural network. Note: Do not forget to use activation layers.</li>
<li>Choose a loss function and an optimizer.You can tune the parameters of the optimizer.</li>
<li>Implement the training process and save your best model.
Finally, for us to test your code and get an accuracy, you should fill the evaluator notebook where you should load the saved model, input to it the data and get the prediction labels. We will be using our own test data for grading.
</li>
</ol>
Deliverables

You need to submit the jupyter notebooks and the trained models into the moodle.

Helpful References

• Pytorch Documentation: https://pytorch.org/docs/stable/

• Pytorch Tutorial: Official link, Collection

• Pytorch Convolution Layers: http://pytorch.org/docs/master/nn.html#convolution-layers

</div>
</div>
</div>
