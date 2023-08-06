## Connected Component Labeling

Design a MATLAB GUI, as shown below, to implement following operations:
- Load Image: read image ‘coins.png’ from MATLAB repository and display into axes.
- Label Image: Label the read image using ‘bwlabel’ function. Populate information about image width, height and no. of coins in ‘static text’ controls. And display the labeled image into axes.
- Display Info: This button should be a toggle button which is if pressed shows the information panel otherwise it will hide the panel.
- Load the image ‘coins.png’ (available in Matlab repository) once the user clicks the ‘Load’ button. You can directly load the image without showing the File Open Dialog to the user.
- Clicking the ‘Label’ button, show the binarized image in the axes, find the number of components in the image and the properties of these components. A rectangle must also be drawn over each detected component (as shown in Figure 2).
- Using the ‘Centroid’ property, join the center of the first connected component with the centers of all connected components using the ‘line’ function (Figure 3).
- Find the area of the largest and the smallest component and display it in a text box. (Use Matlab sort function).


Please see report for all details