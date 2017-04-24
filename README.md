# TCGA_germline-nf
annotation of germline variants from TCGA data

#### Dependencies
1. Install [nextflow](http://www.nextflow.io/).

	```bash
	curl -fsSL get.nextflow.io | bash
	```
	And move it to a location in your `$PATH` (`/usr/local/bin` for example here):
	```bash
	sudo mv nextflow /usr/local/bin
	```

2. Install [annovar](http://annovar.openbioinformatics.org/en/latest/) and move the perl script `annotate_variation.pl` in your path.
