#################

vcf2bed documentation

author: Nolan Kuza (nkuza8@gmail.com)
date: 1/5/19

#################

Converters a .vcf file to a .bed file.

usage: vcf2bed.py [-h] -i INPUT [-o OUTPUT]

optional arguments:
  -h, --help            show this help message and exit
  -o OUTPUT, --output OUTPUT
                        The name of the file to output to (will overwrite file
                        if it already exists). If this argument is not
                        specified, output will be to the input file name with a .bed extension.  

required arguments:
  -i INPUT, --input INPUT
                        The name of the input .vcf file.

example:

	There is a vcf file named genome.vcf
	We want to convert it to genome.new.bed

	Then run with:
		
		python vcf2bed.py -i genome.vcf -o genome.new.bed

	The program will output genome.new.bed

other:
	Make sure the input file has extension .vcf
