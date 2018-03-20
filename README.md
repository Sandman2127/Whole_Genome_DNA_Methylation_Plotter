Whole_Genome_DNA_Methylation_Plotter

The program takes in a bin file organized by chromosome and a methylation ratio file directly out of BSmap_ratio.py and generates the data necessary for a whole genome plot of that mutant. The necessary file format is shown below.

python2.7 WG_methylation_plotter.py -binfile <binfile> -metfile <metfile> -p <int 1 to 5>

-binfile format:

1	0	500000
1	500000	1000000

-metfile format:

chr1	8	+	CHH	0.000	1.00	0	1	3	3	0.000	0.793
chr1	9	+	CHH	1.000	1.00	1	1	4	4	0.207	1.000
chr1	10	+	CHH	1.000	2.00	2	2	4	4	0.342	1.000
