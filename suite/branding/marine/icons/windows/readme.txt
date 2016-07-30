 This Source Code Form is subject to the terms of the Mozilla Public
 # License, v. 2.0. If a copy of the MPL was not distributed with this
 # file, You can obtain one at http://mozilla.org/MPL/2.0/.



The icons in this directory are Win32 program icons, file association icons, 
and window icons (to appear in the upper left corner of various windows).



Each icon contains the following devices images:
48x48, 32x32, and 16x16 - True color XP (Contains alpha shadows)

See bug http://bugzilla.mozilla.org/show_bug.cgi?id=99380 for a lot of rambling about
icons.



Window icons:
Should be named using the following convention: [NAME]-window.ico where [NAME]
represents the name of the window. Example:
history-window.ico

Blank template icon should be available as: template-window.ico

XXXFIXME 
Some icons have been given names such as downloadManager.ico and is because 
there are two naming schemes for windows. This should be remedied. 
Bug http://bugzilla.mozilla.org/show_bug.cgi?id=199576
XXXFIXME


File association icons:
Should be named using the following convention: [NAME]-file.ico where [NAME]
represents the type of file it is. Example:
image-file.ico

Blank template icon should be available as: template-file.ico


Program icon:
Currently, the only available program icon is mozilla.ico
