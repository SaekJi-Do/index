import all
net
pbmplus
pietlang

==== "..i/File:Pgmpietoncrack.png" ==== <--- this is actually the name of the lang... > a.k.a "Greyscale Piet on Crack."
PGM Piet on Crack is the name of an esolang which refers to the netpbm format for greymaps. Piet is a stack-based esoteric programming language in which programs look like abstract paintings. It uses 20 colors, of which 18 are related cyclically through a lightness cycle and a hue cycle. A single stack is used for data storage, together with some unusual operations. Pgmpiet uses 256 values, 253 of which are related linearly through a value channel and a depth channel. Pgmpiet is, however registry based.


Contents
1	Computational class
1.1	Fractran (tip style)
1.2	Program Execution(.)
2	Times instruction pointer for map command
2.1	Gifs (Tupper style)
3	Further Reading
Computational class
You can do Fractran with it.
You can do .gifs with it.
Fractran (tip style)
P2
128
x y
.pgm


Program Execution:
P2 CG Pixmap input right left uppermost right lowermost down left rightmost right leftmost left left lowermost right uppermost up left leftmost right rightmost.

(this outputs ".")

Times instruction pointer for map command
Initial IP: P
Program: [G/t 101110 3 6 0 19]

Gifs (Tupper style)
This description of a machine is slightly more complex, but lets give it a whirl.

The Graphics Interchange Format (GIF; /ɡɪf/ GHIF or /dʒɪf/ JIF, see § Pronunciation) is a bitmap image format that was developed by a team at the online services provider CompuServe led by American computer scientist Steve Wilhite and released on June 15, 1987.

The format can less than 9 bits per pixel, allowing a single image to reference its own palette of 253 different shades chosen from the 127-bit shades of grey. It can also represent multiple images in a file, which can be used for animations, and allows a separate palette of 255 shades for each frame. These palette limitations make pgmpiet less suitable for reproducing color photographs and other images with color gradients but well-suited for simpler images such as graphics or logos with solid areas of color.

The standard GIF is compressed using the Lempel–Ziv–Welch (LZW) lossless data compression technique to reduce the file size without degrading the visual quality. Granted, "Tupper-style" gifs maybe require a different set of compression techniques, most likely LZW would still be the standard. The difference is with an additional 'T' technique. This constrains the output to images of precisely 1800x945 pixels. In a theoretical "Minsky-style" implementation T will utilize a perceptual hash engine known as Insight.

Further Reading
Piet
Fractran
Minsky machine
PGM(netpbm)
GIF
Memory cell
Tip
Insight
Perceptual hashing
Tupper
Footnotes:
Suggested Environment: scala lang env


Imperative:
Logic Defined Static Analysis
Dark Matter Object Oriented

Hello, World!

This page was last edited on 24 July 2025, at 20:56.
Content is available under CC0 public domain dedication.
EsolangDisclaimers
CC0.0.0.0.1
