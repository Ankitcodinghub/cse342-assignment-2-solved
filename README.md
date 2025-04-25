# cse342-assignment-2-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/cse342-sml-solved-2/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;128568&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE342 Assignment 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
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
    
<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (2 votes)    </div>
    </div>
1 Instructions

• You can use inbuilt libraries for Math, plotting, and handling the data (eg. NumPy, Pandas, Matplotlib).

• Usage instructions for other libraries can be found in the question.

• Only (*.py) files should be submitted for code. • Create a (*.pdf) report explaining your assumptions, approach, results, and any further detail asked in the question.

• You should be able to replicate your results during demo.

2 Question-1

Use https://storage.googleapis.com/tensorflow/tf-keras-datasets/mnist.npz MNIST dataset for this question and perform following tasks. • It has all in all 60K train samples from 10 classes and 10K test samples. 10 classes are digits from 0-9. Labels or classes for all samples in train and test set is available.

• Visualize 5 samples from each class in the train set in form of images.

• Find the class of all samples in test set. Report accuracy and class-wise accuracy for testing dataset. Accuracy is ratio of total number of samples correctly classified to the total number of samples tested. Total number of samples tested is 10K. Similarly, for each class report the accuracy. Note the labels or classes for each sample is given in the dataset.

1

3 Question-2

Use same downloaded dataset from Question 1 and perform following tasks.

• Choose 100 samples from each class and create a 784×1000 data matrix. Let this be X.

• Remove mean from X.

• Apply PCA on the centralized X. You need to compute covariance S = XX&gt;/999. The find its eigenvectors and eigenvalues. You can use any library for this. Sort them in descending order and create matrix U.

• Perform Y = U&gt;X and reconstruct Xrecon = UY . Check the MSE between X and Xrecon. This should be close to 0. MSE = Pi,j(X(i,j) −

Xrecon(i,j))2.

• Now chose p = 5,10,20 eigenvectors from U. For each p, obtain UpY , add mean that was removed from X, reshape each column to 28×28, and plot the image. You should see that as p increase the reconstructed images look more like their original counterparts. Plot 5 images from each class.

• Let test set be Xtest. Find . For each value of p find Y , and apply QDA from Q1 on Y. Obtain accuracy on test set as well as per class accuracy. As p inreases, accuracy shall increase.

2
