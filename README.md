# Road-line-Detection
To detect white markings in the lane, first, we need to mask the rest part of the frame. We do this using frame masking. The frame is nothing but a NumPy array of image pixel values. To mask the unnecessary pixel of the frame, we simply update those pixel values to 0 in the NumPy array.

After making we need to detect lane lines. The technique used to detect mathematical shapes like this is called Hough Transform. Hough transformation can detect shapes like rectangles, circles, triangles, and lines.
