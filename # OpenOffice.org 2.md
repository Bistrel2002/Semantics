# OpenOffice.org 2.4

![OpenOffice.org Logo](https://www.openoffice.org/images/AOO_logos/OOo_Website_v2_copy.png)


## Table of Contents

- [Overview](#overview)
- [System Requirements](#system-requirements)
- [Installation Guide](#installation-guide)
- [Known Issues](#known-issues)
- [Support](#support)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Overview

OpenOffice.org is a free and open-source office productivity suite that provides a complete set of applications for document processing, spreadsheets, presentations, and more. This version (2.4) is designed to be accessible to all users, including government, business, educational, and private users.

## System Requirements

### Minimum Requirements
- **Operating System:** Windows 98, ME, NT (Service Pack 6 or later), 2000, or XP
- **Processor:** Pentium-compatible PC
- **Memory:** 64 MB RAM
- **Storage:** 
  - 250 MB free disk space (300 MB for CJK version)
  - 500 MB additional space needed during installation
- **Display:** 
  - Minimum resolution: 800x600
  - Color depth: 256 colors minimum

## Installation Guide

### Pre-installation Steps
1. Close all other applications
2. Ensure sufficient free space in your temporary directory
3. Verify you have read, write, and execute permissions
4. **Note:** Administrator rights are required for installation

### Special Considerations
- **Windows 98 Users:** If installing Java, ignore the reboot prompt or restart the installer after rebooting
- **Previous Versions:** You can install version 2.4 alongside older versions
  - To remove older versions later, run the 2.4 installer and select 'Repair'

## Known Issues

### Graphics and Display
- Display issues may be resolved by updating graphics card drivers
- For 3D rendering problems:
  1. Go to 'Tools - Options - OpenOffice.org - View - 3D view'
  2. Disable 'Use OpenGL'

### Touchpad Scrolling (Windows)
For ALPS/Synaptics touchpads, add the following to `C:\Program Files\Synaptics\SynTP\SynTPEnh.ini`:
```ini
[OpenOffice.org]
FC = "SALFRAME"
SF = 0x10000000
SF |= 0x00004000
```

**Note:** The location of the configuration file might vary on different versions of Windows.

### ZoomText Compatibility
- Requires ZoomText version 7.11 or higher
- Only ZoomText versions downloaded after June 12, 2002, provide the required functionality
- Compatible with OpenOffice.org 2.4

### Email Integration
- Document email functionality may experience issues due to Windows MAPI
- For troubleshooting, visit [Microsoft Knowledge Base and search](http://www.microsoft.com) for "mapi dll"

### Keyboard Shortcuts
- Conflicts with system shortcuts may occur
- Shortcuts can be customized through Tools > Options

### Product Registration
- Optional but highly encouraged
- Helps improve the software suite
- Assists in meeting user needs directly
- Protected by strict privacy policy
- Register during installation or later at [OpenOffice.org Registration](www.openoffice.org/welcome/registration-site.html)

### User Survey
- Online survey available for user feedback
- Helps define higher standards for future releases
- Guides the development of next-generation office suite features
- All responses protected by OpenOffice.org privacy policy
- Your input directly influences product development

## Support

### Community Resources
- **User Forum:** discuss@openoffice.org
- **Documentation:** [OpenOffice.org Documentation](http://www.openoffice.org)
- **FAQ:** [User FAQ](http://user-faq.openoffice.org/)

### Bug Reporting
Report issues through IssueZilla on the OpenOffice.org website to help improve the software.

## Contributing

### Ways to Contribute
1. **Join Mailing Lists:**
   - News: announce@openoffice.org (recommended)
   - User Forum: discuss@openoffice.org
   - Marketing: dev@marketing.openoffice.org
   - Development: dev@openoffice.org

2. **Project Participation:**
   - Documentation
   - Marketing
   - Localization
   - Development
   - Quality Assurance

Join the Marketing Communications & Information Network here: [Marketing Team Contacts](http://marketing.openoffice.org/contacts.html)

Visit [OpenOffice.org Projects](http://projects.openoffice.org/index.html) for more information.

## License

OpenOffice.org is free for all users under the terms specified at [OpenOffice.org License](http://www.openoffice.org/license.html).



OpenOffice.org is licensed under the GNU Lesser General Public License (LGPL-3.0) and Mozilla Public License (MPL).

- ![LGPL-3.0 License](https://img.shields.io/badge/License-LGPL_3.0-blue.svg) ([LGPL-3.0](https://www.gnu.org/licenses/lgpl-3.0.html))
- ![MPL License](https://img.shields.io/badge/License-MPL_2.0-brightgreen.svg) ([Mozilla Public License](https://www.mozilla.org/en-US/MPL/2.0/))
- ![OpenOffice License](https://img.shields.io/badge/license-OpenOffice.org-orange) ([OpenOffice.org License](https://www.openoffice.org/license.html))


## Acknowledgments

- Portions Copyright 1998, 1999 James Clark
- Portions Copyright 1996, 1998 Netscape Communications Corporation

---

*For the latest updates to this readme, visit [OpenOffice.org Welcome Page](http://www.openoffice.org/welcome/readme.html)*