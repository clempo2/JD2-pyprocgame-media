## JD2-pyprocgame-media

JD2-pyprocgame-media is a repackaging of the [JD-pyprocgame](https://github.com/preble/JD-pyprocgame) media kit with assets organized in a content structure suitable for [JD2-pyprocgame](https://github.com/clempo2/JD2-pyprocgame).

JD2-pyprocgame is new software for the [Judge Dredd](https://www.ipdb.org/machine.cgi?id=1322) pinball machine written against [pyprocgame](http://pyprocgame.pindev.org/) running on a [P-ROC](https://www.multimorphic.com/store/circuit-boards/p-roc/) controller. It is a more polished version of [JD-pyprocgame](https://github.com/preble/JD-pyprocgame) by Gerry Stellenberg et al.

## Installation

- Copy the media archives to the JD2-pyprocgame source.  
    ```
    copy jd2_media_a.tar.gz C:\P-ROC\JD2-pyprocgame  
    copy jd2_media_b.tar.gz C:\P-ROC\JD2-pyprocgame
    ```
- Extract the media files. This will populate the existing .\assets directory with more files.  
    ```
    cd C:\P-ROC\JD2-pryprocgame  
    tar xf jd2_media_a.tar.gz  
    tar xf jd2_media_b.tar.gz
    ```
- Optionally delete the media archives to save space.  
    ```
    del jd2_media_a.tar.gz  
    del jd2_media_b.tar.gz
    ```
## Authors

JD2-pyprocgame is a collaboration of many people.

Game Play: Gerry Stellenberg  
Software: Adam Preble, Clement Pellerin  
Sound and Music: Rob Keller, Jonathan Coultan  
Dots: Travis Highrise  
Special Thanks to: Steven Duchac, Rob Anthony, Michael Ocean, Josh Kugler

## License

JD2-pyprocgame-media and its use in JD2-pyprocgame is made possible by the express written permission of the original author.

JD2-pyprocgame-media repackaging is Copyright (c) 2022 Clement Pellerin  
JD2-pyprocgame media kit is Copyright (c) 2011 Gerry Stellenberg

The JD-pyprocgame media kit is distributed under a restrictive custom license. JD2-pyprocgame-media inherits the same license.

All rights reserved except as delineated below.

Any use of this material requires express written permission of the copyright
holder except permission is hereby granted, free of charge, to any person
obtaining a copy of this material (the "Media Kit"), to use the Media Kit
exclusively in the context of JD-pyprocgame for non-commercial purposes,
subject to the following conditions:

1) Any use associated with a physical pinball machine requires the use of
Pinball-Remote Operations Controller (P-ROC) hardware.

2) The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Media Kit.

THE MEDIA KIT IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE MEDIA KIT OR THE USE OR OTHER DEALINGS IN THE
MEDIA KIT.
