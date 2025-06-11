# ee5178-assignment-2--canny-edge-detection-solved
**TO GET THIS SOLUTION VISIT:** [EE5178 Assignment 2- Canny Edge Detection Solved](https://mantutor.com/product/ee5178-programming-assignment-2-canny-edge-detection-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;98591&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;5&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (5 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EE5178  Assignment 2- Canny Edge Detection Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (5 votes)    </div>
    </div>
Note:

2. Submit a single zip file in the moodle named as PA1-Rollno.zip. Submit your detailed answers in PDF format and your code with relevant output in a Jupyter Notebook. Kindly comment your code generously.

3. Read the problem fully to understand the whole procedure.

1. You are required to implement the canny edge detection algorithm as described in class. Please follow the steps mentioned below.

(a) Read the image ‘clown.jpeg’ and display it.

(b) Convert it into a grayscale image.

(c) To suppress the noise use a Gaussian kernel to smoothen it. Keep the

kernel size as 5 x 5 and sigma = 1.5.

(d) Apply the standard Sobel operator Gx and Gy discussed in class. Display the filtered outputs. Also show the gradient magnitude and angle images.

(e) Apply non-maximum suppression as discussed in class. The exact method requires computing the imaginary pixels shown in gray in the image below using interpolation methods such as bilinear and bicubic interpolation. As a simplification just locate the image pixels which are spatially closest to the imaginary gray pixels and use those pixels as the neighboring pixels for non-maxima suppression. This way you can bypass the interpolation step and have a computationally lighter method if you so desire. Show the NonMaximum Suppression output.

1

Figure 1: The exact method requires you to do interpolation. As an alternative adopt the simplified approach described in Step (e).

(f) Instead of using the Double thresholding Hysteresis used in the exact algorithm simply do a single thresholding operation. Pixels with values less than the threshold should be suppressed. Use the median value of the magnitude image computed in Step 4 as the threshold value. Show the final output.

2. Repeat the above question but increase the sigma of the Gaussian kernel to 3. Choose your filter size appropriately. Just show the final output for this question. How does the final output differ from that of the previous question?

1
