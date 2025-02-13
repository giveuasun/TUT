<!-- 本文为汉化ipp库函数用法 -->
# 卷1 信号与数据处理

## <font color = yellow>基本函数</font>
### <font color = cyan>逻辑和移位函数</font>
#### AndC
* 计算标量值和向量每个元素的位与。
#### And
* 计算两向量的位与。
#### OrC
* 计算标量值和向量每个元素的位或。
#### Or
* 计算两向量的位或。
#### XorC
* 计算标量值和向量每个元素的异或。
#### Xor
* 计算两向量的位异或。
#### Not
* 计算向量的位非。
#### LshiftC
* 向量元素按位左移。
#### RshiftC
* 向量元素按位右移。
#### AddC
* 为向量中每一个元素加一个常量。
#### Add
* 两向量对应元素相加。
#### AddProductC
* pSrcDst[n] = pSrcDst[n] + pSrc[n]*val, 0 ≤ n < len
#### AddProduct
* 两向量逐位相乘，并位累加在第三个向量上。
#### MulC
* 数乘，常量乘以向量。
#### Mul
* 两向量逐位相乘。
#### SubC
#### SubCRev
#### Sub
#### DivC
#### DivCRev
#### Div
#### Div_Round
#### Abs
#### Sqr
* 平方
#### Sqrt
* 平方根
#### Cubet
* 立方根
#### Exp
* e指数
#### Ln
* 自然对数
#### SumLn
#### Arctan
* 反正切
#### Normalize
* 归一化
#### SortAscend, SortDescend
* 排序
#### SortIndexAscend, SortIndexDescend
#### SortRadixGetBufferSize
* 计算 SortRadixAscend 和 SortRadixDescend 所需缓存的大小。
#### SortRadixAscend, SortRadixDescend
#### SortRadixIndexGetBufferSize
* 计算 SortRadixIndexAscend 和 SortRadixIndexDescend 所需缓存大小。
#### SortRadixIndexAscend, SortRadixIndexDescend
#### TopKGetBufferSize
#### TopKInit
#### TopK
* 返回最大值
#### SwapBytes
#### Convert
#### Conj
#### ConjFlip
#### Magnitude
#### Phase
#### PowerSpectr
* 实部平方加虚部平方
#### Real
#### Imag
#### RealToCplx
#### CplxToReal
#### Threshold
* 门槛函数
#### Threshold_LT, Threshold_GT
#### Threshold_LTAbs, Threshold_GTAbs
#### Threshold_LTVal, Threshold_LTAbsVal, Threshold_GTVal, Threshold_LTValGTVal
#### Threshold_LTInv
#### CartToPolar
#### PolarToCart
#### MaxOrder
#### Flip
#### FindNearestOne
#### FindNearest
#### WinBartlett
#### WinBlackman
#### WinHamming
#### WinHann
#### WinKaiser
#### Sum
#### Max
#### MaxIndx
#### MaxAbs
#### MaxAbsIndx
#### Min
#### MinIndx
#### MinAbs
#### MinAbsIndx
#### MinMax
#### MinMaxIndx
#### ReplaceNAN
#### Mean
#### StdDev
#### MeanStdDev
#### Norm
#### NormDiff
#### DotProd
* 点积
#### MaxEvery, MinEvery
#### ZeroCrossing
#### CountInRange
#### SampleUp
* 上采
#### SampleDown
* 下采
#### PatternMatchGetBufferSize
#### PatternMatch
#### AutoCorrNormGetBufferSize
#### AutoCorrNorm
* 计算，有偏，无偏的向量自相关函数。（挪动相乘求和）
* <img src=".\离散自相关函数.png">
#### CrossCorrNormGetBufferSize
#### CrossCorrNorm
* 互相关
#### ConvolveGetBufferSize
#### Convolve
* 线性卷积
* <img src=".\卷积和.png">
#### ConvBiased
#### SumWindow
#### FIRMRGetSize
#### FIRMRInit
#### FIRMR
#### FIRSRGetSize
#### FIRSRInit
#### FIRSR
#### FIRSparseInit
* 稀疏滤波器
#### FIRSparseGetStateSize
#### FIRSparseSetDlyLine
#### FIRSparse
* <img src=".\稀疏滤波.png">
#### FIRGenGetBufferSize
#### FIRGenLowpass
#### FIRGenHighpass
#### FIRGenBandpass
#### FIRGenBandstop
#### FIRLMSGetTaps
#### FIRLMSGetDlyLine
#### FIRLMSSetDlyLine
#### FIRLMSGetStateSize
#### FIRLMSInit
#### FIRLMS
#### IIRInit
#### IIRInit_BiQuad
#### IIRGetStateSize
#### IIRGetStateSize_BiQuad
#### IIRGetDlyLine
#### IIRSetDlyLine
#### IIR
#### IIRSparseInit
#### IIRSparseGetStateSize
#### IIRSparse
#### IIRGenGetBufferSize
#### IIRGenLowpass, IIRGenHighpass
#### IIRIIRGetStateSize
#### IIRIIRInit
#### IIRIIRGetDlyLine
#### IIRIIRSetDlyLine
#### IIRIIR
#### FilterMedianGetBufferSize
#### FilterMedian
#### ResamplePolyphaseGetSize，ResamplePolyphaseFixedGetSize
#### ResamplePolyphaseInit, ResamplePolyphaseFixedInit
#### ResamplePolyphaseSetFixedFilter




























## <font color = yellow>滤波函数</font>

## <font color = yellow>变换函数</font>

## <font color = yellow>向量初始化函数</font>

## <font color = yellow>固定精度算术函数</font>

## <font color = yellow>数据压缩函数</font>
1
