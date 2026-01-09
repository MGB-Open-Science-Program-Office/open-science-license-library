# MGB Open Source License 1.0 Best Practice Guide

The MGB Open Source License 1.0 (MGB 1.0) is a permissive license that was drafted to enable Open Source projects within highly regulated clinical-research spaace, such as within Mass General Brigham and other Academic Medical Centers. While the most popular permissive licenses (MIT and Apache 2.0) are quite similar to MGB OS 1.0, there are a number of key differences. 

# Use Cases

**For Researchers**

The National Institutes of Health (NIH) as well as many other entities providing research grants to Academic Medical Centers and their researchers promote the broad dissemination of research products including grant-funded and/or developed research software. Openly sharing research software, as well as source and object code, provides transparency, and also serves the key objectives of rigor and reproducibility as part of responsible conduct of research.  These objectives are consistent with existing NIH data sharing policies and guidance.
Making software and code “open” means sharing software and code in a way that allows researchers to use code, modify and redistribute it. This can be done by releasing software and code in an open-source format in an appropriate, unrestricted, publicly accessible repository with version control. Repositories allow the provisioning of additional metadata and provide search tools and finding aids can enhance the FAIR-ness of software.
The MGB OS License 1.0 (MGB 1.0) facilitates and encourages the reuse of the code by clarifying and documenting the terms of how the software can be used, modified, and redistributed by others, and for what purposes. The MGB OS License 1.0 also disclaims any liability for problems associated with the software after the code has been released to the public. 

**For Developers**

Like MIT and Apache, the MGB OS License 1.0 is easy to add to your code, letting you get your open source software out into the academic community immediately. Plus, for-profit companies and individuals are able to use your code in their commercial applications without licensing disruption, meaning you are able to get your project into the hands of large software companies, a common entry point into future commercial relationships.
Another major incentive is the clear clinical-research risk restrictions,  enabling developers who work within Academic Medical Centers alignment with AMC policies and restrictions. The well-defined terms of the license lay out exactly what one can and can’t do with the software, fostering confidence and clarity for users.

# Grant Overview

Open source licenses come in two varieties: Permissive and Copyleft. MGB OS 1.0 is in the permissive category so meaning that users can do (nearly) anything they want with the code, with a few articulated exceptions.
The license splits the open source code-based intellectual property into two groups of rights: Patent rights and Non – Patent rights. According to the open source definition, open source development must grant licensees freedom to use and distribute the software, which requires addressing patents alongside copyrights to truly enable unrestricted collaboration. This practice also prevents patent “trolls,” or aggressive litigation, ensuring that both the author and subsequent downstream users that they won't be sued for using the software they are utilizing. In an attempt to balance Mass General Brigham’s protectionist interest in its extensive patent portfolio with the proper downstream enablement of open source software, MGB 1.0 expressly limits licensed patents to contributor inventions that have elements (or “claims”) that overlap with (read: are embodied by) those of the licensed code.  Thus is a more narrowly tailored patent grant than the broader Apache 2.0 grant to “infringing” patent claims.  
MGB 1.0’s grants are also compatible with emerging ai innovation where open science research results in the open sharing of machine learning models and algorithms which span code and database components. The large majority of previously available open source licenses were not compatible with the distribution of ai model materials which exist outside of copyright licensing schemes. 

# Redistribution Requirements

Anyone who redistributes open source software licensed under MGB 1.0 must include the following in their copy of the code:
1.	All original copyright, patent, trademark, and attribution notices 
2.	A copy of the license itself
3.	A copy of the NOTICE file with attribution notes
4.	If applicable, a statement of any significant changes made to the original code

The fourth requirement above is a major differentiator between the MGB 1.0 and other permissive licenses which do not require repository searchable inclusion of author acknowledgment. 
Also of note is that the original code to  which the licensee adds improvements to is still (the license granted is irrevocable) covered by the MGB 1.0 license, hence the need to make sure that a copy of the original license follows along with any derivative works. This also connects to the obligation to identify the changes Licensees have made and introduced to the original version. This differentiation is needed, not only to understand which elements are covered by the original MGB 1.0 license but also to make sure that future users to identify any future improvements made by downstream licensees who retains full ownership and IP rights over their creation. Note:  These licensees (and the original author) are free to distribute additions in whichever way they desire, commercially or otherwise.

# Use Summary
MGB 1.0 explicitly describes what users are allowed to do with the licensed code. Under this license, users can:
1.	Use the code commercially: Anyone can include the licensed code in proprietary software that they then sell to customers.
2.	Alter the code: Developers are permitted to make modifications to the original code.
3.	Distribute any copies or modifications of the code: An individual or organization is allowed to copy and/or update the code, then make that version available to others (even commercially).
4.	Sublicense the code: A company can distribute their reworked version of the code under a stronger license.
5.	Place warranty:  While redistributing the code or modifications of the code thereof, an individual or organization may choose to offer, and charge a fee for, acceptance of support, warranty, indemnity, or other liability obligations and/or rights consistent with this License.

# Risk Management Summary
1.	No Implied Rights to related software:  Nothing in MGB 1.0  grants any third party or software even if necessary to use or distribute the Work licensed under this License. Licensees are responsible for obtaining and maintaining their own licenses, at its own cost and expense, to any such third-party rights.
2.	No Implied Warranties, No Representations, and No Liability for Any Damages: The Work licensed under MGB 1.0 is provided by licensor and contributors “as is”.
3.	No Trademark or Name License:  MGB 1.0 does not grant permission to use the trade names, trademarks, service marks, or product names of the Licensor (Mass General Brigham Incorporated in this case), except as required for reasonable and customary use in describing the origin of the Work and reproducing the content of the NOTICE file.
4.	Included Data; Personal Information. Although the Work licensed MGB 1.0 may include data, graphs, and / or model materials, You may have obligations to comply with laws and policies concerning personal data or patient health information, and MGB 1.0 does not excuse those legal obligations. 

# MGB OS License 1.0 vs other Permissive Licenses

**MGB OS License 1.0 vs. the MIT License**
•	MGB 1.0 requires users to state any significant changes they make to the original code. 
•	MGB 1.0 includes express risk management around Patents, personal information, 3rd Party Software Rights, TM / Name rights and the ability to re-release the code under a different License and Warranty.   
•	In MIT there is ambiguity about whether  non-explicit terms exist, there is none when it comes to the MGB 1.0. The language of the license makes the protection of Licensor and AMC IP clear

**MGB OS License 1.0 vs. the Apache 2.0 License**

 <img width="888" height="467" alt="image" src="https://github.com/user-attachments/assets/5d51dbe4-b69b-4e31-a38b-2e8a2be97bfe" />




**MGB OS License 1.0 vs. the BSD License**

Beyond MGB 1.0’s explicit risk mitigation language as previously described, it features clear definitions of critical terms (“Work,” “Contributor,” “Licensor,” etc.) unlike the BSD license, removing ambiguity.
