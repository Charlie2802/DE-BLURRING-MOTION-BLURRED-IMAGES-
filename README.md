# DE-BLURRING-MOTION-BLURRED-IMAGES-
DE-BLURRING MOTION BLURRED IMAGES 
Motion de-blurring of square images using the Radon transform is a technique used to accurately estimate the motion blur angle and restore the sharpness of the image.

When an image is captured with motion blur, the objects in the scene appear elongated or smeared due to the movement of the camera or the subject. The Radon transform is a mathematical technique that can analyze the image's projection profiles at different angles and provide information about the blur angle.

To perform motion de-blurring using the Radon transform, the square image is first converted to the frequency domain. The Radon transform is then applied to the image, which measures the intensity of the image's projections at different angles. By analyzing these projections, the maximum variance in the column is identified to determine the blur angle.

The maximum variance in the column indicates the direction in which the motion blur occurred. By estimating this angle, the de-blurring algorithm can apply the appropriate inverse motion blur filter to restore the image's sharpness. The inverse filter counteracts the blur by compensating for the motion in the opposite direction, resulting in a clearer and sharper image.

The Radon transform-based approach offers computational efficiency and accuracy, especially for higher values of blur length (L). By accurately estimating the blur angle using the maximum variance in the column, it enables effective restoration of motion-blurred square images, leading to improved visual quality and better image analysis.
