# convertshape
 convertshape - shell scripts (and VNMR macro) that convert shape
 definitions
 (shapelib/*.RF) into decoupling / spinlock pattern definitions
 (shapelib/*.DEC) and vice versa.

 Copyright 2016 University of Oregon

 Licensed under the Apache License, Version 2.0 (the "License");
 you may not use this file except in compliance with the License.
 You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

 Unless required by applicable law or agreed to in writing, software
 distributed under the License is distributed on an "AS IS" BASIS,
 WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 See the License for the specific language governing permissions and
 limitations under the License.

                                SUBMISSION FORM

Submitter:      Rolf Kyburz, Agilent Technologies
Date submitted: 1995-01-09
                1996-04-16 (added convertpattern utility)

File name:      convertshape
Directory:      shapelib
Description:    shell scripts (and VNMR macro) that convert shape definitions
                (shapelib/*.RF) into decoupling / spinlock pattern definitions
                (shapelib/*.DEC) and vice versa.

Related files:  bin/convertshape        bin/convertpattern
                maclib/convertshape     maclib/convertpattern
                manual/convertshape     manual/convertpattern

Existing VnmrJ / VNMR files which are superseded or
otherwise affected by this submission:  none

Hardware configuration limitations:     WFG
Known software version compatibility:   any
Known OS version compatibility:         SunOS 4.1/4.1.x, Solaris 2.3

**This software has not been tested on OpenVnmrJ. Use at your own risk.**

To install this user contribution:  
Download the repository from GitHub and checkout the tag of the contribution you want.
Typically tags end in the version (e.g. -v1.0)

     git clone https://github.com/OpenVnmrJ/shapelib  
     cd shapelib  
     git checkout convertshape-v1.0


You may also download the archive directly from github at

    https://github.com/OpenVnmrJ/maclib/archive/convertshape-v1.0.zip

Read convertshape.README for installation instructions.

In most cases, move the contribution to /vnmr/userlib/shapelib 
then use extract to install the contribution:  

    extract shapelib/convertshape