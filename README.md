# **Not-So-FastQC**

*Disclaimer: Not-So-FastQC is an independent project and is not affiliated with, officially endorsed by, or maintained by the Babraham Institute.*

Programming project from my bioinformatics bachelor education, and my first ever coding project. 

Not-So-FastQC is a high throughput sequence data quality control software inspired by the popular [FastQC](https://www.bioinformatics.babraham.ac.uk/projects/fastqc/) software. 

## Using the software:

Upon starting the [script](Not-So-FastQC.py), you will be met with a simple GUI window: 

![open](welcome_screen.png)

Use the top left button to open a fastq file. By default, the software will sample the file in order to provide faster results. You can turn this off by checking the "bypass data reduction" checkbox. This will provide more accurate results, but will take a much longer time to compute.

Once a file is open, you see will see basic statistics about the file, and tabs with the data plots:

![open](open_file.png)
![open](per_base_sequence_quality.png)

## Main Dependencies:

The software is fully written with Python, Main packages utilized include:

```
tkinker
Bio
matplotlib.pyplot
pandas
numpy
scipy.stats
matplotlib.backends.backend_tkagg

```
