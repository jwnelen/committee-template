# Committee-template

## Problem
- takes too much time to build one every year
- Style varies over the different sites.

## Proposal by Tim
This is a solution adapted from the proposal by [Tim van der Lippe](https://github.com/TimvdLippe).  
He proposed a solution where we have a core development team that implementes custom elements that can be used by committees. His full analysis and vision can be found [here](https://github.com/WISVCH/committee-website-vision/blob/master/README.md)  

## Changed
This is a very good analysis and there is a lot that can be improved in the committee websites. But one problem that we found with the solution that Tim suggested was that most committee members are not able to use those somewhat complex modules.  
We want to have a simple `index.html`, `style.css` and `script.js` solution which is generic for every committee.

## Goal
Summarized: 
- Very generic template on which the commmittees can build. 
- Easy and simple to use.
- Lot of flexability. 
- No special dependencies.

### Provide
So what should we provide?
- Fonts
- Colors
- Navigation bar
- Footer
- Different html files that all load a different page
- General style of displaying the committee.

### Bootstrap
We are now working on a version that is **with bootstrap**. This is debatable since not everyone understands boostrap but it is very easy to use.

### Other options
- We could setup an repo for every committee inside the [WISVCH organisation](https://github.com/WISVCH)  (Then all sites can be edited by members of CH that may have more knowledge then the committee member from the committee itself. )

