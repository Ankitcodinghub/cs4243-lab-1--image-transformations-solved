# cs4243-lab-1--image-transformations-solved
**TO GET THIS SOLUTION VISIT:** [CS4243 Lab 1- Image Transformations Solved](https://www.ankitcodinghub.com/product/cs4243-lab-1-image-transformations-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;113958&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS4243  Lab 1- Image Transformations Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Objective

The objective of this lab is to familiarize yourself with basic image processing and transformation operations. The lab has three parts:

1. Histogram Normalization &amp; Equalization

2. Gaussian &amp; Laplacian Image Pyramids

3. Image Blending

You are free to use any functions in numpy to help you, but other built-in functions for image processing are not allowed. If you are new to Python and Jupyter Notebooks, please review the materials in the Python Refresher in LumiNUS¿Files¿Labs to help you start your work.

Part 1: Histogram Equalization and Normalization (35%)

In this part, you are asked to implement the following 5 functions: cs4243 resize(), cs4243 rgb2grey(), cs4243 histnorm(), cs4243 histequ() and cs4243 histmatch(). The expected outcomes of each function are shown in in Fig. 1 and main.ipynb. The code skeletons for the functions are given in transform.py.

For simplicity, we consider only greyscale images in this lab. Given a colour image, first resize it to a smaller image and then convert it from RGB to greyscale. Afterwards, perform histogram normalization, equalization or matching to enhance the image contrast. Image normalization (equalization) is to stretch the range of image intensity linearly (uniformly). Histogram matching is to make the image histogram match with the histogram of the reference image, which means that you have to find a mapping of intensity between two images according to their cumulative histograms.

Figure 1: Image histogram normalization, equalization and matching.

Figure 2: Gaussian &amp; Laplacian Pyramid.

Part 2 Gaussian and Laplacian Pyramid (55%)

Part 3 Image Blending (10%)

One neat use for Laplacian image pyramids is to blend two images together (see Fig. 3). For image blending, you separately build the Laplacian pyramids for the two constituent images and linearly combine them different pyramid levels during reconstruction.

Figure 3: Apple and orange blending example.

The general approach for image blending is as follows:

1. Construct Laplacian pyramids LA and LB from composing images A and B.

2. Build a Gaussian pyramid GR on a mask R which selects the pixels coming from A vs B

3. Construct a combined pyramid Lc from La and Lb by using the elements of GR as weights, where Lc(i, j) = GR(i, j) ∗ LA(i, j) + (1 − GR(i, j)) ∗ LB(i, j)

4. Reconstruct belended image from Lc.

An example of linearly combining two images with a mask is given in main.ipynb.

Useful Resources and Extension Reading

Nearest-Neighbour Image Resizing [link]

Histogram Equalization[link]

Histogram Normalization[link]

Histogram Matching[link]

Image Filtering[link]

Blending[link]

Hand in
