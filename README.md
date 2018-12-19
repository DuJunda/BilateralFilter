# BilateralFilter
The implemention for cv2. bilateralFilter .
I wouldn't bother to introduce the paremater and usage, since it's clear in the code.

I think the adjustment for paremater is important.

********English By Google Translate :)********
Gaussian filter weights for color differences: If you want to make the color difference also affect, set color_sigma to a larger value; otherwise, the effect of large color difference is small, which will play the role of retaining the boundary.
Gaussian filter weights for distance differences: If you want to make the difference in distance also affect, set distance_sigma to a larger value; otherwise, the effect of large distance difference is small, which will play a smooth role (fuzzy).
Another sentence: Anaconda3-5.3.1 opencv parameters of the bilateralFilter is likely to confuse sigmaColor and sigmaSpace.

********Raw********
有关颜色差的高斯滤波权重：如果想让颜色差别大的也能起到影响，设置color_sigma为较大的值；否则颜色差别大的影响作用很小，将会起到保留边界的作用
有关距离差的高斯滤波权重：如果想让距离差别大的也能起到影响，设置distance_sigma为较大的值；否则距离差别大的影响作用很小，将会起到平滑的作用（模糊）
另外插一句：Anaconda3-5.3.1的opencv中bilateralFilter的参数很有可能将sigmaColor和sigmaSpace混淆了。
