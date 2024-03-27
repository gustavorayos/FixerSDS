# FixerSDS
FixerSDS (Standard Deployment Script) is a System Administration and Cyber Security tool used to harden Linux systems to NIST security standards. It's written in Bash and also includes other configurations options such as SCAP and STIGViewer install, log collection, antivirus install, luks and clevis configuration, etc. 

## Getting Started

FixerSDS is written in Bash and is meant to be run with an additional flag option. For example ./FixerSDS.sh -full-config 

### Prerequisites

1) Linux "EL7" system
2) Admin privileges on system

### Installing

FixerSDS can be run locally on from a network location. Just copy the entire directory to where you want to run it from. 

## Built With

* [Sublime](https://www.sublimetext.com/) - Text editor
* [Windows Hyper-V](https://www.microsoft.com/en-us/) - VM test environment
* [DISA](https://www.disa.mil/) - Used to configure computer system with STIG standards
* [SCAP](https://public.cyber.mil/stigs/scap/) - Automated vulnerability scanner
* [STIGViewer](https://public.cyber.mil/stigs/srg-stig-tools/) - System vulnerability checklist/viewer

## Authors

* **Gustavo Rayos** - *Initial work* - [gustavorayos.com](https://www.gustavorayos.com)

## Acknowledgments

* Hat tip to developers and posters on forums (Stack Overflow, Reddit, YouTube, etc)
* Inspiration

## Screenshots

User Interface

![Fixer_SDS_Screenshot](https://github.com/gustavorayos/FixerSDS/assets/8792052/e5e4fbbc-be0c-4411-899f-30effed77bc3)

Before running FixerSDS SCAP score 

![RHEL-PreSTIG-SCAP](https://github.com/gustavorayos/FixerSDS/assets/8792052/978c0b32-074f-488b-9f25-7ec9c5f90176)

After running FixerSDS SCAP score

![RHEL-PostSTIG-SCAP](https://github.com/gustavorayos/FixerSDS/assets/8792052/a45410ba-f24a-4bfd-802f-6c7d71e693ff)

