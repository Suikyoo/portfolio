+++
date = '2026-05-24T23:43:52+08:00'
title = 'Vehicle Detection'
+++

I've had many projects involving vehicle detection done mostly for a single commision that took me ages. 


## YOLO Detection

I barely know anything about machine learning at this point. 

If I remember correctly, I've used Ultralytics' features such as detection in regions of interests. This just uses the pretrained weights of YOLOv8n, and I've filtered it to only detect vehicle-like classes.
{{< video
    src="yolo-vehicle-detection.mp4"
    caption="prototype deployed on a **raspberry pi**, *(very lag)*"
    loop=true
    muted=true
>}}

## SSD-Mobilenet Detection 
Unlike YOLO, ssd-mobilenet doesn't really have an official ecosystem or environment around it. This was very challenging because I didn't know anything about trackers at this point and the raspberry pi didn't help at all with the performance.
{{< video
    src="ssd-mobilenet-vehicle-detection.mp4"
    caption="prototype deployed on a **raspberry pi**, *(also very lag)*"
    loop=true
    muted=true
>}}
I had to do line-checking whether at any perceivable point in time, any detection has occurred or collided with the line.
