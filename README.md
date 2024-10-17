# Micro-Planner files, 1971-1982 
This repository contains a set of files from 1971-1982 that constitute the source and related files of early versions of [Micro-Planner, an implementation of part of the Planner programming language](https://en.wikipedia.org/wiki/Planner_(programming_language)#Micro-planner_implementation) originally created at MIT by Gerald Jay Sussman, Terry Winograd, and Eugene Charniak in 1970. The Micro-Planner implementation was used in the early natural-language understanding program, [SHRDLU](https://en.wikipedia.org/wiki/SHRDLU). Manuals to Micro-Planner are available on MIT DSpace in Artificial Intelligence Memo [No. 203](http://hdl.handle.net/1721.1/5833) and [No. 203A (updated)](http://hdl.handle.net/1721.1/6184). The files available in this repo are a part of the [Massachusetts Institute of Technology, Tapes of Tech Square (ToTS) collection](https://archivesspace.mit.edu/repositories/2/resources/1265) at the MIT Libraries Department of Distinctive Collections (DDC).
## File organization and details
### [plnr](../main/plnr)
The files within this directory are the Micro-Planner specific files from [7 different tape image files](../main/tapeimagelist.txt) in the [ToTS collection](https://archivesspace.mit.edu/repositories/2/resources/1265) that constitute files from multiple early versions. Files are from ITS backup tapes. Most files are written in the Micro-Planner programming language and were originally created on a PDP-10 timeshare computer running the ITS operating system.  

Files were extracted from the tape images using the [itstar program](https://github.com/PDP-10/itstar). The filenames have been adapted to Unix conventions, as per the itstar translation. The original filename syntax would be formatted like, `PLNR; PLNR 176`, for example. All files have been placed into this artificial `plnr` directory for organizational purposes. The files extracted from the tape images were put into sub-folders with a corresponding name to the tapes listed in the `tapelist.txt` file.

Each directory contains a `_info_.plnr` file that describes the main files in the directory and how they function within Micro-Planner. Multiple manuals exist in the files as well which are versions of the published manuals found in the AI Memos cited above. They are typically just named `manual` such as `manual.179`.
### [codemeta.json](../main/codemeta.json)
This file is metadata about the Micro-Planner files, using the [CodeMeta Project](https://codemeta.github.io/) schema.
### [LICENSE](../main/LICENSE)
This file describes the details about the rights to these files. See [Rights](#rights) for additional information.
### [README.md](../main/README.md)
This file is the readme detailing the content and context for this repository.
### [tree.txt](../main/tree.txt)
A file tree listing the files in the [`planr`](../main/planr) directory showing the original file timestamps as extracted from the tape images.
### [tapeimagelist.txt](../main/tapeimagelist.txt)
A list of all the tape images and their paths in the ToTS collection that these files came from.

## Preferred Citation
[filename], Micro-Planner files, 1971-1982, Massachusetts Institute of Technology, Tapes of Tech Square (ToTS) collection, MC-0741. Massachusetts Institute of Technology, Department of Distinctive Collections, Cambridge, Massachusetts. [swh:1:dir:afcbf89b68664105987e14e1e85a52ee04102a6b](https://archive.softwareheritage.org/swh:1:dir:afcbf89b68664105987e14e1e85a52ee04102a6b)
## Rights
To the extent that MIT holds rights in these files, they are released under the terms of the [MIT License](https://opensource.org/licenses/MIT). See the `LICENSE` file for more information. Any questions about permissions should be directed to [permissions-lib@mit.edu](mailto:permissions-lib@mit.edu)
## Acknowledgements
Thanks to [Eric Swenson](https://github.com/eswenson1) for help with identifying these files.