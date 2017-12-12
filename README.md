# ReadDepth Plot

A standalone script which reads in 3-column output from (e.g. `samtools depth test.bam > test_coverage.txt`) and creates a heatmap plot representing depth as a function of base poition.

As this is intended to be a comparative figure, there is an expectation that at least 2 samples (files) will be found in the input directory.

Files should be named with the preferred sample name and end with "_coverage.txt".

A requirements file is included and the modules can be installed using pip: `pip install -r requirements.txt`. Root authority may be required.


