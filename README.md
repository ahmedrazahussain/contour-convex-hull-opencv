# Contour-Convex-Hull-Opencv
## Contour and Convex Hull Detection using Opencv
This projects demonstrates how to detect contours and convex hulls of objects (such as hands) using Opencv. It analyzes contours and convex hulls from an input image.
## Features
- Reads an image and converts it to grayscale
- Applies contours and draws convex hulls
- Compute convexity defects to identify shape features (like finger gaps)
## How It Works
- Convert the image to grayscale
- Threshold the image using 'cv2.THRESH_BINARY_INV'
- Perform morphological operations like dilation
- Use 'cv2.findContours' and 'cv2.convexHull'
- Optionally detect convexity defects and draw points
