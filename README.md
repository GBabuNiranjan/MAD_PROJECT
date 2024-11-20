# MAD_PROJECT
 This app allows you to either click image from your phone or select an image from storage and apply the blur. This app can run on ARM32 bit ARM v7A as well as ARM64 ARMv8-A.

 ~Select image from storage or click them using camera
 ~Blur a variety of subjects (most centered subject will be selected rest will be background).
 ~SoftBlur around edges
 I have 3 pre-trained models of different crop sizes Default 1025 px. You can use any one of them but with increased crop size the processing time also increases (by a lot), so use them as per your requirement. Crop size is the size of the image that the input image will be resized to and sent for processing. The output dimensions are always less than crop size.

For using 1537 px: Copy InputSize 1537px\frozen_inference_graph.pband paste it in CameraBlur\app\src\main\assets\.
