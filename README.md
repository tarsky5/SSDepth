# SSDepth
Reproduction of the SSD device "the vOICe" (Meijer, 1992) with multiple waveform handling for depth representation.

## Description
This sample code :
1. convert an image and it's (compressed) depth greyscale representation to 50x50 matrices
2. compute a SIN wave (image) and a TRIANGLE wave (depth) of different frequencies per lines
3. ponderate the intensity of each wave by the greyscale intensity of the lines' pixels.
4. mix the sounds & play the image's conversion and depth conversion succesively.

Note : The bottom and top halves of the image are computed and separated by stereo to favorise the discrimination of dynamics in ambigous letters (e.g O and C).

## Examples

### Social scene

#### Image transformations

Top left : Original image squared
Top right : 50x50 conversion of the original image
Bottom left : Original depth map squared
Bottom right : 50x50 conversion of the original depth map

![result_social](https://user-images.githubusercontent.com/78429558/236629877-771b920b-c4bb-46ef-8b15-bd832ce26e5f.png)

#### Sound Result

https://user-images.githubusercontent.com/78429558/236630053-9b5f7280-f599-4eee-a3d7-14655617e283.mp4

### Table

#### Image transformations

![table](https://user-images.githubusercontent.com/78429558/236630082-7ae9fc20-b182-4a38-a301-315e62fe1258.png)

#### Sound Result

https://user-images.githubusercontent.com/78429558/236630100-a7ca5b21-60ab-4ea2-bc19-512a0d64983a.mp4

### Hand

#### Image transformations

![main](https://user-images.githubusercontent.com/78429558/236630128-3db5eb66-e5e3-4a66-82c0-18fe7ebd3eb1.png)

#### Sound Result

https://user-images.githubusercontent.com/78429558/236630133-0e0302e8-5eed-4557-aa23-729bce72d498.mp4





