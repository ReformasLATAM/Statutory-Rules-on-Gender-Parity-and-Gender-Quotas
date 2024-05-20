# Statutory Rules on Gender Parity and Gender Quotas in the National Governing Bodies of Latin American Political Parties

Welcome to the GitHub repository of the database "Statutory Rules on Gender Parity and Gender Quotas in the National Governing Bodies of Latin American Political Parties," maintained by members of the Political Reform Observatory in Latin America.

## Contents

- [Summary](#summary)
- [Description](#description)
- [Citation](#citation)

## Summary

The database contains information for describing and understanding how political parties in Latin America currently regulate women's participation in their national leadership bodies, particularly in Assemblies, Political Councils and Executive Committees. The information was collected by consulting the statutes of a sample of 54 political parties in Latin America, with a special focus on the statutory rules on gender parity and gender quotas in the national leadership bodies of party organizations. 

The selection of parties considered as relevant in 18 Latin American countries included in the observation units of the database was based on the framework created by Alcántara Sáez and Freidenberg (2001). It consists of four main principles: that a party a) had obtained representation in the lower house for the last three legislative elections (numerical strength in seats or votes obtained), b) had surpassed the 5% electoral threshold in the last three lower house legislative elections, c) had representation in all the country’s electoral districts (territorial strength) or that its representation in certain districts was clearly significant and d) had substantially  contributed to the party dynamics of the political system, meaning it exerted influence on the political system (even if it does not meet the previous criteria).

Members of the Observatory on Political Reforms in Latin America collected and coded the information. The responsible for information collection are Flavia Freidenberg (Institute for Legal Research, UNAM) and Carlos Guadarrama (Latin American Faculty of Social Sciences, Mexico City), while the responsible for coding the information are Flavia Freidenberg (Institute for Legal Research, UNAM), Carlos Guadarrama (Latin American Faculty of Social Sciences, Mexico City) and Karla Estrada (Facultad de Estudios Superiores Acatlán, UNAM). 

## Description

The directory `./Data/` contains the file `./Data/DD_Parity` where all relevant information regarding the database linked to the statutory rules on gender parity and gender quotas in the national governing bodies of Latin American political parties and its reforms is located. Specifically, the database consists of the following variables:

-   `party_id`: numeric key to identify each of the 54 parties in the database. The identification number was composed of the country and party numbers in the sample per country.

-   `party_acr`: abbreviations of each of the 54 parties in the database according to documentary sources from the same parties.

-   `country`: name of the country to which the political party belongs and from which the statutes were selected establishing internal rules regarding parity and quotas in the national governing bodies.

-   `cowcode`: country code according to the coding of "Correlates of War".
 https://correlatesofwar.org/data-sets/cow-country-codes.

-   `country_code`: country abbreviations according to the ISO three-letter code (ARG, MEX, SAL) http://utils.mucattu.com/iso_3166-1.html.

-   `statute_year`: political party statutes’ year of publication between 1996 and 2020, in which the internal rules regarding parity and quotas in the national governing bodies were consulted. Where information is not available, the number -9999 is used. 

-   `parity`: records presence or absence of statutory rules in political parties that stipulate gender parity in their national leadership. Values: No [0]: Party statutes do not provide rules establishing gender parity as a criterion for membership of national leadership bodies. Yes [1]: Party statutes provide rules establishing gender parity as a criterion for the composition of national leadership bodies.

-   `quotas`: records presence or absence of statutory rules in political parties that stipulate gender quotas in the composition of national leadership. Values: No [0]: Party statutes do not provide rules establishing gender quotas as a criterion for composition of national leadership bodies. Yes [1]: Party statutes provide rules establishing gender quotas as a criterion for the composition of national leadership bodies.

-   `percentage`: indicates the percentage that political party statutes establish for gender quotas. Values: 888: For cases where the statutes stipulate gender quotas but do not establish a figure for them.999: For cases where the statutes do not specify figures for gender quotas.

-   `directorate_bodies`: indicates whether the nature of the directorate bodies to which the gender parity and quotas rules of the political parties' statutes apply is specific or general for all directorate bodies. Values: Specific bodies [1]: The statutory rules of gender parity and quotas explicitly specify the directorate bodies to which these criteria apply in their composition. All bodies [2]: The statutory rules of gender parity and quotas do not establish a distinction between the directorate bodies to which these criteria apply in their composition. Not determined [99]: The statutory rules of gender parity and quotas do not stipulate which directorate bodies these criteria apply to in their composition.

-   `bodies`: indicates which specific governing bodies of political parties are covered by the rules on gender parity and quotas set out in their statutes. Values: Assembly [1]: The statutes of political parties establish the National Assemblies or its equivalent as one of the governing bodies to which the rules of parity and gender quotas apply. National Political Council [2]: The statutes of political parties establish the National Political Council or its equivalent as one of the governing bodies to which rules of parity and gender quotas apply. National Executive Committee [3]: The statutes of political parties establish the National Executive Committee or its equivalent as one of the governing bodies to which rules of parity and gender quotas apply. 

-   `art_n`: indicates the article number of the political parties statutes in which the parity and gender quotas rules are established.

## Citation

``` r
Freidenberg, Flavia. Dir., 2023, “Statutory rules on gender parity and quotas in the national leadership bodies in Latin American political parties”. Observatory of Political Reforms in Latin America (1978-2023). Mexico City: Institute for Legal Research (IIJ-UNAM) and Washington, D.C.: Secretariat for Strengthening Democracy of the Organization of American (SSD/OAS), V1. Available at: https://bit.ly/3E09uVL
```