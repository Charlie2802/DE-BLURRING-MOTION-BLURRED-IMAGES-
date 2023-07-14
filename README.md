
DE-BLURRING MOTION BLURRED IMAGES 

The project aims to develop an innovative and computationally efficient method for restoring motion-blurred square images. By leveraging the Radon transform, the technique accurately estimates the motion blur angle and applies an inverse motion blur filter to restore the sharpness of the image.

Motion blur occurs when there is relative motion between the camera or the subject being captured, resulting in smearing or elongation of objects in the image. In this project, the Radon transform is used to analyze the image's projection profiles at different angles, providing insights into the blur characteristics.

One of the key aspects of this project is the utilization of the maximum variance in the column. By examining the variance in each column of the Radon transform output, the technique identifies the column with the highest variance. This column corresponds to the angle at which the blur occurred. By finding the angle with the maximum variance, the technique accurately estimates the motion blur angle.

Accurate estimation of the motion blur angle is crucial for effective restoration. Once the blur angle is determined, the project applies an inverse motion blur filter. This filter counteracts the blur by compensating for the motion in the opposite direction, resulting in the restoration of the image's sharpness.

Furthermore, the project focuses specifically on square images, which are commonly encountered in various domains, such as computer vision, image processing, and pattern recognition. By tailoring the technique to address motion blur in square images, it provides specialized solutions to challenges unique to this image format.

The technique's computational efficiency is another significant advantage. By efficiently analyzing the projection profiles using the Radon transform, the project can quickly estimate the motion blur angle. This efficiency is particularly advantageous for real-time applications or scenarios involving large-scale image processing.

The proposed project aims to enhance the visual quality of motion-blurred square images by leveraging the Radon transform and its computational efficiency. By accurately estimating the motion blur angle using the maximum variance in the column, the project offers an effective solution for motion de-blurring.
