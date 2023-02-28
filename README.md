## Abstract 
In this project, we present the implementation and investigation of a technique for
fusing a bracketed exposure sequence into a high-quality image, without the need
for physically-based HDR assembly. This technique, called ExposureF usion,
was introduced by T. Mertens, J. Kautz, F in their paper [Exposure Fusion](https://web.stanford.edu/class/cs231m/project-1/exposure-fusion.pdf). Their approach simplifies the
image acquisition process by skipping the HDR assembly step, and is computa-
tionally efficient and versatile enough to include flash images in the sequence.
The technique blends multiple exposures in a multi-resolution fashion, guided by
quality measures such as saturation and contrast. The resulting image quality is
comparable to existing tone mapping operators and demonstrates the potential of
our proposed method. 


## Illustraion 

<p align="center">
<img src="https://github.com/souhaiel1/Exposure-Fusion/blob/main//Results/illustration.PNG" />
</p>

## Various Results
<p align="center">
<img src="https://github.com/souhaiel1/Exposure-Fusion/blob/main//Results/res1.PNG" />
</p>

<p align="center">
<img src="https://github.com/souhaiel1/Exposure-Fusion/blob/main//Results/res2.PNG" />
</p>

<p align="center">
<img src="https://github.com/souhaiel1/Exposure-Fusion/blob/main//Results/res3.PNG" />
</p>
