# An introduction to antigenic cartography for HU students

This repo contains an introduction and example data to familiarise yourself with antigenic cartography.

## Software

[Racmacs](https://acorg.github.io/Racmacs/index.html). Either install from CRAN or from [GitHub](https://github.com/acorg/Racmacs).

## Tutorials and practical information

[Racmacs documentation](https://acorg.github.io/Racmacs/index.html)

[An introduction to antigenic cartography by Sam Wilks](https://acorg.github.io/Racmacs/articles/intro-to-antigenic-cartography.html)

[Making an antigenic map from titer data](https://acorg.github.io/Racmacs/articles/making-a-map-from-scratch.html)

## Example data and tasks

[Here](data/titertable.csv) is some example titer data (the columns are the different sera, the rows are the variants). It is from hamsters that were infected with different SARS-CoV-2 variants and then titrated against SARS-CoV-2 variants. Install RStudio and Racmacs and solve the tasks below.

1. Turn the titer table into an antigenic map using Racmacs. If you get stuck, see here [https://acorg.github.io/Racmacs/articles/making-a-map-from-scratch.html](https://acorg.github.io/Racmacs/articles/making-a-map-from-scratch.html)

2. Colour the viruses and sera with sensible colours.

3. What does the map tell you about the antigenic relationships between different SARS-CoV-2 variants? Does it make sense?

4. Make a map in three dimensions and check whether the antigenic map fits well in two or three dimensions. See [here](https://acorg.github.io/Racmacs/reference/dimensionTestMap.html).

5. What is the uncertainty of the positioning of the antigens. See [here](https://acorg.github.io/Racmacs/reference/triangulationBlobs.html) and [here](https://acorg.github.io/Racmacs/reference/bootstrapMap.html)/[here](https://acorg.github.io/Racmacs/reference/bootstrapBlobs.html).

## Scientific literature

The initial publication on antigenic cartography: [Mapping the Antigenic and Genetic Evolution of Influenza Virus](https://www.science.org/doi/10.1126/science.1097211)

[Antigenic and Genetic Characteristics of Swine-Origin 2009 A(H1N1) Influenza Viruses Circulating in Humans](https://www.science.org/doi/full/10.1126/science.1176225)

[Antibody landscapes after influenza virus infection or vaccination](https://www.science.org/doi/10.1126/science.1256427)

[Dengue viruses cluster antigenically but not as discrete serotypes](https://www.science.org/doi/10.1126/science.aac5017)

[Mapping SARS-CoV-2 antigenic relationships and serological responses](https://www.science.org/doi/full/10.1126/science.adj0070)

[Antigenic cartography using variant-specific hamster sera reveals substantial antigenic variation among Omicron subvariants](https://www.pnas.org/doi/10.1073/pnas.2310917121)




