# UK House of Commons: Ten-Minute Rule Speeches

A dataset of ten-minute rule speeches delivered in the UK House of Commons, covering multiple parliamentary sessions. Each row represents one speech made by a Member of Parliament (MP) when seeking leave to introduce a private member's bill under Standing Order No. 23 (First Reading).

## File

`tmr\_speeches.csv`

## Columns

|Column|Description|
|-|-|
|`bill\_short\_title`|Short title of the proposed bill|
|`originating\_session`|Parliamentary session in which the First Reading speech was delivered (e.g. `54/2` = 54th Parliament, 2nd Session)|
|`bill\_page\_url`|URL of the bill's page on parliament.uk|
|`date`|Date of the speech (DD/MM/YYYY)|
|`member`|Name of the MP who delivered the speech|
|`Party`|Party affiliation of the MP at the time of the speech|
|`constituency`|Constituency represented by the MP|
|`speech\_text`|Full text of the First Reading speech as recorded in Hansard (opposition speeches not included)|
|`hansard\_url`|URL of the corresponding Hansard debate record|
|`notes`|Miscellaneous notes (e.g. missing speeches)|
|`gender`|Gender of MP presenting the bill|

## Coverage

* **Rows:** 1,072 speeches
* **Unique MPs:** 663
* **Gender breakdown:** 724 male speeches (67.5%), 348 female speeches (32.5%)
* **Sessions covered:** Multiple sessions from the 54th Parliament onwards (2006-2026)

## Source

Speech text and metadata were originally sourced from the UK Parliament's Hansard records. Bill metadata is drawn from the bills.parliament.uk API.

* Hansard: https://hansard.parliament.uk
* Bills: https://bills.parliament.uk


