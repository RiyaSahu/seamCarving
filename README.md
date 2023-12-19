# About Seam Carving
- Seam-carving is a content-aware image resizing technique where the image is reduced in size by one pixel of height (or width)
at a time, providing an intelligent method for adjusting image dimensions while preserving vital features and content.
- This project centered around the creation and application of foundational principles in Seam Carving, encompassing tasks
such as image energy calculation, lowest energy seam identification and lowest energy seam removal
- Seam carving plays a pivotal role in contemporary graphic design and photo editing applications like Adobe Photoshop.

### Library and language used
---
Used opencv library in c++
- For installation on ubuntu one can follow below link:
  https://www.geeksforgeeks.org/how-to-install-opencv-in-c-on-linux/
  
### Reference
---
- Below youtube playlist can help you get a strong hold of playing around with images using opencv library (starting 4-5 videos would be enough for a kickstart).  
 https://youtube.com/playlist?list=PLAp0ZhYvW6XbEveYeefGSuLhaPlFML9gP&si=jgasPKt_j52_oxNY
 
- Below link explains the complete logic of seam carving.
  https://www.cs.princeton.edu/courses/archive/fall17/cos226/assignments/seam/index.html

### Some possible corrections
---
- I have used dual gradient energy function for energy calculation, however one can try using more efficient energy functions to get better results.

### Sample Images
---
- This repository also contains some sample input images which can prove to be handy while testing your code.