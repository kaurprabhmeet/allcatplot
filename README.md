# allcatplot

## Purpose

`allcatplot` is a Stata command that ensures all predefined response categories for a variable, including those not present in the dataset, are included in in a graph. Traditional plotting methods omit such unselected categories, potentially skewing interpretation. allcatplot uses the predefined value labels to identify and label such omitted response options and add them to the graph as zero-height bars. It also supports custom lists, labels and graph customization directly through the program syntax. This program is especially useful for surveys and assessments utilizing likert scales or other structured response options, where it offers a holistic view of all potential responses in the graph, thereby ensuring a comprehensive understanding of the full range of response options.

The command is available on the [SSC library](https://ideas.repec.org/c/boc/bocode/s459328.html).
## Installation

To install the `allcatplot` within Stata please type:

   ```stata
   ssc install allcatplot
```
The command has been co-authored with [Kabira Namit](https://github.com/kabira-namit-kapoor) and [Zaeen de Souza](https://github.com/zaeendesouza/zaeendesouza).
