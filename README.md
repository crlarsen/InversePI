# Python 3 Scripts to Prototype Binary32/Binary64/Binary128 Reciprocal Circuit

## Description

Compute floating point reciprocal using Newton's Method. The code marks the location of the binary point, and avoids the numerical instabilities which occur in the C++ version of the code.

The code is a quick and dirty hack. It IS NOT production quality code. Use at your own risk. It is strictly "Proof of Concept" code.

Multiplying by the reciprocal as a substitute for divison is known to produce inaccurate results in the last bit, or two of the result.

The code is explained in the video series [Building an FPU in Verilog](https://www.youtube.com/playlist?list=PLlO9sSrh8HrwcDHAtwec1ycV-m50nfUVs).
See the video *Building an FPU In Verilog: Floating Point Division, Part 6*.

## Manifest

|   Filename    |                             Description                             |
|---------------|---------------------------------------------------------------------|
| README.md     | This file.                                                          |
| InversePI-32  | Python 3 script to compute and round reciprocal of binary32 values  |
| InversePI-64  | Python 3 script to compute and round reciprocal of binary64 values  |
| InversePI-128 | Python 3 script to compute and round reciprocal of binary128 values |

## Copyright

:copyright: Chris Larsen, 2022
