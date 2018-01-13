# Links.github.io
this is a simple html-css way of creating links

CSS3 Filters are a quite interesting offshoot from SVG, allowing you to modify HTML elements and images with blurs, brightness and a lot more. In this quick tutorial we’ll go over exactly how they’re going to work.

# How it Works
Using just CSS we can accomplish some pretty complicated effects. These should be applicable to both images and HTML elements, but obviously browsers will vary for the foreseeable future. The property used to control all of this stuff is filter.
filter: filter(value);
As you might expect though, browser prefixes will be required. For the moment though, -webkit-(Chrome and Safari) is the only browser engine supporting these properties.
-webkit-filter: filter(value);
-moz-filter: filter(value);
-o-filter: filter(value);

# Filtering
There are quite a few filter, so to get a better idea lets take a look at them individually. Multiple filters can be applied with a space, for example, brightness and blur:
filter: blur(5px) brightness(0.5);
There are a few filters that I won’t outline below, but these can be easily accomplished with already existing CSS (opacity and drop shadows). Here’s the original image which we’re going to filter below:
 
I will provide the filtered version of the photo (the first photo) and a picture of what the filter should look like (the second photo) should you be using a browser that can’t see filters. Enjoy!

