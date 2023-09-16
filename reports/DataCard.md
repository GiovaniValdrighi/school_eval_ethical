# Basic Education Assessment System 2019 (SAEB)
Dataset with school assessment from Brazil performed in 2019. It contains the results of Portuguese and math tests of students from each school for different education levels (primary education, high school). It also has questionnaires about social and economic conditions answered by students, teachers, and the principal. Brazil's government collects the data in an initiative from INEP. This data is suited for analysis of school performance in Brazil.

#### Dataset Link
<!-- info: Provide a link to the dataset: -->
<!-- width: half -->
https://www.gov.br/inep/pt-br/areas-de-atuacao/avaliacao-e-exames-educacionais/saeb/resultados

#### Data Card Author(s)
<!-- info: Select **one role per** Data Card Author:

(Usage Note: Select the most appropriate choice to describe the author's role
in creating the Data Card.) -->
<!-- width: half -->
- **Juan David Nieto, Team: H.IAAC Unicamp** (Contributor)
- **Giovani de Almeida Valdrighi, Team: H.IAAC Unicamp** (Contributor)

## Authorship
### Publishers
#### Publishing Organization(s)
<!-- scope: telescope -->
<!-- info: Provide the names of the institution or organization responsible
for publishing the dataset: -->
National Institute of Educational Studies and Research Anisio Teixeira (INEP)

#### Industry Type(s)
<!-- scope: periscope -->
<!-- info: Select **all applicable** industry types to which the publishing
organizations belong: -->
- Academic - Education
- Not-for-profit - Education, government

#### Contact Detail(s)
<!-- scope: microscope -->
<!-- info: Provide publisher contact details: -->
- **Mailing List:** microdados.daeb@inep.gov.br
- **Website:** https://www.gov.br/inep

### Dataset Owners
#### Team(s)
<!-- scope: telescope -->
<!-- info: Provide the names of the groups or team(s) that own the dataset: -->
National Institute of Educational Studies and Research Anisio Teixeira (INEP)

#### Contact Detail(s)
<!-- scope: periscope -->
<!-- info: Provide pathways to contact dataset owners: -->
- **Dataset Owner(s):** National Institute of Educational Studies and Research Anisio Teixeira (INEP)
- **Affiliation:** Ministry of Education - Brazil
- **Website:** https://www.gov.br/inep

## Dataset Overview
#### Data Subject(s)
<!-- scope: telescope -->
<!-- info: Select ***all applicable**** subjects contained the dataset: -->
- Data about Brazilian schools
- Data about Brazilian students

#### Dataset Snapshot
<!-- scope: periscope -->
<!-- info: Provide a snapshot of the dataset:<br><br>(Use the additional notes
to include relevant information, considerations, and links to table(s) with
more detailed breakdowns.) -->
Category | Data
--- | ---
Size of Dataset | 123456 MB
Number of Instances | 123456
Number of Fields | 123456
Labeled Classes | 123456
Number of Labels | 123456789
Average Labeles Per Instance | 123456
Algorithmic Labels | 123456789
Human Labels | 123456789
Other Characteristics | 123456

**Above:** Summary statitics of dataset.    

**Additional Notes:** Add here.

#### Content Description
<!-- scope: microscope -->
<!-- info: Provide a short description of the content in a data point: -->
Contains information information of Brazilian schools in 2019: the average result of students of the last year of basic education in a test of portuguese and math, information about the school and a questionnarie answered by the school principal. 


#### Descriptive Statistics
<!-- width: full -->
<!-- info: Provide basic descriptive statistics for each field.

Use additional notes to capture any other relevant information or
considerations.

Usage Note: Some statistics will be relevant for numeric data, for not for
strings. -->

Statistic | Field Name | Field Name | Field Name | Field Name | Field Name | Field Name
--- | --- | --- | --- | --- | --- | ---
count |
mean |
std |
min |
25% |
50% |
75% |
max |
mode |

**Above:** Provide a caption for the above table or visualization.

**Additional Notes:** Add here.

### Sensitivity of Data
#### Sensitivity Type(s)
<!-- scope: telescope -->
<!-- info: Select ***all applicable*** data types present in the dataset: -->
- Employee Data
- Pseudonymous Data
- Children’s Data

#### Field(s) with Sensitive Data
<!-- scope: periscope -->
<!-- info: List fields in the dataset that contain S/PII, and specify if their
collection was intentional or unintentional.

Use additional notes to capture any other relevant information or
considerations. -->
**Intentional Collected Sensitive Data**

S/PII were collected as a part of the
dataset creation process. However, the available version
of the dataset already anonymized this information.

Field Name | Description
--- | ---
ID_ESCOLA | Identifier of school
ID_MUNICIPIO | Identifier of municipality

#### Security and Privacy Handling
<!-- scope: microscope -->
<!-- info: Summarize the measures or steps to handle sensitive data in this
dataset.

Use additional notes to capture any other relevant information or
considerations. -->

The identifier of school and municipality was masked with a
random code. This random code can be used to related between
different tables, despite that it is not possible to identify
the original school and municipality from this random code.

**Method:** Removal of sensitive identifiers and replacement with random codes

### Dataset Version and Maintenance
#### Maintenance Status
<!-- scope: telescope -->
<!-- info: Select **one:** -->

**Limited Maintenance** - The data will not be updated,
but technical issues might be addressed. Similar datasets will
be generated yearly.

#### Version Details
<!-- scope: periscope -->
<!-- info: Provide details about **this** version of the dataset: -->
**Current Version:** 3.0

**Last Updated:** 04/2023
