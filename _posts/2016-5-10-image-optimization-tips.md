---
layout: post
title: Quick and Easy Image Optimization Tips
---

Something I have been thinking about (and doing a lot of lately) is image optimization for web. How do you make sure your image-heavy site loads quickly, while also ensuring your images will look good on retina/ high-resolution screens? There are many good articles out there about optimizing images, so I wanted to bring up some quick and easy things I do on a regular basis.

## Resizing Images

Before you do anything, make sure you have the original images saved elsewhere, in case you make a change you can't undo! An easy way to decrease file size is to resize the image. Professional photographers take extremely high quality photographs: an image can have a size of 10MB and be 4000px wide (almost 42"!) A website would take a very long time to load such a big photo, and you definitely do not need that size.

A 27" monitor is 2560 pixels wide, so this is the widest I will save a photo for web (sometimes I save it at 1280px wide which is my laptop size). While the 27" iMac Retina can support a resolution of 5000+ pixels... I can't think about that and think about having a fast load time for my site at the same time! I won't upload a photo that is over 1MB. Frankly, 1MB is still huge so try to get it under 500KB. (Remember these are just general guidelines I keep in mind when optimizing images, not rules that must be followed.)

You can use Photoshop to resize images: Go to (Image - Image Size) to adjust pixel width or height.

*Easy Method:* In Mac, you can use the default program for photos, Preview. Just go to (Tools - Adjust Size) and change the pixel width or height! Remember to only change one value so it will size down proportionately. You can also use the crop function to make the photo your desired size. If you don't have a Mac, there are plenty of free image resizers on the web.
 
## Image Types

I save as JPG files photographs I want to remain high-quality, and many photos in general. GIFs are smaller in file size so I use that for pictures that I don't mind at lower quality (and animated photos of course). PNGs are pretty big so I often end up saving file size by using another format, but I may use PNGs for little pictures. SVG or vector graphics should be used for logos. There are many articles online about topics such as: JPG vs GIF vs PNG, SVG creation, vector vs raster graphics, lossless vs lossy, etc. all of which I cannot explain very well, but plenty of other people have!

## Compress your Images and Image Quality

In Photoshop you can "File-Save for Web" in older versions of Photoshop, or "File-Export-Save for Web" in Photoshop Creative Cloud. That will allow you to save your photo at a lower quality, while giving you a preview screen of exactly how your photo will look. You will find that you may be able to save your photo at Medium quality and it will still look very similar to the original photo! Photos for web are 72dpi and RGB color, so you can change that (as opposed to 300 dpi and CMYK color which is needed for print).

*Easy method:* Download ImageOptim, a free desktop program for Mac. Right before you upload (after you have used Photoshop or edited your pics), you can drag all of your pics into ImageOptim. ImageOptim will strip the photo of unnecessary metadata - and I've found it often reduces my photo size by 20% or more! You don't even have to then drag your photos out of ImageOptim, it will have updated the original photos!

If you don't have Photoshop, there are free image editing alternatives like PicMonkey and GIMP.

## Other

Other suggestions include serving up different sizes of the same image using CSS, Javascript or in your HTML image tags. Or perhaps serving your assets on a content delivery network (CDN) not on your own site. 

This is a good article for learning about image optimization for SEO purposes, and in general
https://www.shopify.com/blog/7412852-10-must-know-image-optimization-tips

