Demo of pure CSS filters (specifically SVG filters) for gamma (correction) in OSD.  This applies an SVG gamma filter to the whole canvas using CSS filters and filter url to apply SVG filters. 1.5 amplitude, 2.5 exponent, 0 offset (can be changed). Commented out values (.5, .5, 0 iirc) are for subtractive gamma correction on 20.dzi which gamma is too high. Pathology off of second image from OSD user github: sinamcr7 provided, tiles removed from this can be downloaded or replaced. Credit me if you use this code.

### Related resources:
* Gamma Correction (involves math): https://en.wikipedia.org/wiki/Gamma_correction
* feComponentTransfer SVG Filters (CSS part): https://developer.mozilla.org/en-US/docs/Web/SVG/Reference/Element/feComponentTransfer
* transfer function element attributes: https://drafts.fxtf.org/filter-effects/#feFuncRElement
* For gamma, the function is defined by the following exponential function: C' = amplitude * pow(C, exponent) + offset

Example in operation, video and unfiltered pic (caddy_crop.jpg) also in repo:

https://github.com/user-attachments/assets/8eec6263-8264-4804-829e-df7db811ddc5

Using OSD and 20.dzi and tiles this is gamma subtracted :

https://github.com/user-attachments/assets/7f6395f6-035f-4804-882a-00f7fa5ce5e3

