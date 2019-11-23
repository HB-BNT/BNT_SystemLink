BNT_SystemLink extends the CSPP_Core package of the CS++-Project. 

It contains a derived classes of
- CSPP_ProcessVariables.lvlib:PVConnection.lvclass
- CSPP_PVMonitor.lvlib:CSPP_PVMonitor.lvclass

Refer to https://git.gsi.de/EE-LV/CSPP for CS++ project overview, details and documentation.

LabVIEW 2019 is the currently used development environment.

Related documents and information
=================================
- README.md
- EUPL v.1.1 - Lizenz.pdf
- Contact: Holger.Brand@BrandNewTechnologies.de
- Download, bug reports... : http://github.com/HB-BNT/BNT_SystemLink
- Documentation:
  - Refer to package folder

GIT Submodules
==============
This package can be used as submodule
- Packages\BNT_SystemLink:
  - BNT_SLTagConnection.lvlib
  - BNT_SLTagMonitor.lvlib
  - BNT_SLTools.lvlib

External Dependencies
---------------------
- CSPP_Core: https://git.gsi.de/EE-LV/CSPP/CSPP_Core
- LabVIEW SystemLink Interface

Getting started:
=================================
- Add BNT_SLContent.vi into your own LabVIEW project.
- Move lvlibs mentioned above from dependencies to your virtual folder structure.
- You need to extend your project specific ini-file.
  - A sample ini-file should be available on disk in the corresponding package folder.

Lizenziert unter EUPL V. 1.1 
  
Author: Holger.Brand@BrandNewTechnologies.de

Copyright 2019  Brand New Technologies

Dr. holger Brand, Asternweg 12a, 64291 Darmstadt, Germany

Lizenziert unter der EUPL, Version 1.1 oder - sobald diese von der Europäischen Kommission genehmigt wurden - Folgeversionen der EUPL ("Lizenz"); Sie dürfen dieses Werk ausschließlich gemäß dieser Lizenz nutzen.

Eine Kopie der Lizenz finden Sie hier: http://www.osor.eu/eupl

Sofern nicht durch anwendbare Rechtsvorschriften gefordert oder in schriftlicher Form vereinbart, wird die unter der Lizenz verbreitete Software "so wie sie ist", OHNE JEGLICHE GEWÄHRLEISTUNG ODER BEDINGUNGEN - ausdrücklich oder stillschweigend - verbreitet.

Die sprachspezifischen Genehmigungen und Beschränkungen unter der Lizenz sind dem Lizenztext zu entnehmen.