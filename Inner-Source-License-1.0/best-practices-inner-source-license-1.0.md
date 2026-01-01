# MGB Inner Source License 1.0 Best Practice Guide 

**tldr:**

The Mass General Brigham (“MGB”) Digital Research Operations Data Concierge Team presented Digital Business Development - Innovation (“Digital BD”) with a request for a GitLab compatible software license in support of MGB Snowflake Enterprise Data Warehouse enabled researchers to improve collaboration and increase development support speed and quality. These repository use cases for “open source like” internal distribution of SQL Epic queries presented an opportunity for Digital BD to create a MGB Inner Source License that aligned with the MGB Open Science Program Office (“MGB OSPO”) policies currently under development. The attached license is suitable for freely distributing software across the system through a GitLab repository, addressing several MGB privacy and confidentiality constraints. Please contact OpenScience@Mgb.org with any use case questions or concerns or to be added to the OSPO Mailing List.

# Background:	

**What is Inner Source?**

"Inner Source" describes the process of applying open source principles to software development within MGB without publishing the program code outside the company. This allows the benefits of open source development models to be realized without making the development public.
Inner source can thus lead to improved collaboration, increased development speed and quality, and contribute to reducing costs. This is particularly successful in situations where different parts of MGB require software components with similar requirements, for example, internal standard libraries, infrastructure components, or development, testing, and deployment tools.

**Why a new software license?**

Within some single entity organizations, inner source is a new form of collaboration and does not require special contracts or software licenses, as all authors and users of a software belong to the same company. In a matrix Academic Medical Center context, further challenges arise from the collaboration between the various subsidiaries. The transfer of source code or binary packages between different companies—even within the same group—requires contractual arrangements and must be mindful of the compliance environment with in the hospital system. 
The MGB Inner Source License resolves contractual issues and creates a legally secure framework for collaboration between MGB;s Academical Medical Centers, Community Hospitals, Labs, and corporate digital teams. Thus, MGB ISL makes a concrete contribution to holistic optimization for MGB.
Since traditional open source licenses only assume a donation of the software and aim to enable and promote the maximum public distribution of the software worldwide, they are not applicable to collaboration based on open source principles across MGB, where for example, the public distribution of Epic intellectual property or personal health data is prohibited. The new MGB ISL license bridges these worlds and provides a legal framework for open source collaboration within MGB.

**What is the MGB Inner Source License?**

The MGB Inner Source License (MGB ISL) is a software license under which software can be freely used and developed within MGB, and the source code is available to all software developers within MGB. It thus enables research and collaborative development utilizing well-known open source models within the MGB without the risk of these becoming public.
The MGB ISL is based on a so-called "copyleft" type license, which not only ensures that source code is available and can be used freely, but also that modifications and further developments must be made available under the same conditions so that the greatest possible benefit can be derived from the shared and developed code.
The license is available as an option for internal software development and can also be used in connection with orders and contracts between different parts of the MGB organization.
In addition to the legal framework for sharing code within an open-source-like development model, the MGB ISL also provides the basis for adapting elements of open-source culture where they can help improve communication and collaboration and make processes more efficient, transparent, and self-organized.

**Rights and obligations of the MGB Inner Source License**

The MGB ISL maps rights and obligations known from open source licenses to the scenario of intra-system development.
It is important to note that the resulting rights and freedoms are always limited to use and disclosure within the system. Any disclosure to parties outside the system  requires an explicit relicensing agreement, which must be obtained from the relevant rights holders. Please contact OpenScience@mgb.org for all relicensing support requests.

**Software licensed under the MGB ISL fulfills the four freedoms of open source software within the system:**

1.	The software can be used without restrictions within the system
2.	The source code of the software is available to all users
3.	Users can modify the software independently to make adjustments and improvements
4.	Modified versions of the software may be distributed to others

The exercise of these freedoms is based solely on the license. No license fees or other additional agreements are necessary.

MGB ISL’s primary obligation is to make the source code of the software licensed under MGB ISL available to all recipients of the software. This includes the original code and any modifications made to the code.
This obligation cannot be restricted and thus extends from one recipient of the software to the next. This ensures that the effort invested in developing the software is available to the broadest possible audience. Any further developments thus also benefit all other users of the software, in the interest of optimizing MGB’s systematic approach. .
The MGB ISL generally allows so-called "forks," i.e., development branches of the software that are continued independently of the original branch. However, this should only be necessary in well-articulated use cases. In any case, it is advisable to develop jointly on a branch and make changes to the main branch or at least merge them back promptly. This avoids the effort required for parallel development, leads to optimal value creation by pooling development resources, and ensures that the software can be sustainably maintained.

# Application scenarios

The use of MGB ISL is always advisable when sensitive code, machine learning materials, or data is to be made available to a broad audience within MGB in the easiest possible way and when collaboration on these elements is to be enabled and encouraged.

**In principle, the inner-source model can be used for a variety of use cases. It is particularly suitable for the following cases:**

•	Infrastructure and tools that are similar for many projects and usually do not represent the core clinical or research purposes of an application.
•	Reference implementations that are intended to be as easy as possible to make available to the largest possible internal audience.
•	Implementation of standards that help to establish generally applicable MGB internal standards. 

The MGB ISL is not suitable for code developed with the intent of commercialization, nor for software intended for open access publication and other distribution models to recipients outside of MGB. Depending on the use case, traditional proprietary or open source licenses are suitable.

**How is the MGB Inner Source License applied?**

An important principle in the application of MGB ISL is that existing license and copyright notices may not be removed but must be retained in their entirety when distributing or modifying the software. This ensures clarity regarding the license and rights holders of all parts of the code.
The license text is stored in a file named "LICENSE" (possibly with a file extension such as .TXT or .MD) in the root directory of the code repository. This file must always be included when distributing the software, whether in source code or binary form.
If the software is distributed in binary form, it must contain effective instructions on how the recipient can obtain the source code from which the binary form was generated.

Ideally, all code developed under the MGB ISL will be managed in a version control system that is equally accessible to everyone to make code usage and collaboration as effective as possible such as GitLab.

Each source code file must contain a reference to the license and the owner of the exploitation rights at the beginning.

Example:

// Copyright 2026 Mass General Brigham, Inc.
// Licensed under the MGB ISL 10.

If changes are made to a file by a copyright holder who is not already listed in the copyright notice, that new copyright holder adds an additional copyright line.
The years mentioned in the copyright notice should correspond to the years in which changes were made by the respective rights holder. This can also be a list or a range of years, for example, "2025, 2026" or "2025-2026.”
