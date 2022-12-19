============================================================================================================
START readme
============================================================================================================
[WUR Template README file for archiving data. This template is focused on raw data, that cannot be 
published due to legitimate reasons (e.g. personal data), to be archived at WUR (for example Yoda or W 
drive). This file is written and formatted in Notepad++ in the normal text language on Windows 10. 
The provided guidance between '[..]' must be removed when the README file is filled in (including this text). 
Please keep line length in between the ===== line (just press enter to continue on a new line).]

Terms within this file can be based on
- the DataCite Metadata Scheme 4.4 (https://schema.datacite.org/), indicated with 'DC' in front of the 
  term in the header,
- the Yoda metadata scheme (https://yoda.uu.nl/schemas/default-1/metadata.json), indicated with 'YD' in 
  front of the term in the header, 
- or are required data management information, indicated with 'DM' in front of the term in the header. 
If no letter indicators are present in the headers, then they are general terms. 

============================================================================================================
## General
============================================================================================================
## Author(s): 		[Author(s) of this metadata file]
## Project: 		[Project that this metadata file concerns]
## University:  	Wageningen University and Research [+ other institutes if present]
## Department(s): 	[department(s) where this project was performed]
## Contact: 		[Contact of author(s) of this metadata file] 
## Version:		[version of the data]
## Language: 		[language of the data]


============================================================================================================
## DC Title
============================================================================================================
[Provide a title that reflects the content of the data. If the title of the data is the 
same as the title of the accompanying publication(s), add 'Data from: ' or 
'Data underlying the publication(s):'.] 


============================================================================================================
## DC Description 
============================================================================================================
descriptionType = "Methods"

[Description on how the data was attained or which settings were used on machines to attain the 
data This should also include what processing of data took place to attain the files (if any processing of 
data was performed).]

============================================================================================================
## YD Affiliation
============================================================================================================
[Provide the identifier of the affiliation(s) given under 'General'

Example 

affilliationIdentifier: 
	affiliationIdentifierScheme = "ROR" https://ror.org/04qw24q55

] 

============================================================================================================
## DM Folder
============================================================================================================
[Explanation folder structure]

- Parent folder name
	-- subfolder name
	-- subfolder name
		--- sub-subfolder name
	-- subfolder name
etc.........


============================================================================================================
## DM FolderContents
============================================================================================================
[What data / files can be found where and how should data be used and what is the purpose of the 
data]


============================================================================================================
## DM SoftwareRequired
============================================================================================================
[Is there specific software required to open files > name software, version, company]


============================================================================================================
## DM Formats
============================================================================================================
[What type of file formats does the data contain]


============================================================================================================
## DM Codebook
============================================================================================================
[List of used abbreviations and/or codes + explanation used in files, columns, and in filenames]

## Abbreviations/codes + explanation used
[what do the abbreviations / code / data mean, where is the abbreviation or code used, what do column names 
mean, what do the columns / data represent, what is the unit of measurement]
[
Example:

Name: ELISA 
Used in: columns, filenames, foldernames 
Meaning: laboratory assay
Represents: relative titers of natural antibody within plasma obtained from pigs 

Name: sex 
Used in: columns 
Meaning: gender of animal
Represents: m = male pig (boar); f = female pig (sow)

Name: bodyweight
Used in: columns 
Meaning: bodyweight of pigs
Represents: body weight of pigs in kg with one decimal
]


============================================================================================================
[Add any other information required for people to understand and use the data.]
============================================================================================================


============================================================================================================
END readme
============================================================================================================
