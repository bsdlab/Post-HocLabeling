# Post-hoc labeling of EEG for benchmarking of decoding methods
This is the source code for the post-hoc labelled dataset generation framework:

> Castaño-Candamil, Sebastián, Andreas Meinel, and Michael Tangermann. _"Post-hoc labeling of arbitrary M/EEG recordings for data-efficient evaluation of neural decoding methods."_ Frontiers in neuroinformatics 13 (2019).

## Getting started
1. Run the download_dependecies.m script to download and configure the bbci_toolbox.
2. Download EEG data available at https://zenodo.org/record/1065107#.WhaCX3XyvCI and place the .mat files under ./data
3. Run the script test_postHocLabelling.m to see usage example.

## Comments on the New York's head model -
The Original head model can be downloaded at https://www.parralab.org/nyhead/
The .mat available here was stripped to the strictly necessary data in order to run this toolbox. Head model is licensed under GPL v3:
>The New York Head (ICBM-NY)

 >> Copyright (C) 2015 Yu Huang (Andy), Lucas C. Parra and Stefan Haufe

  >>This program is free software: you can redistribute it and/or modify
  >>it under the terms of the GNU General Public License as published by
  >>the Free Software Foundation, either version 3 of the License, or
  >>(at your option) any later version.

  >>This program is distributed in the hope that it will be useful,
  >>but WITHOUT ANY WARRANTY; without even the implied warranty of
  >>MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
  >>GNU General Public License for more details.

  >>You should have received a copy of the GNU General Public License
  >>along with this program.  If not, see <http://www.gnu.org/licenses/>.

>>Contact:
>>Yu (Andy) Huang  
>>Dept. of Biomedical Engineering, City College of New York  
>>Center for Discovery and Innovation, Rm. 13-320,  
>>85 St Nicholas Terrace, New York, NY 10027  
>>Email: andypotatohy@gmail.com  
>>yhuang16@citymail.cuny.edu
