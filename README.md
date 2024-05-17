# gwas2vcf
A tool to convert GWAS TSV files to VCF format

This tool 'gwas2vcf' converts GWAS results file such as the tsv.bgz files from the UK Biobank studies into the standard VCF 4.0 format.
It was tested in Python 3.11.6, so creating a virtual environment with this version is recommended.

USAGE:: $ gwas2vcf [-h] -i INPUT -o OUTPUT

Convert GWAS file VCF format.

options:
  -h, --help            show this help message and exit
  -i INPUT, --input INPUT
                        please provide the path for the input file with the extension .bgz
  -o OUTPUT, --output OUTPUT
                        please provide desire output file name, tool will automatically append the .vcf.gz extension

If you like my tool or have suggestions for improvements, please consider following me on X and leave a post.
https://x.com/VK_Ulaganathan
