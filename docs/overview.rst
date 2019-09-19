Introduction
=============================

The  AGS Format  has  now  been  accepted  by  many  in  ground  engineering  as  being  appropriate  to electronic  data  transfer  and  storage.  Prior  to  this  there  was  a  proliferation  of  software  systems  and associated data formats that differed both in form and purpose even though much of their content was common. This was recognised by the Association of Geotechnical and Geoenvironmental Specialists (AGS) in 1991 and led to the setting up of a Working Party to establish an interchange format which allowed  transfer  of  data  between  systems  with  minimal  change  to  the  systems  themselves.  The outcome of this work was embodied in the First Edition of this document published in 1992. The Second and  Third  Editions,  published  in  1994  and  1999  respectively,  contained  a  series  of  updates and developments reflecting the ongoing needs of the industry.

The  producers  of  geotechnical  and  geoenvironmental  data  have  adopted  systems  for  the  efficient preparation and presentation of reports in printed format and the receivers for its analysis. Clearly, the transfer of data by electronic means to the receiver’s systems, without the need for a printed interface, helps to minimise costs, time and the potential for error. It also encourages more and better use of the data. However, much remains to be done to encourage the use of data in the electronic format and the ongoing development of the AGS Format seeks to encourage its use not only in ground investigation but also in the design, bidding and construction phases of the project.

The capability of ageotechnical and geoenvironmental data system to accept or produce AGS Format data allows the data system operator to continue to use their own individual and bespoke processes and  working  methods,  such  as  familiar  data  capture  or  processing  forms,  without  compromising  the ability to exchange data with clients, partners or suppliers.  This aids the implementation and continual improvement of quality assurance procedures within data producers and receivers. Storage and access to  the  data  is  rendered  far  more  efficient  and  the  format  also  facilitates  the  establishment  of  data archives by producers, receivers and national bodies.

This document describes an update of the AGS Format and continues the trend of updating the Format in  response  to  industry  requirements.  The  AGS4  rules  have  been  revised  and  the  Data  Dictionary extensively updated to extend the range of data that can be transferred and reflect the requirements of the implementation of Eurocodes, accreditation and quality assurance. The changes also extend the functionality of the AGS Format to encompass the data processes prior to reporting; for example, new data groups allow transmittal of laboratory schedule requirements.

Scope
==============================

The  transmission  by  electronic  means  of  data  recorded  during  ground  investigations  and  ground engineering construction related activities is a realistic objective. The AGS Format allows for transfer of data  presented  on  forms  such  as  exploratory  hole  records  (e.g.  boreholes  and  trial  pits),  in  situ  test data, laboratory test results including geoenvironmental testing and monitoring.  

The transmission of report texts (introductory text, summaries, discussions and interpretations) is not within this scope. The transfer is limited to data without typographic or rendering information, such as font, underline or paragraph format. Typically these documents would be transmitted in standard file formats  such  as  Adobe  Portable  Document  Format  (PDF)  which  retain  thepublished  format  of  the documents.  Similarly,  the  format  of  the  transmission  of  drawings  and  photographs,  if  required,  is covered  by  other  standards.  AGS4,  however,  includes  the  transmittal  of  these  documents  within  an AGS  submission  using  the  FILE  Group,such  that  reports,  drawings  and  photographs  may  also  be transferred in a coordinated manner by electronic means.

User Support
==============

The AGS has made provision on its website (www.ags.org.uk) for:

- Downloading of this document
- Provision of standard abbreviations
- Guidance documents
- Example files
- Discussion boards

These resources aim to provide users with the appropriate materials to support implementation and use of  the  AGS  Format.  The  discussion  boards  assist  in  identification  of  user  needs  and  support  the development of the format to meet industry requirements.  The website is also used to communicate amendments to registered users.

Appendix 1 provides further information on the services provided to AGS Format users via the website.

Internal Preliminary and Final Data
====================================

The precise use of AGS Format data files within the project process and data management activities is not pre-determined. The data files are structured in order to allow the presentation of preliminary data as well as its updating during the course of a project, prior to issue of the final data.

AGS4  includes  new  Groups  relating  to  the  transmittal  of  laboratory  testing  requirements;  these  data form part of the project process and do not form part of the final data report.

Preliminary data in electronic format can be useful on major projects where design is undertaken during the period of the investigation. However, the need for this facility should be very carefully considered by the receivers before including it in their Contract Specifications since it will require the imposition of rigorous management procedures. The highlighting of change in data is considered to pose significant difficulties and hence preliminary data should be replaced by subsequent data and not merely updated by it.  Where the highlighting of change is required, this should be a facility incorporated in the receiver’s software. This does not preclude submission of parts of the data on separate media but the producer must ensure that the data within all separate issues are compatible and that updates are carried through all sub-sets of the data.

Each  issue  shall  be  given  a  unique  issue  sequence reference.    AGS4  includes  the  new  transmittal group,  TRAN,  to  manage  this  process  and  include  information  about  the  data  transfer  within  the transferred file.

Clear  labelling  of  files  and  media  and  conventions  for  its  security  and  management  are  vital  to  the implementation of a practical system. These aspects are dealt with in Appendix 2.  

Management
=============

In order to provide a framework, within which the data can be used, it is necessary to have specifications that fall into the following categories:

- National Specification
- General Specification
- Particular Specification

The  National  Specification in the UK, the ‘UK Specification for Ground Investigation’1,  includes  the general requirement for data in electronic format. To fully specify the data deliverable requirements, the General clauses for a contract may re-iterate these points and typically Particular Specification clauses should be presented to fully define the data format and deliverable requirements. AGS4 includes many headings  for  which  data  can  be  collected  during  a  geotechnical  or  geoenvironmental  investigation. 

However,  the  actual  data  transferred  from  the  producer  to  the  receiver  is  described  in  the  particular CONTRACT SPECIFICATIONbetween the two parties.

The more precise the information presented in the Particular Specification, the more likely that the data deliverable providedby the supplier will meet expectations. Notes on the approach to development of Particular Specification clauses are presented in a Guidance Document published on the AGS Format website.

AGS4 provides the facility to include user defined groups and headings for specific data requirements. It is important to note that adding additional headings can be very disruptive to producer’s internal processes and may result in considerable extra cost.  The specification of additional or user defined fields, therefore, should only be done if absolutely necessary. 

Updating
===========

To  meet  the  rapidly  changing  needs  of  its  users  the  AGS  Format  must  continue  to  develop.  The publication of a First Edition (1992) and a Second Edition (1994), were in hard copy forms. However, the broadening of the user base has required greater flexibility for dissemination of amendments.  The AGS  website  has  been  used  since  the  Third  Edition  (2004)  to  publish  subsequent  updates.    Whilst placing  the  Format  in  open  access  on  the  website  permits  more  frequent  updates,  all  changes  are subject to rigorous control and notification procedures.

Extensions to the AGS Format will continue to be necessary from time to time and details aregiven in Appendix 1 of how updates are notified to the user community. 

Any  problems  in  the  use  of  this  document  should  be  brought  to  the  attention  of  the  AGS  via  the discussion  board  on  the  website.    Problems  with  proprietary  software  should  be  directedto  the suppliers.


International Use of the AGS Format
====================================

The  requirements  for  other  countries  to  adopt  and  use  the  AGS  Format  as  a  national  data  transfer standard are defined in a Guidance Document on the AGS website. The documentation includes the approach to be followed that permits implementation of the AGS Format for transfer in accordance with the technical standards of that country.
