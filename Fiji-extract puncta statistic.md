# Extract puncta statistic

1.  Open \*.oib or \*.tif image in Fiji

2.  Duplicate the channel under *Image-\>Duplicate* , remember to
    uncheck the checkbox, get *image1*

3.  Click on *image1* , use *Image-\>Properties* and set *Pixel width*
    and *Pixel height* to 1, press *OK*

4.  Duplicate the selected channel again, get *image2*

5.  Click on *image2* , and perform *Process-\>Subtract background* ,
    set *Rolling ball radius* to 8, press *OK*

6.  Use *Image-\>Adjust-\>Threshhold* , set method to *moment* , press
    \*Apply\*

7.  Use *Analyze-\>set measurement*s, set *Redirect to* to *image1* ,
    and press *OK*

8.  Use *Analyze-\>Analyze Particles*


