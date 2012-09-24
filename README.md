
Moa template "bowtie"

Copyright 2012 Mark Fiers
This software is under the gplv3 license, please see "COPYING" for details



### Description

Run BOWTIE on an set of input files (query) vs a database index.

### Filesets

input
:    Fasta/fastq input files for bowtie

     - *type:* set<br>
     - *category:* input<br>
     - *optional:* no

output
:    Output files

     - *type:* map<br>
     - *category:* output<br>
     - *optional:* no



### Parameters

db
:    The (basename of the) bowtie database to use.

     *type: *string<br>
       optional:no

input_format
:    Format of the input files

     *type: *set<br>
       optional:yes

extra_params
:    extra parameters to feed bowtie

     *type: *string<br>
       optional:yes



### Private parameters

db
:    The (basename of the) bowtie database to use.

     *type: *string<br>
       optional:no

input_format
:    Format of the input files

     *type: *set<br>
       optional:yes

extra_params
:    extra parameters to feed bowtie

     *type: *string<br>
       optional:yes



### General

* Author: Mark Fiers
* Backend: ruff

*This file is automatically generated by "moa_template_setup"*