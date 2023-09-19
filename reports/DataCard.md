# Basic Education Assessment System 2019 (SAEB)
Dataset with school assessment from Brazil performed in 2019. It contains the results of Portuguese and math tests of students from each school for different education levels (primary education, high school). It also has questionnaires about social and economic conditions answered by students, teachers, and the principal. Brazil's government collects the data in an initiative from INEP. This data is suited for analysis of school performance in Brazil.

#### Dataset Link
<!-- info: Provide a link to the dataset: -->
<!-- width: half -->
https://drive.google.com/file/d/1Q9jCNuTbw0PAa9lU474TGWziAie_B0IY/view?usp=sharing

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
- Not-for-profit - Education, Government

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
Size of Dataset | 26 MB
Number of Instances | 23940 
Number of Fields | 240
Score Fields | 2

**Above:** Summary statistics of dataset.    


#### Content Description
<!-- scope: microscope -->
<!-- info: Provide a short description of the content in a data point: -->
Contains information on Brazilian schools in 2019: the average result of students in the last year of basic education in a test of Portuguese and math, information about the school, and a questionnaire answered by the school principal. 


### Sensitivity of Data
#### Sensitivity Type(s)
<!-- scope: telescope -->
<!-- info: Select ***all applicable*** data types present in the dataset: -->
- Employee Data
- Pseudonymous Data
- Children's Data

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
random code. This random code can be used to relate between
different tables, although it is impossible to identify
the original school and municipality from this random code.

**Method:** Removal of sensitive identifiers and replacement with random codes


## Motivations & Intentions
### Motivations
#### Purpose(s)
<!-- scope: telescope -->
<!-- info: Select **one**: -->
- Monitoring
- Research

#### Domain(s) of Application
<!-- scope: periscope -->
<!-- info: Provide a list of key domains of application that the dataset has
been designed for:<br><br>(Usage Note: Use comma-separated keywords.) -->
`Data Analysis`, `Machine Learning`, `Regression`

#### Motivating Factor(s)
<!-- scope: microscope -->
<!-- info: List the primary motivations for creating or curating this dataset:

(Usage Note: use this to describe the problem space and corresponding
motivations for the dataset.) -->

- Analyzing patterns of basic education in Brazil
- Study Brazil school assessment (SAEB) with a socioeconomic point of view

### Intended Use
#### Dataset Use(s)
<!-- scope: telescope -->
<!-- info: Select **one**: -->
- Safe for research use

#### Suitable Use Case(s)
<!-- scope: periscope -->
<!-- info: Summarize known suitable and intended use cases of this dataset.

Use additional notes to capture any specific patterns that readers should
look out for, or other relevant information or considerations. -->
**Suitable Use Case:** Calculate statistical measures of correlation and dependence.

**Suitable Use Case:** Development of school score models based on school attributes.

#### Unsuitable Use Case(s)
<!-- scope: microscope -->
<!-- info: Summarize known unsuitable and unintended use cases of this dataset.

Use additional notes to capture any specific patterns that readers should look
out for, or other relevant information or considerations. -->
**Unsuitable Use Case:** Identify causal relations between bad school performance
and attributes from schools.

#### Research and Problem Space(s)
<!-- scope: periscope -->
<!-- info: Provide a description of the specific problem space that this
dataset intends to address. -->
Comprehend structural relations between the performance of students from a school in
math and Portuguese and the school infrastructures, as well as characteristics related to
location.


## Provenance
### Collection
#### Method(s) Used
<!-- scope: telescope -->
<!-- info: Select **all applicable** methods used to collect data: -->
- Survey, forms, or polls

#### Methodology Detail(s)
<!-- scope: periscope -->
<!-- info: Provide a description of each collection method used.

Use additional notes to capture any other relevant information or
considerations.

(Usage Note: Duplicate and complete the following for collection method
type.) -->
**Collection Type** Eletrochnic and physical surveys and tests applied in schools

**Source:** INEP technical note

**Is this source considered sensitive or high-risk?** No

**Dates of Collection:** 2019

**Primary modality of collection data:**

- Tabular Data

**Update Frequency for collected data:**

- Yearly

### Version and Maintenance

#### Cadence
<!-- scope: telescope -->
<!-- info: Select **one**: -->
- Yearly

#### Last and Next Update(s)
<!-- scope: periscope -->
<!-- info: Please describe the update schedule: -->
- **Date of last update:** 04/2023
- **Total data points affected:** All
- **Date of next update:** The Dataset of the following years will be published, but there is no planned update for the dataset
of SAEB 2019

#### Changes on Update(s)
<!-- scope: microscope -->
<!-- info: Summarize the changes that occur when the dataset is refreshed.

Use additional notes to capture any other relevant information or
considerations.

(Usage Note: Duplicate and complete the following for each source type.) -->
- **Source Type:** The SAEB 2019 dataset was updated to hide the identifier of
schools and municipalities, according to LGPD.

## Transformations
<!-- info: Fill this section if any transformations were applied in the
creation of your dataset. -->
### Synopsis
#### Transformation(s) Applied
<!-- scope: telescope -->
<!-- info: Select **all applicable** transformations
that were applied to the dataset. -->
- Cleaning Missing Values
- Joining Input Sources

### Breakdown of Transformations
<!-- info: Fill out relevant rows. -->
#### Cleaning Missing Value(s)
<!-- scope: telescope -->
<!-- info: Which fields in the data were missing
values? How many? -->
Many fields with missing values were cleaned. 

#### Cleaning Method
<!-- scope: periscope -->
Some missing fields were related to a hierarchy of questions.

Some missing fields related to the occurrence of activities at the school were replaced with no-occurrence.

Fields with more than 1% of nan values were removed.

The remaining rows with any missing values were removed.
 
#### Residual & Other Risk(s)
<!-- scope: microscope -->
<!-- info: What risks were introduced because of
this transformation? Which risks were
mitigated? -->
The missing values can be related to socioeconomic conditions of schools.
This need to be further evaluated by analyzing the differences of the distribution
of features.

#### Joining Input Sources
<!-- scope: telescope -->
<!-- info: What were the distinct input sources joined? -->
The result of schools was joined with the questionnaire of directors. 
Both tables were available at the SAEB 2019 dataset and shared a feature "ID_ESCOLA"
that can be joined.

**Schools performance:** 137 columns

**Principals survey:** 262 columns

#### Method(s) Used
<!-- scope: periscope -->
<!-- info: What are the shared field columns used to join these
sources? -->
Few schools had more than one principal, in this situation
only one as used. An inner join was performed based on the feature
"ID_ESCOLA".