
# Supplementary Page for "A Unified framework based on Unsupervised Convolutional Neural Networks for Hybrid Affine-Deformable Image registration"

----

## Registration output examples where proposed ARN performs better than SITK linear registration  


||ARN coronal view|SITK coronal view|ARN transaxial view|SITK transaxial view|
|----|||||
|pair 1|![](imgs/b/52533238_to_26018233ARNcoro.png)|![](imgs/b/52533238_to_26018233SITKcoro.png)|![](imgs/b/52533238_to_26018233ARNtrns.png)|![](imgs/b/52533238_to_26018233SITKtrns.png)|
|pair 2|![](imgs/b/00464985_to_32402804ARNcoro.png)|![](imgs/b/00464985_to_32402804SITKcoro.png)|![](imgs/b/00464985_to_32402804ARNtrns.png)|![](imgs/b/00464985_to_32402804SITKtrns.png)|
|pair 3|![](imgs/b/62828273_to_29773460ARNcoro.png)|![](imgs/b/62828273_to_29773460SITKcoro.png)|![](imgs/b/62828273_to_29773460ARNtrns.png)|![](imgs/b/62828273_to_29773460SITKtrns.png)|
|pair 4|![](imgs/b/82307434_to_81987874ARNcoro.png)|![](imgs/b/82307434_to_81987874SITKcoro.png)|![](imgs/b/82307434_to_81987874ARNtrns.png)|![](imgs/b/82307434_to_81987874SITKtrns.png)|
|pair 5|![](imgs/b/24201400_to_00057691ARNcoro.png)|![](imgs/b/24201400_to_00057691SITKcoro.png)|![](imgs/b/24201400_to_00057691ARNtrns.png)|![](imgs/b/24201400_to_00057691SITKtrns.png)|
|pair 6|![](imgs/b/77142232_to_21486282ARNcoro.png)|![](imgs/b/77142232_to_21486282SITKcoro.png)|![](imgs/b/77142232_to_21486282ARNtrns.png)|![](imgs/b/77142232_to_21486282SITKtrns.png)|

||
|---|
|Sitk Affine registration is configured to opimizes Mattes mutual information with 50 histogram bins. Opitmization is done at 3 levels at 1/4, 1/2, and 1 of original scale. Each scale have a maximum step of 100.|


----

##  Examples where Dice of lung area after registration is low

Affine registration results are often poor when lungs of fixed and moving images have large difference, or when lung segmentation is not ideal.


||||||
|:----|||||
||**fixed image coronal**|**fixed image transaxial**|**moving image coronal**|**moving image transaxial**|
|pair1 input|![](imgs/f/14020534_to_38176629.fixed_coro.png)|![](imgs/f/14020534_to_38176629.fixed_trns.png)|![](imgs/f/14020534_to_38176629.moving_coro.png)|![](imgs/f/14020534_to_38176629.moving_trns.png)|
||**ARN coronal view**|**SITK coronal view**|**ARN transaxial view**|**SITK transaxial view**|
|pair1 output|![](imgs/f/14020534_to_38176629ARNcoro.png)|![](imgs/f/14020534_to_38176629SITKcoro.png)|![](imgs/f/14020534_to_38176629ARNtrns.png)|![](imgs/f/14020534_to_38176629SITKtrns.png)|
||**fixed image coronal**|**fixed image transaxial**|**moving image coronal**|**moving image transaxial**|
|pair2 input|![](imgs/f/26788410_to_93447078.fixed_coro.png)|![](imgs/f/26788410_to_93447078.fixed_trns.png)|![](imgs/f/26788410_to_93447078.moving_coro.png)|![](imgs/f/26788410_to_93447078.moving_trns.png)|
||**ARN coronal view**|**SITK coronal view**|**ARN transaxial view**|**SITK transaxial view**|
|pair2 output|![](imgs/f/26788410_to_93447078ARNcoro.png)|![](imgs/f/26788410_to_93447078SITKcoro.png)|![](imgs/f/26788410_to_93447078ARNtrns.png)|![](imgs/f/26788410_to_93447078SITKtrns.png)|
||**fixed image coronal**|**fixed image transaxial**|**moving image coronal**|**moving image transaxial**|
|pair3 intput|![](imgs/f/20212245_to_51510913.fixed_coro.png)|![](imgs/f/20212245_to_51510913.fixed_trns.png)|![](imgs/f/20212245_to_51510913.moving_coro.png)|![](imgs/f/20212245_to_51510913.moving_trns.png)|
||**ARN coronal view**|**SITK coronal view**|**ARN transaxial view**|**SITK transaxial view**|
|pair3 output|![](imgs/f/20212245_to_51510913ARNcoro.png)|![](imgs/f/20212245_to_51510913SITKcoro.png)|![](imgs/f/20212245_to_51510913ARNtrns.png)|![](imgs/f/20212245_to_51510913SITKtrns.png)|
||**fixed image coronal**|**fixed image transaxial**|**moving image coronal**|**moving image transaxial**|
|pair4 input|![](imgs/f/50179315_to_32552628.fixed_coro.png)|![](imgs/f/50179315_to_32552628.fixed_trns.png)|![](imgs/f/50179315_to_32552628.moving_coro.png)|![](imgs/f/50179315_to_32552628.moving_trns.png)|
||**ARN coronal view**|**SITK coronal view**|**ARN transaxial view**|**SITK transaxial view**|
|pair4 output|![](imgs/f/50179315_to_32552628ARNcoro.png)|![](imgs/f/50179315_to_32552628SITKcoro.png)|![](imgs/f/50179315_to_32552628ARNtrns.png)|![](imgs/f/50179315_to_32552628SITKtrns.png)|
||**fixed image coronal**|**fixed image transaxial**|**moving image coronal**|**moving image transaxial**|
|pair5 input|![](imgs/f/39772525_to_42416930.fixed_coro.png)|![](imgs/f/39772525_to_42416930.fixed_trns.png)|![](imgs/f/39772525_to_42416930.moving_coro.png)|![](imgs/f/39772525_to_42416930.moving_trns.png)|
||**ARN coronal view**|**SITK coronal view**|**ARN transaxial view**|**SITK transaxial view**|
|pair5 output|![](imgs/f/39772525_to_42416930ARNcoro.png)|![](imgs/f/39772525_to_42416930SITKcoro.png)|![](imgs/f/39772525_to_42416930ARNtrns.png)|![](imgs/f/39772525_to_42416930SITKtrns.png)|
||**fixed image coronal**|**fixed image transaxial**|**moving image coronal**|**moving image transaxial**|
|pair6 input|![](imgs/f/55921267_to_04476681.fixed_coro.png)|![](imgs/f/55921267_to_04476681.fixed_trns.png)|![](imgs/f/55921267_to_04476681.moving_coro.png)|![](imgs/f/55921267_to_04476681.moving_trns.png)|
||**ARN coronal view**|**SITK coronal view**|**ARN transaxial view**|**SITK transaxial view**|
|pair6 output|![](imgs/f/55921267_to_04476681ARNcoro.png)|![](imgs/f/55921267_to_04476681SITKcoro.png)|![](imgs/f/55921267_to_04476681ARNtrns.png)|![](imgs/f/55921267_to_04476681SITKtrns.png)|


