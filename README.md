The default 5mm dots template was too compact for my handwriting.  So, I wrote a simple tex program in an online LaTeX editor - [overleaf](https://www.overleaf.com/) to generate a 6mm spaced dots template PDF specific to the Supernote Nomad.
Once I had the PDF, I used  [ImageMagick](https://imagemagick.org/) to generate the template in PNG form:
  `magick -density 300 -units PixelsPerInch <TEMPLATE-NAME.pdf> -resize 1404x1872 -quality 90 <TEMPLATE-NAME.png>`
The tex program I wrote is available at https://www.overleaf.com/read/qqvdyssvqmhh#701c5c for anyone to copy and customize for their own use.
  
This can be easily adapted to any device(A5X*,A4X*) - by just updating page height and width values.

Other possible tex programs that can be adapted: [Printable Paper with LaTeX and TikZ](https://michaelgoerz.net/notes//printable-paper-with-latex-and-tikz/)
  
