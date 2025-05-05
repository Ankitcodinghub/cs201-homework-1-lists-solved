# cs201-homework-1-lists-solved
**TO GET THIS SOLUTION VISIT:** [CS201 Homework 1-Lists Solved](https://www.ankitcodinghub.com/product/cs201-homework-1-lists-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;102241&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS201 Homework 1-Lists Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

This write-up has 3 parts. The first part provides an explanation of your implementation tasks. It refers to code that is provided in the appendices in the third part. The second part lists the tasks for you to do. It contains space for you to enter your solutions to some of the problems. The third part lists code which is referred to in the first part.

You have to fill in the solutions in the second part, and complete the code files in the accompanying src/ folder as described in Part 1. Please work in this file, hw1.tex, and not in a copy. When submitting, please remove the first and third parts from this file.

Part I Explanation

In this assignment, we will implement an ArrayList to represent a List. We will use the List to implement an image and will write operations for the image.

1 Image Operations

We will work with RGB images and perform four operations on them–channel suppression, rotations, mask application, and resize. None of these operations is destructive. That is, the operations do not alter the original image, rather they return a new image containing the result of the operation.

1.1 Channel Suppression

An image is said to contain color values in different channels. In an RGB image, the channels are Red, Blue, and Green. Each channel contains the intensities for that color for every pixel in the image. The values from all three channels at a pixel yield the RGB value at the pixel. A channel suppression operation switches off a specific channel. That is, all intensities in that channel are turned to zero, or turned off. Figure 1 shows an original image and two modifications, one with the blue channel turned off, and the other with only the blue channel turned on, i.e. the red and green channels turned off.

1.2 Rotation

Given a square image, i.e. one whose width is equal to its height, this operation generates a new image that contains rotations of the original image. Figure 2 shows an example of applying the operation. The resulting image has twice the dimensions of the original image, i.e. twice the width and twice the height. It contains 4 appropriately placed sub-images which, going anti-clockwise are the original image rotated anti-clockwise by increments of 90◦.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
(a) An RGB image of a swimming (b) The image with the blue chan- (c) The original image with only

</div>
</div>
<div class="layoutArea">
<div class="column">
pool.

</div>
<div class="column">
nel turned off. the blue channel turned on.

Figure 1: Example of channel suppression.

</div>
</div>
<div class="layoutArea">
<div class="column">
1.3

</div>
<div class="column">
Applying a Mask

</div>
</div>
<div class="layoutArea">
<div class="column">
(a) A square image.

</div>
</div>
<div class="layoutArea">
<div class="column">
(b) The image obtained as a result of ap- plying rotations to the original image.

Figure 2: Example of rotation.

</div>
</div>
<div class="layoutArea">
<div class="column">
A mask specifies certain weights and applying the mask to an image entails replacing the value at each pixel in the image with a weighted sum or weighted average of the values of its neighbors. The weights and the neighbors to consider for the average are specified by the mask.

A mask is an n × n array of integers representing weights. For our purposes, n must be odd. This means that the n × n array has a well defined center–the origin. The weights in the mask can be arbitrary integers–positive, negative, or zero.

For each pixel in the input image, think of the mask as being placed on top of the image so its origin is on the pixel we wish to examine. The intensity value of each pixel under the mask is multiplied by the corresponding value in the mask that covers it. These products are added together. Always use the original values for each pixel for each mask calculation, not the new values that you compute as you process the image.

For example, refer to Figure 3a, which shows the 3 × 3 mask,

131 353 131

and an image on which we want to perform the mask computation. Suppose we want to compute the result of the mask computation for pixel e. This result would be:

a+3b+c+3d+5e+3f +g+3h+i

Some masks require a weighted average instead of a weighted sum. The weighted average in the case of Figure 3a for pixel e would be:

a+3b+c+3d+5e+3f +g+3h+i 1+3+1+3+5+3+1+3+1

</div>
</div>
<div class="layoutArea">
<div class="column"></div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
<div class="layoutArea">
<div class="column">
(a) Overlay the 3×3 mask over the image so it is centered on pixel e to compute the new value for pixel e.

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 3: Applying a mask to an image.

Instead of doing this calculation for each channel individually at a pixel, for the purpose of this calculation, replace the value of each channel at the pixel with the average channel value at the pixel. For example, if the pixel is given by (r, g, b) = (107, 9, 218), then apply the mask to the average value (107 + 9 + 218)//3 = 111 (integer division) and copy the result to each channel of the corresponding pixel in the output image. This effectively converts the output image to grayscale.

Note that sometimes when you center the mask over a pixel, the mask will hang over the edge of the image. In this case, compute the weighted sum of only those pixels that the mask covers. For the example shown in Figure 3b, the weighted sum for the pixel e is given by:

</div>
</div>
<div class="layoutArea">
<div class="column">
and the weighted average is as follows.

</div>
<div class="column">
3b+c+5e+3f +3h+i

3b+c+5e+3f +3h+i 3+1+5+3+3+1

</div>
</div>
<div class="layoutArea">
<div class="column">
(b) If the mask hangs over the edge of the image, use only those mask values that cover the image in the weighted sum.

</div>
</div>
<div class="layoutArea">
<div class="column">
Integer division is used when computing averages in order to ensure that pixel intensities are integers.

1.3.1 Applications of Masks

Applying different masks leads to different properties. For example, applying the following mask leads to blurring of the image. Figures 4a and 4b show the blurring effect of this mask. Note that color information

</div>
</div>
<div class="layoutArea">
<div class="column">
is lost as mentioned above.

</div>
<div class="column">
24542 4 9 12 9 4 5 12 15 12 5. 4 9 12 9 4

24542

</div>
</div>
<div class="layoutArea">
<div class="column">
Another application we use is an implementation of Canny Edge Detection using Sobel Operators. Once the image has been blurred as above, two more filters, or masks, (the Sobel operators) are applied in succession to the blurred image. These filters determine the change in intensity, which approximates the

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
(a) An image with sharp details and several lines.

</div>
</div>
<div class="layoutArea">
<div class="column">
(b) Result of applying the blur mask (c) Result of applying the Sobel fil- to the original image. ters to the blurred image.

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 4: Blurring and detection of edges in an image using masks. horizontal and vertical derivatives.

−1 0 1 −1 −2 −1 Gx=−2 0 2, Gy= 0 0 0 .

−1 0 1 1 2 1

After these operations are applied one after the other to the blurred image, the values obtained are used to search for edges based on the magnitude and direction of the change in intensity. An example of the final result is shown in Figure 4c.

1.4 Resize

Given an image, this operation generates a new image that has twice the dimensions of the original image i.e, twice the width and twice the height. Figure 5 shows a 4×3 image which is resized to twice its size. The resized image has 4 times as many pixels and some of them take on the values from the original image as shown. For the pixels shown to be blank, color values are not known and have to be computed from the known values. Consider the labeled pixels in the resized image below. One way to fill in the missing color information is as follows.

P = 21 ( A + B ) , T = 12 ( C + D ) , Q = 21 ( A + C ) , S = 12 ( B + D ) Page 4 of 20

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 5: Bilinear Interpolation

There are various ways to compute R, all of which are ultimately equivalent.

R= 12(P+T)= 12(S+Q)= 14(A+B+C+D)= 14(P+Q+S+T)= 18(A+B+C+D+P+Q+S+T)

The boundary pixels pose a problem as some of the neighboring pixels required for the average do not exist. In such cases, only the existing neighbors are used for the average.

Notice how all the above expressions are affine combinations. Furthermore, the colors for P, Q, S, and T are linearly interpolated from their horizontal or vertical neighbors. The color for R is a bilinear interpolation: it is a linear interpolation of P and T, or Q and S, which are themselves linear interpolations.

Note: All divisions in the above expressions are integer divisions.

2 Image

We treat an image as a grid of pixels where each pixel is represented as an RGB value indicating the red, green, and blue intensities of the pixel. An image has dimensions, namely width and height, which determine the number of rows and columns in the image. Every pixel in the image is at a unique combination of row and column numbers which can therefore be used as a coordinate system in the image. An image with width w and height h is said to be of size w×h. Figure 6a shows the column and row numbers in a w×h image along with the resulting pixel coordinates. Note that the coordinate is just a means to locate a pixel in the image, it is not the value stored at the pixel. The value stored at a pixel is a triplet denoting the red, green, and blue intensities respectively.

We will work with a flattened representation of an image. That is, we will store the pixel values in a 1-dimensional list structure as opposed to a 2-dimensional structure (programming languages generally store multi-dimensional arrays in their flattened form) . The list stores pixel values as they appear in the image from left to right and top to bottom. Figure 6b shows a 5 × 5 image with some supposed RGB values. Note that each value would be a triplet of integers, each integer between 0 and 255 inclusive. Using our representation, the image in Figure 6b will be represented as the list:

[a,b,c,d,e,f,g,h,i,j,k,l,m,n,o,p,q,r,s,t,u,v,w,x,y]

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="section">
<div class="layoutArea">
<div class="column">
Spring 2023

</div>
</div>
<div class="layoutArea">
<div class="column">
<ol start="0">
<li>0 &nbsp;(0,0)</li>
<li>1 &nbsp;(1,0)</li>
<li>2 &nbsp;(2,0)</li>
</ol>
</div>
<div class="column">
(0,1) (0,2) … (1,1) (1,2) … (2,1) (2,2) …

</div>
<div class="column">
(0,w − 1) (1,w − 1) (2,w − 1)

</div>
</div>
<div class="layoutArea">
<div class="column">
Columns

0 1 2 … (w−1)

</div>
<div class="column">
abcde fghij klmno pqrst uvwxy

</div>
</div>
<div class="layoutArea">
<div class="column">
……. ……

</div>
</div>
<div class="layoutArea">
<div class="column">
(h − 1) (h − 1, 0) (h − 1, 1) (h − 1, 2) . . . (h − 1, w − 1)

(a) Row and column numbers of an image with width w and height h. Pixel (b) A 5 × 5 image with supposed

coordinates are also shown. pixel values.

Figure 6: Image dimensions and pixel coordinates.

3 Implementation Details and Tasks

We will be working with a MyImage class as shown in Listing 1 on Page 9, also included in the accompanying file src/myimage.py. Its implementation is complete but requires a concrete implementation of MyList which is our implementation of the List interface. The implementation to be used is specified in the constructor of MyImage.

An implementation of MyList is shown in Listing 2 on Page 12, also included in the accompanying file src/mylist.py. The implementation is mostly complete except for the segments marked as pass. These are to be implemented appropriately in the subclasses of MyList which are indicated at the end of the listing and whose implementation is completely missing. Writing their implementations is one of your tasks in this assignment.

Once you are done implementing MyList subclasses, the MyImage class is ready to be operated on. Functions corresponding to the operations described in Section 1 are shown in Listing 3 on Page 16 and included in the accompanying file src/image operations.py. None of the operations is destructive. That is, each operates on a MyImage instance and returns the result as a new MyImage instance. The functions are missing implementations. Writing their implementations is another of your tasks in this assignment.

3.1 Tasks

<ul>
<li>􏰃 &nbsp;Go over the provided files thoroughly in order to understand what they do or are expected to do.</li>
<li>􏰃 &nbsp;Provide implementations for unimplemented methods, i.e. those that have pass in their body.</li>
<li>􏰃 &nbsp;Derive ArrayList class from MyList and provide its implementation in the same file. ArrayList implements the list using python arrays.
3.2 Requirement

You will need to install Pillow which will prove the PIL module used in the provided code. 3.3 Tips

Below are some tips to avoid the errors that have previously caused tests to fail. Following these may save you many frustrating hours of debugging!
</li>
</ul>
<ul>
<li>􏰃 &nbsp;Delay division as much as possible and perform int division wherever needed.</li>
<li>􏰃 &nbsp;When writing gray values to file, make sure to clamp them to [0,255].</li>
<li>􏰃 &nbsp;Take care about imagine indexing.</li>
<li>􏰃 &nbsp;Be careful when creating a copy of the image. Use the copy where needed and the original where needed.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column"></div>
</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
􏰃 Do not forget to average the RGB values when the corresponding flag in apply_mask is enabled.

􏰃 Take care about efficiency. Some structures are slow. If, on top, your code is inefficient, the automated tests may fail due to time out.

3.4 Testing

Once you have successfully implemented the subclasses and image operations, you can test your code by creating an image and performing operations on it. Your submission will be tested automatically by GitHub using the accompnaying pytest file, test image.py.

4 Credits

This homework is adapted from Homework 3 of the Fall 2014 offering of 15-122: Principles of Imperative Computation at Carnegie Mellon University (CMU).

Part II

Problems

The grading is defined in the accompanying rubric file.

1. Implementation

Complete the tasks listed in Section 3.1 by providing the implementations in the indicated files.

2. Amortized Analysis

Consider an ArrayStack implementation of the List interface with a slightly altered resize() operation. Instead of reserving space for 2n elements in the new array, it reserves space for n + ⌈ n4 ⌉ elements. Prove that the append() operation still takes O(1) time in the amortized sense.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column"></div>
</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="section">
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
&nbsp;Data Structures II

</div>
</div>
</div>
<div class="page" title="Page 9">
<div class="layoutArea">
<div class="column">
Part III Appendices

A MyImage

1 2 3 4 5 6 7 8 9

10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25 26 27 28 29 30 31 32 33 34 35 36 37 38 39 40 41 42 43 44 45 46 47 48 49 50 51 52 53 54 55 56 57 58

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
from PIL import Image

from src.mylist import ArrayList

</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
class MyImage:

“””Holds a flattened RGB image and its dimensions. Also implements Iterator

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
methods to allow iteration over this image. “””

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
def __init__(self, size: (int, int)) -&gt; None:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
“””Initializes a black image of the given size.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Parameters:

– self: mandatory reference to this object

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
– size: (width, height) specifies the dimensions to create.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Returns: none

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
“””

# Save size, create a list of the desired size with black pixels.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
width , height = self.size = size

self.pixels: ArrayList = ArrayList(width * height ,

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
value=(0, 0, 0))

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
def __iter__(self) -&gt; ‘MyImage’:

”’Iterator function to return an iterator (self) that allows iteration over

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
this image.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Parameters:

– self: mandatory reference to this object

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Returns:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
an iterator (self) that allows iteration over this image.

”’

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
# Initialize iteration indexes.

self._iter_r: int = 0

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
self._iter_c: int = 0 return self

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
def __next__(self):

””Iterator function to return the next value from this list.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Image pixels are iterated over in a left-to-right, top-to-bottom order.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Parameters:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
– self: mandatory reference to this object

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Returns:

the next value in this image since the last iteration.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
”’

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
if self._iter_r &lt; self.size[1]: # Iteration within image bounds. # Save current value as per iteration variables. Update the

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
# variables for the next iteration as per the iteration # order. Return saved value.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
value = self.get(self._iter_r , self._iter_c) self._iter_c += 1

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
if self._iter_c == self.size[0]:

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Page 9 of 20

</div>
</div>
</div>
<div class="page" title="Page 10">
<div class="layoutArea">
<div class="column">
59 60 61 62 63 64 65 66 67 68 69 70 71 72 73 74 75 76 77 78 79 80 81 82 83 84 85 86 87 88 89 90 91 92 93 94 95 96 97 98 99

100 101 102 103 104 105 106 107 108 109 110 111 112 113 114 115 116 117 118 119 120 121 122 123 124

</div>
</div>
<div class="layoutArea">
<div class="column">
CS 201 Data Structures II

</div>
<div class="column">
Homework 1: Lists

</div>
<div class="column">
Spring 2023

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
self._iter_c = 0

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
self._iter_r += 1 return value

else: # Image bounds exceeded, end of iteration.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
# Reset iteration variables , end iteration.

self._iter_r = self._iter_c = 0

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
raise StopIteration

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
def _get_index(self, r: int, c: int) -&gt; int:

“””Returns the list index for the given row, column coordinates.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
This is an internal function for use in class methods only. It should

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
not be used or called from outside the class.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Parameters:

– self: mandatory reference to this object

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
– r: the row coordinate

– c: the column coordinate

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Returns:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
the list index corresponding to the given row and column coordinates “””

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
# Confirm bounds, compute and return list index.

width , height = self.size

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
assert 0 &lt;= r &lt; height and 0 &lt;= c &lt; width, “Bad image coordinates: “\ f”(r, c): ({r}, {c}) for image of size: {self.size}”

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
return r*width + c

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
def open(path: str) -&gt; ‘MyImage’:

“””Creates and returns an image containing from the information at file path.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
The image format is inferred from the file name. The read image is

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
converted to RGB as our type only stores RGB.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Parameters:

– path: path to the file containing image information

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Returns:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
the image created using the information from file path. “””

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
# Use PIL to read the image information and store it in our instance.

img: Image = Image.open(path)

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
myimg: MyImage = MyImage(img.size)

# Covert image to RGB. https://stackoverflow.com/a/11064935/1382487

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
img: Image = img.convert(‘RGB’)

# Get list of pixel values (https://stackoverflow.com/a/1109747/1382487),

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
# copy to our instance and return it.

for i, rgb in enumerate(list(img.getdata())):

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
myimg.pixels.set(i, rgb) return myimg

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
def save(self , path: str) -&gt; None:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
“””Saves the image to the given file path.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
The image format is inferred from the file name.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Parameters:

– self: mandatory reference to this object

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
– path: the image has to be saved here.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Returns: none

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
“””

# Use PIL to write the image.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
img: Image = Image.new(“RGB”, self.size) img.putdata([rgb for rgb in self.pixels])

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 11">
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
img.save(path)

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
def get(self, r: int, c: int) -&gt; (int, int, int):

“””Returns the value of the pixel at the given row and column coordinates.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Parameters:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
– self: mandatory reference to this object – r: the row coordinate

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
– c: the column coordinate

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Returns:

the stored RGB value of the pixel at the given row and column coordinates.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
“””

return self.pixels[self._get_index(r, c)]

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
def set(self, r: int, c: int, rgb: (int, int, int)) -&gt; None:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
“””Write the rgb value at the pixel at the given row and column coordinates.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Parameters:

– self: mandatory reference to this object

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
– r: the row coordinate

– c: the column coordinate

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
– rgb: the rgb value to write

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Returns: none

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
“””

self.pixels[self._get_index(r, c)] = rgb

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
def show(self) -&gt; None:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
“””Display the image in a GUI window.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Parameters:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Returns: none

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
“””

# Use PIL to display the image.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
img: Image = Image.new(“RGB”, self.size) img.putdata([rgb for rgb in self.pixels])

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
img.show()

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
125 126 127 128 129 130 131 132 133 134 135 136 137 138 139 140 141 142 143 144 145 146 147 148 149 150 151 152 153 154 155 156 157 158 159 160 161 162 163 164 165

</div>
</div>
<div class="layoutArea">
<div class="column">
Code Listing 1: Image Type

</div>
</div>
</div>
<div class="page" title="Page 12">
<div class="layoutArea">
<div class="column">
1 2 3 4 5 6 7 8 9

10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25 26 27 28 29 30 31 32 33 34 35 36 37 38 39 40 41 42 43 44 45 46 47 48 49 50 51 52 53 54 55 56 57 58 59 60 61 62 63 64

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
import array as arr

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
class MyList:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
”’A list interface. Also implements Iterator functions in order to support iteration over this list.

”’

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
def __init__(self, size: int, value=None) -&gt; None:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
“””Creates a list of the given size, optionally intializing elements to value.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
The list is static. It only has space for size elements.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Parameters:

– self: mandatory reference to this object

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
– size: size of the list; space is reserved for these many elements. – value: the optional initial value of the created elements.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Returns:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
none “””

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
self.lst_arr = [value] * size

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
def __len__(self) -&gt; int:

”’Returns the size of the list. Allows len() to be called on it.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Ref: https://stackoverflow.com/q/7642434/1382487

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Parameters:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
– self: mandatory reference to this object

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Returns:

the size of the list.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
”’

return len(self.lst_arr)

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
def __getitem__(self, i: int):

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
”’Returns the value at index, i. Allows indexing syntax.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Ref: https://stackoverflow.com/a/33882066/1382487

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Parameters:

– self: mandatory reference to this object

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
– i: the index from which to retrieve the value.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Returns:

the value at index i.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
”’

# Ensure bounds.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
assert 0 &lt;= i &lt; len(self),\

f’Getting invalid list index {i} from list of size {len(self)}’

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
return self.lst_arr[i]

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
def __setitem__(self, i: int, value) -&gt; None:

”’Sets the element at index, i, to value. Allows indexing syntax.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Ref: https://stackoverflow.com/a/33882066/1382487

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Parameters:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
– self: mandatory reference to this object – i: the index of the elemnent to be set

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
– value: the value to be set

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Returns: none

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Page 12 of 20

</div>
</div>
</div>
<div class="page" title="Page 13">
<div class="layoutArea">
<div class="column">
65 66 67 68 69 70 71 72 73 74 75 76 77 78 79 80 81 82 83 84 85 86 87 88 89 90 91 92 93 94 95 96 97 98 99

100 101 102 103 104 105 106 107 108 109 110 111 112 113 114 115 116 117 118 119 120 121 122 123 124 125 126 127 128 129 130

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
”’

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
# Ensure bounds.

assert 0 &lt;= i &lt; len(self),\

f’Setting invalid list index {i} in list of size {len(self)}’

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
self.lst_arr[i] = value

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
def __iter__(self) -&gt; ‘MyList’:

”’Iterator function to return an iterator (self) that allows iteration over

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
this list.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Parameters:

– self: mandatory reference to this object

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Returns:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
an iterator (self) that allows iteration over this list.

”’

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
# Initialize iteration index.

self._iter_index: int = 0

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
return self

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
def __next__(self):

””Iterator function to return the next value from this list.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Parameters:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
– self: mandatory reference to this object

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Returns:

the next value in this list since the last iteration.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
”’

if self._iter_index &lt; len(self):

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
value = self.get(self._iter_index) self._iter_index += 1

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
return value else:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
# End of Iteration

self._index = 0

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
raise StopIteration

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
def get(self, i: int):

”’Returns the value at index , i.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Alternate to use of indexing syntax.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Parameters:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
– self: mandatory reference to this object

– i: the index from which to retrieve the value.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Returns:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
the value at index i.

”’

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
return self[i]

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
def set(self, i: int, value) -&gt; None:

”’Sets the element at index, i, to value.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Alternate to use of indexing syntax.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Parameters:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
– self: mandatory reference to this object – i: the index of the elemnent to be set

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
– value: the value to be set

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Returns: none

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
”’

self[i] = value

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Page 13 of 20

</div>
</div>
</div>
<div class="page" title="Page 14">
<div class="layoutArea">
<div class="column">
131 132 133 134 135 136 137 138 139 140 141 142 143 144 145 146 147 148 149 150 151 152 153 154 155 156 157 158 159 160 161 162 163 164 165 166 167 168 169 170 171 172 173 174 175 176 177 178 179 180 181 182 183 184 185 186 187 188 189 190 191 192 193 194 195 196

</div>
</div>
<table>
<tbody>
<tr>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
class ArrayList(MyList):

”’A list interface. Also implements Iterator functions in order to support

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
iteration over this list.

”’

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
def __init__(self, size: int, value=None) -&gt; None:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
“””Creates a list of the given size, optionally intializing elements to value.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
The list is static. It only has space for size elements.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Parameters:

– self: mandatory reference to this object

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
– size: size of the list; space is reserved for these many elements. – value: the optional initial value of the created elements.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Returns:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
none “””

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
self.arr_red = arr.array(‘i’, [value[0] for i in range(size)]) self.arr_green = arr.array(‘i’, [value[1] for i in range(size)])

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
self.arr_blue = arr.array(‘i’, [value[2] for i in range(size)])

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
def __len__(self) -&gt; int:

”’Returns the size of the list. Allows len() to be called on it.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Ref: https://stackoverflow.com/q/7642434/1382487

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Parameters:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
– self: mandatory reference to this object

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Returns:

the size of the list.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
”’

return len(self.arr_blue)

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
def __getitem__(self, i: int):

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
”’Returns the value at index, i. Allows indexing syntax.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Ref: https://stackoverflow.com/a/33882066/1382487

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Parameters:

– self: mandatory reference to this object

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
– i: the index from which to retrieve the value.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Returns:

the value at index i.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
”’

# Ensure bounds.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
assert 0 &lt;= i &lt; len(self),\

f’Getting invalid list index {i} from list of size {len(self)}’

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
return ((self.arr_red[i], self.arr_green[i], self.arr_blue[i]))

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
def __setitem__(self, i: int, value) -&gt; None:

”’Sets the element at index, i, to value. Allows indexing syntax.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Ref: https://stackoverflow.com/a/33882066/1382487

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Parameters:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
– self: mandatory reference to this object – i: the index of the elemnent to be set

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
– value: the value to be set

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Returns: none

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Page 14 of 20

</div>
</div>
</div>
<div class="page" title="Page 15">
<div class="layoutArea">
<div class="column">
CS 201 Data Structures II

</div>
<div class="column">
Homework 1: Lists

</div>
<div class="column">
Spring 2023

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
”’

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
# Ensure bounds.

assert 0 &lt;= i &lt; len(self),\

f’Setting invalid list index {i} in list of size {len(self)}’

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
self.arr_red[i] = value[0]; self.arr_green[i] = value[1]; self.arr_blue[i] = value[2 ]

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
197 198 199 200 201

</div>
</div>
<div class="layoutArea">
<div class="column">
Code Listing 2: List Type

</div>
</div>
<div class="layoutArea">
<div class="column">
Page 15 of 20

</div>
</div>
</div>
<div class="page" title="Page 16">
<div class="layoutArea">
<div class="column">
CS 201 Data Structures II

</div>
<div class="column">
Homework 1: Lists

</div>
<div class="column">
Spring 2023

</div>
</div>
<div class="layoutArea">
<div class="column">
C Image Operations

1 2 3 4 5 6 7 8 9

10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25 26 27 28 29 30 31 32 33 34 35 36 37 38 39 40

41 42 43 44 45 46 47 48 49 50 51 52 53 54 55 56 57 58 59 60 61 62 63

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
from src.myimage import MyImage

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
def remove_channel(src: MyImage, red: bool = False, green: bool = False,

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
blue: bool = False) -&gt; MyImage:

“””Returns a copy of src in which the indicated channels are suppressed.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Suppresses the red channel if no channel is indicated. src is not modified.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Args:

– src: the image whose copy the indicated channels have to be suppressed.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
– red: suppress the red channel if this is True.

– green: suppress the green channel if this is True.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
– blue: suppress the blue channel if this is True.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Returns:

a copy of src with the indicated channels suppressed.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
“””

src_copy = MyImage(src.size)

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
rows = src.size[1] cols = src.size[0]

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
for row in range(rows):

for col in range(cols):

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
src_copy.set(row, col, src.get(row, col))

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
if red == False and green == False and blue == False: for row in range(rows):

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
for col in range(cols):

temp = list(src_copy.get(row, col)); temp[0] = 0

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
else:

</div>
</div>
<div class="layoutArea">
<div class="column">
src_copy.set(row, col, tuple(temp))

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
for row in range(rows):

for col in range(cols):

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
temp = list(src_copy.get(row, col)) if red == True: temp[0] = 0

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
if green == True: temp[1] = 0 if blue == True: temp[2] = 0

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
src_copy.set(row, col, tuple(temp)) return src_copy

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
def convert_to_matrix(lst, m, n): #converts a flattened representation into an mxn matrix

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
mat = []

</div>
</div>
<div class="layoutArea">
<div class="column">
such that m and n are known

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
for i in range(0, len(lst), n): mat.append(lst[i:i+n])

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
return mat[:m]

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
def rotate_90(matrix): #Rotates a given m x n matrix 90 degress clockwise res = []

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
for i in range(len(matrix[0])): lst = []

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
for j in range(len(matrix)): lst.append(matrix[j][i])

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
# Reversing the matrix for 90 degree

lst.reverse()

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
res.append(lst) return res

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
def rotations(src: MyImage) -&gt; MyImage:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
“””Returns an image containing the 4 rotations of src.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
The new image has twice the dimensions of src. src is not modified.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Args:

– src: the image whose rotations have to be stored and returned.

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Page 16 of 20

</div>
</div>
</div>
<div class="page" title="Page 17">
<div class="layoutArea">
<div class="column">
64 65 66 67 68 69 70 71 72 73 74 75 76 77 78 79 80 81 82 83 84 85 86 87 88 89 90 91 92 93 94 95 96 97 98 99

100 101 102 103 104 105 106 107 108 109 110 111 112 113 114 115 116 117 118 119 120 121 122 123 124 125 126 127 128 129

</div>
</div>
<div class="layoutArea">
<div class="column">
CS 201 Data Structures II

</div>
<div class="column">
Homework 1: Lists

</div>
<div class="column">
Spring 2023

</div>
</div>
<table>
<tbody>
<tr>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Returns:

an image twice the size of src and containing the 4 rotations of src. “””

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
rows = src.size[1] cols = src.size[0]

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
src_copy = MyImage((cols * 2, rows * 2)) rot_90_lst = []

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
rot_180_lst = [] rot_270_lst = []

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
rot_360_lst = [] temp = []

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
for row in range(rows):

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
for col in range(cols): temp.append(src.get(row, col))

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
rot_360_lst = convert_to_matrix(temp, rows, cols) #Og image # 90 degree clockwise rotation

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
rot_90_lst = rotate_90(rot_360_lst) #Image – 180

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
rot_180_lst = rotate_90(rot_90_lst) #Image – 90 anticlockwise

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
rot_270_lst = rotate_90(rot_180_lst) src_copy_lst = []

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
for i in range(rows * 2): if i &lt; rows:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
for x in range(len(rot_270_lst[i])): src_copy_lst.append(rot_270_lst[i][x])

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
for x in range(len(rot_360_lst[i])): src_copy_lst.append(rot_360_lst[i][x])

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
else:

for x in range(len(rot_180_lst[i % rows])):

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
src_copy_lst.append(rot_180_lst[i % rows][x]) for x in range(len(rot_90_lst[i % rows])):

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
src_copy_lst.append(rot_90_lst[i % rows][x]) lst1 = convert_to_matrix(src_copy_lst , rows*2, cols*2)

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
for row in range(rows*2):

for col in range(cols*2):

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
src_copy.set(row, col, lst1[row][col]) return src_copy

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
def resize(src: MyImage) -&gt; MyImage:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
“””Returns an image which has twice the dimensions of src.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
The new image has twice the dimensions of src. src is not modified.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Args:

– src: the image which needs to be resized.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Returns:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
an image twice the size of src. “””

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
rows = src.size[1] cols = src.size[0]

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
src_copy = MyImage((cols * 2, rows * 2)) for row in range(rows):

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
for col in range(cols):

src_copy.set(row*2, col*2, src.get(row, col))

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
for row in range(cols*2):

for col in range(rows * 2):

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
if row % 2 == 0: #All even rows – not black rows if col % 2 == 1:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
if col == (cols * 2) – 1: #The last column – edge case pix = src_copy.get(row, col – 1)

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
src_copy.set(row, col, pix) else:

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Page 17 of 20

</div>
</div>
</div>
<div class="page" title="Page 18">
<div class="layoutArea">
<div class="column">
130 131 132

133 134 135 136 137 138 139 140 141 142 143

144 145 146 147 148 149 150 151 152 153 154 155

156 157 158 159 160 161 162 163 164 165 166 167 168 169 170 171 172 173

174 175 176 177 178

179 180 181 182 183

</div>
</div>
<div class="layoutArea">
<div class="column">
CS 201 Data Structures II

</div>
<div class="column">
Homework 1: Lists

</div>
<div class="column">
Spring 2023

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
pix1 = src_copy.get(row, col-1)

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
pix2 = src_copy.get(row, col+1)

pix = ((pix1[0] + pix2[0])//2, (pix1[1] + pix2[1])//2, (pix1[2] +

pix2[2]) // 2)

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
src_copy.set(row, col, pix) else: pass

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
if row % 2 == 1: #Black rows

if col % 2 == 0: #Not completely black columns

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
if row == (rows * 2) – 1: #Last row – edge case pix = src_copy.get(row – 1, col)

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
src_copy.set(row, col, pix) else:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
pix1 = src_copy.get(row – 1, col) pix2 = src_copy.get(row + 1, col)

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
pix = ((pix1[0] + pix2[0]) // 2, (pix1[1] + pix2[1]) // 2, (pix1[2] + pix2[2]) // 2)

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
src_copy.set(row, col, pix) if col % 2 == 1:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
if col == (cols * 2) – 1:

pix = src_copy.get(row, col – 1)

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
src_copy.set(row, col, pix) else:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
if row != (rows * 2) – 1:

pix1 = src_copy.get((row – 1), (col – 1))

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
pix2 = src_copy.get((row – 1), (col + 1)) pix3 = src_copy.get((row + 1), (col + 1))

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
pix4 = src_copy.get((row + 1), (col – 1))

pix = ((pix1[0] + pix2[0] + pix3[0] + pix4[0])//4, (pix1[1] +

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
pix2[1] + pix3[1] + pix4[1]) // 4, (

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
pix1[2] + pix2[2] + pix3[2] + pix4[2

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
src_copy.set(row, col, pix)

</div>
</div>
<div class="layoutArea">
<div class="column">
]) // 4)

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
for row in range(rows * 2):

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
for col in range(cols * 2):

if row % 2 == 1 and col % 2 == 1:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
if col == (cols * 2) – 1: #Edge case – last col pix = src_copy.get(row, col – 1)

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
src_copy.set(row, col, pix)

elif row == (row * 2) – 1: #Edge case – last row

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
pix = src_copy.get(row – 1, col) src_copy.set(row, col, pix)

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
else:

if row != (rows * 2) – 1:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
pix1 = src_copy.get((row – 1), (col – 1)) pix2 = src_copy.get((row – 1), (col + 1))

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
pix3 = src_copy.get((row + 1), (col + 1)) pix4 = src_copy.get((row + 1), (col – 1))

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
pix = ((pix1[0] + pix2[0] + pix3[0] + pix4[0])//4, (pix1[1] + pix2[1 ] + pix3[1] + pix4[1])

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
// 4, (pix1[2] + pix2 [2] + pix3[2] + pix4[2

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
src_copy.set(row, col, pix)

</div>
</div>
<div class="layoutArea">
<div class="column">
]) // 4)

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
else:

pix1 = src_copy.get(row, col – 1)

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
pix2 = src_copy.get(row, col + 1)

pix = ((pix1[0] + pix2[0]) // 2, (pix1[1] + pix2[1]) // 2, (pix1[2]

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
src_copy.set(row, col, pix)

</div>
</div>
<div class="layoutArea">
<div class="column">
+ pix2[2]) // 2)

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
return src_copy

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
def maskreader(maskfile): #Reads the maskfile and returns a list with values of maskfile ”’

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Page 18 of 20

</div>
</div>
</div>
<div class="page" title="Page 19">
<div class="layoutArea">
<div class="column">
184 185 186 187 188 189 190 191 192 193 194 195 196 197 198 199 200 201 202 203 204 205 206 207 208 209 210 211 212 213 214 215 216 217 218 219 220 221 222 223 224 225 226 227

228 229

230 231 232 233 234 235 236

237 238 239

240 241 242 243 244 245

</div>
</div>
<div class="layoutArea">
<div class="column">
CS 201 Data Structures II

</div>
<div class="column">
Homework 1: Lists

</div>
<div class="column">
Spring 2023

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Returns a tuple of mask list and length.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
This is a helper function that is used in apply_mask function to read the mask file and return a list of n by n.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
maskfile is a text file containing n by n mask.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Args:

– maskfile: path to file specifying mask

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Returns:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Tuple of lst of n by n and length

”’

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
f = open(maskfile , ‘r’); lst = []

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
for i in f: lst.append(int(i))

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
mat_len = lst[0]; mask_lst = lst[1::] f.close()

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
return (mask_lst , mat_len)

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
def apply_mask(src: MyImage, maskfile: str, average: bool = True) -&gt; MyImage: “””Returns an copy of src with the mask from maskfile applied to it.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
maskfile specifies a text file which contains an n by n mask. It has the

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
following format:

– the first line contains n

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
– the next n^2 lines contain 1 element each of the flattened mask

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Args:

– src: the image on which the mask is to be applied

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
– maskfile: path to a file specifying the mask to be applied

– average: if True, averaging should to done when applying the mask

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Returns:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
an image which the result of applying the specified mask to src. “””

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
rows = src.size[1]; cols = src.size[0] src_copy = MyImage(src.size)

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
# for row in range(rows):

# for col in range(cols):

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
# src_copy.set(row, col, src.get(row, col))

vals = maskreader(maskfile)

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
mask_lst = vals[0]; n = vals[1]

# print(f”Mask list: {mask_lst} \n length = {n} \n center at {center} with value {

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
for i , pixels in enumerate(src):

</div>
</div>
<div class="layoutArea">
<div class="column">
mask_lst[center]}”)

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
row, col = divmod(i,cols) #gives row index with corresponding column index to iterate over

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
# print(row, col)

val = 0; total = 0

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
for x in range(n):

for y in range(n):

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
mask_row = x – (n // 2) #Computing row mask mask_col = y – (n // 2) #Computing col mask

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
if row + mask_row &gt;= 0 and row + mask_row &lt; rows and col + mask_col &gt;= 0 and col + mask_col &lt; cols:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
total += mask_lst[n * x + y]

pix = src.get(row + mask_row, col + mask_col)

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
# print(f”Row {row} Col {col} RowMask {mask_row} ColMask {mask_col} pixel {pix}”)

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
val += ((pix[0] + pix[1] + pix[2])) // 3 * mask_lst[n * x + y] if average == True: val = val // total

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
if val &gt; 255: val = 255 if val &lt; 0: val = 0

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
src_copy.set(row, col, (val,val,val)) return src_copy

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column"></div>
</div>
</div>
<div class="page" title="Page 20">
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
</div>
