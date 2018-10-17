
# Supplementary Page for "A Unified framework based on Unsupervised Convolutional Neural Networks for Hybrid Affine-Deformable Image registration"

----

ARN: Affine registration network 

DRN: Deformable registration network

Hybrid model: ARN+DRN

## A  Hybrid Affine-Deformable Pipeline

Application of the proposed hybrid registration model to chest CT scans. The following figure shows the image pairs before registration, after affine registration, after the hybrid affine-deformable registration. We have also shown the the magnitude of the displacement field for the deformable  registration in the last column. 

||Before registration|After ARN|After ARN+DRN|DRN Flow Field|
|----|----|----|----|----|
|Patient 1|![](imgs/v/51078172_to_44547538.orig.png)|![](imgs/v/51078172_to_44547538.arn.png)|![](imgs/v/51078172_to_44547538.vm.png)|![](imgs/v/51078172_to_44547538.flow.png)|
|Patient 2|![](imgs/v/48057819_to_32672488.orig.png)|![](imgs/v/48057819_to_32672488.arn.png)|![](imgs/v/48057819_to_32672488.vm.png)|![](imgs/v/48057819_to_32672488.flow.png)|
|Patient 3|![](imgs/v/06553963_to_22966903.orig.png)|![](imgs/v/06553963_to_22966903.arn.png)|![](imgs/v/06553963_to_22966903.vm.png)|![](imgs/v/06553963_to_22966903.flow.png)|
|Patient 4|![](imgs/v/96643212_to_77262879.orig.png)|![](imgs/v/96643212_to_77262879.arn.png)|![](imgs/v/96643212_to_77262879.vm.png)|![](imgs/v/96643212_to_77262879.flow.png)|
|Patient 5|![](imgs/v/76881768_to_33905433.orig.png)|![](imgs/v/76881768_to_33905433.arn.png)|![](imgs/v/76881768_to_33905433.vm.png)|![](imgs/v/76881768_to_33905433.flow.png)|
|Patient 6|![](imgs/v/02160131_to_97861724.orig.png)|![](imgs/v/02160131_to_97861724.arn.png)|![](imgs/v/02160131_to_97861724.vm.png)|![](imgs/v/02160131_to_97861724.flow.png)|
|Patient 7|![](imgs/v/22604050_to_49941516.orig.png)|![](imgs/v/22604050_to_49941516.arn.png)|![](imgs/v/22604050_to_49941516.vm.png)|![](imgs/v/22604050_to_49941516.flow.png)|
|Patient 8|![](imgs/v/30842140_to_68218850.orig.png)|![](imgs/v/30842140_to_68218850.arn.png)|![](imgs/v/30842140_to_68218850.vm.png)|![](imgs/v/30842140_to_68218850.flow.png)|
|Patient 9|![](imgs/v/14068610_to_37083249.orig.png)|![](imgs/v/14068610_to_37083249.arn.png)|![](imgs/v/14068610_to_37083249.vm.png)|![](imgs/v/14068610_to_37083249.flow.png)|
|Patient 10|![](imgs/v/76881768_to_33905433.orig.png)|![](imgs/v/76881768_to_33905433.arn.png)|![](imgs/v/76881768_to_33905433.vm.png)|![](imgs/v/76881768_to_33905433.flow.png)|


----

## ARN vs SITK
The following figure hsows a head-to-head comparison between the proposed ARN and the commonly used affine registration method from the SITK library. As seen, the ARN outperforms SITK qualitatively (please see the paper for quantitative comparisons). It might be possible for the affine registration to diverge when the images are already in good alignment, as seen in patient 4, in which case ARN exhibits more stable and robust performance.

||**Before registration**|**SITK**|**ARN**|**Before registration**|**SITK**|**ARN**|
|----|----|----|----|----|----|----|
|Patient 1|![](imgs/b/52533238_to_26018233CAcoro.png)|![](imgs/b/52533238_to_26018233SITKcoro.png)|![](imgs/b/52533238_to_26018233ARNcoro.png)|![](imgs/b/52533238_to_26018233CAtrns.png)|![](imgs/b/52533238_to_26018233SITKtrns.png)|![](imgs/b/52533238_to_26018233ARNtrns.png)|
|Patient 2|![](imgs/b/00464985_to_32402804CAcoro.png)|![](imgs/b/00464985_to_32402804SITKcoro.png)|![](imgs/b/00464985_to_32402804ARNcoro.png)|![](imgs/b/00464985_to_32402804CAtrns.png)|![](imgs/b/00464985_to_32402804SITKtrns.png)|![](imgs/b/00464985_to_32402804ARNtrns.png)|
|Patient 3|![](imgs/b/62828273_to_29773460CAcoro.png)|![](imgs/b/62828273_to_29773460SITKcoro.png)|![](imgs/b/62828273_to_29773460ARNcoro.png)|![](imgs/b/62828273_to_29773460CAtrns.png)|![](imgs/b/62828273_to_29773460SITKtrns.png)|![](imgs/b/62828273_to_29773460ARNtrns.png)|
|Patient 4|![](imgs/b/82307434_to_81987874CAcoro.png)|![](imgs/b/82307434_to_81987874SITKcoro.png)|![](imgs/b/82307434_to_81987874ARNcoro.png)|![](imgs/b/82307434_to_81987874CAtrns.png)|![](imgs/b/82307434_to_81987874SITKtrns.png)|![](imgs/b/82307434_to_81987874ARNtrns.png)|
|Patient 5|![](imgs/b/24201400_to_00057691CAcoro.png)|![](imgs/b/24201400_to_00057691SITKcoro.png)|![](imgs/b/24201400_to_00057691ARNcoro.png)|![](imgs/b/24201400_to_00057691CAtrns.png)|![](imgs/b/24201400_to_00057691SITKtrns.png)|![](imgs/b/24201400_to_00057691ARNtrns.png)|
|Patient 6|![](imgs/b/77142232_to_21486282CAcoro.png)|![](imgs/b/77142232_to_21486282SITKcoro.png)|![](imgs/b/77142232_to_21486282ARNcoro.png)|![](imgs/b/77142232_to_21486282CAtrns.png)|![](imgs/b/77142232_to_21486282SITKtrns.png)|![](imgs/b/77142232_to_21486282ARNtrns.png)|


|SITK Setup|
|----|
|Sitk Affine registration is configured to opimize Mattes mutual information with 50 histogram bins. Opitmization is done at 3 levels at 1/4, 1/2, and 1 of original scale. Each scale has a maximum step of 100.|


----

##  Challenging cases for registration

Lung Dice score after registration could be low when input cases are patients with incomplete and/or partial CT scans, or patients with severe pulmonary conditions where the lung areas show large lesions such as bulla or pneumothorax.

||**fixed coronal**|**moving coronal**|**fixed transversal**|**moving transversal**|**Comments**|
|----|----|----|----|----|----|
|Patient 1|![](imgs/f/14020534_to_38176629.fixed_coro.png)|![](imgs/f/14020534_to_38176629.moving_coro.png)|![](imgs/f/14020534_to_38176629.fixed_trns.png)|![](imgs/f/14020534_to_38176629.moving_trns.png)|Fixed image shows a partial scan where only a portion of the thorax is visible|
|Patient 2|![](imgs/f/26788410_to_93447078.fixed_coro.png)|![](imgs/f/26788410_to_93447078.moving_coro.png)|![](imgs/f/26788410_to_93447078.fixed_trns.png)|![](imgs/f/26788410_to_93447078.moving_trns.png)|Large bulla (black areas) coveing the lung areas in box fixed and moving images|
|Patient 3|![](imgs/f/20212245_to_51510913.fixed_coro.png)|![](imgs/f/20212245_to_51510913.moving_coro.png)|![](imgs/f/20212245_to_51510913.fixed_trns.png)|![](imgs/f/20212245_to_51510913.moving_trns.png)|The left lung in the fixed image appears small due to phrenic nerve paralysis|


<!--- 
||||||
|----|----|----|----|----|
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
-->

