Tested on USB 2.0 on a PC with Intel i7 and Titan Xp.

| Image size  |      Filters in subsequent layers    | Output Size  |  FPS | NumParams | NumFLOPs | 
|----------|:-------------:|------:|------:|------:| ------:|
| 1 x 256 x 256 x 2 | [32,64,128,256] | 1 x 256 x 256 x 2 | 50 |  |  |
| 1 x 256 x 256 x 6 | [32,64,128,256] | 1 x 256 x 256 x 2 | 36 |  |  |
| 1 x 256 x 256 x 6 | [32,64,128,256] | 1 x 256 x 256 x 4 | 36  |  |  |
| 1 x 256 x 256 x 6 | [32,64,128,256] | 1 x 256 x 256 x 8 | 26  |  |  |
| 1 x 256 x 256 x 24 | [32,64,128,256] | 1 x 256 x 256 x 8 | 15  |  |  |
| 1 x 256 x 256 x 24 | [32,64,128,256] | 1 x 256 x 256 x 32 | 7.7  |  |  |
| 4 x 256 x 256 x 6 | [32,64,128,256] | 1 x 256 x 256 x 8 | Internal compiler error. Aborting!  |  |  |
| 1 x 128 x 128 x 96 | [32,64,128,256] | 1 x 128 x 128 x 128 | 6.1  |  |  |
| 1 x 512 x 512 x 2 | [32,64,128,256] | 1 x 512 x 512 x 2 | Internal compiler error. Aborting! |  |  | 
| 1 x 512 x 512 x 6 | [32,64,128,256] | 1 x 512 x 512 x 2 | Internal compiler error. Aborting! |  |  | 
| 1 x 512 x 512 x 6 | [32,64,128,256] | 1 x 512 x 512 x 4 | Internal compiler error. Aborting! |  |  | 
| 1 x 512 x 512 x 6 | [32,64,128,256] | 1 x 512 x 512 x 8 | 3.5 |  |  | 
| 1 x 480 x 480 x 2 | [32,64,128,256] | 1 x 480 x 480 x 2 | 11.4 |  |  | 
| 1 x 480 x 480 x 6 | [32,64,128,256] | 1 x 480 x 480 x 2 | 8.8 |  |  | 
| 1 x 480 x 480 x 6 | [32,64,128,256] | 1 x 480 x 480 x 4 | 8.8 |  |  | 
| 1 x 480 x 480 x 6 | [32,64,128,256] | 1 x 480 x 480 x 8 | Internal compiler error. Aborting! |  |  | 
