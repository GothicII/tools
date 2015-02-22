
GothicZTEX 2.6
==============

What for...
¯¯¯¯¯¯¯¯¯¯¯
This tool is intended to convert the compressed
textures of the Gothic II Add-On (v2.6) back to
TGA files (including directories).

Preparation
¯¯¯¯¯¯¯¯¯¯¯
At first expand the following VDFS volumes to
your harddrive (if not already done):
[g2addon]\Data\Textures.vdf
[g2addon]\Data\Textures_Addon.vdf

note: you may use GothicVDFS for this task.

Installation / Usage
¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯
Copy the two files (exe/ini) into the tools
directory ([g2addon]\_work\tools\ZTEX), select
the root path ([g2addon]\_work\data\Textures),
and press the "Convert" button.

Comments
¯¯¯¯¯¯¯¯
In the Add-On the Loading.tga + StartScreen.tga
are now placed in [textures]/Desktop/nomip_16bit.
You should disable (rename to .tga.bak) the old
versions in [textures]/Desktop/nomip because it
is not allowed to have files with identical names
in the texture folder (and subfolders).

You'll never (mostly) get the original image
back because of the DXTC/S3TC compression.

The images are not scaled to its original size.
However, this is not a big problem (only few).

Legal Stuff
¯¯¯¯¯¯¯¯¯¯¯
Copyright (c) 2001-2003, Nico Bendlin
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

  * Redistributions of source code must retain the above copyright notice,
    this list of conditions and the following disclaimer.
  * Redistributions in binary form must reproduce the above copyright notice,
    this list of conditions and the following disclaimer in the documentation
    and/or other materials provided with the distribution.
  * Neither the name of the copyright holder nor the names of its
    contributors may be used to endorse or promote products derived from this
    software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE
LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR
CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF
SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS
INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN
CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE)
ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE
POSSIBILITY OF SUCH DAMAGE.
