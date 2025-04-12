# nuclei_template
Personal collection of Nuclei custom templates.

List of my written Nuclei custom templates; some are HTTP-focused, others are TCP-focused.

Oriented around the ICS, PLC, and CPS monitoring world.

NOTE: the readme is categorisied by purpose (Honeypot detection , login page detection, etc..) but the template ar categorized by vendor (expect for the honeypot detections). 

- [PLC model / Series](#plc-model)
- [Honeypot_detection](#honeypot-detection)
- [Login_page_detection](#login-page-detection)
- [Monitoring_page](#monitoring-page)
- [Unprotected_panel](#unprotected-panel)
- [Default_password_detection](#default-password-detection)



# PLC model

| name                                         | purpose                                                                            |
|----------------------------------------------|------------------------------------------------------------------------------------|
| modicon_340_detect                           |  Detect Schneider Modicon 340 PLC via UMAS protocol                                                 |
| modicon_580_detect                           |  Detect Schneider Modicon 580 PLC via UMAS protocol                                                 |
| Red_Lion_detect                              |  Detect Red Lion  PLC via via ENIP protocol                                                             |
| Allan_Bredlley_CompactLogix_enip-cip_detect           |  Detect Allan Bredlley CompactLogix serie PLC via enip-cip protocol                                      |
| Allan_Bredlley_GuardPLC_enip-cip_detect               |  Detect Allan Bredlley GuardPLC serie PLC via enip-cip protocol                                         |
| Allan_Bredlley_Micro800_enip-cip_detect               |  Detect Allan Bredlley Micro800 serie PLC via enip-cip protocol                                         |
| Allan_Bredlley_MicroLogix_enip-cip_detect             |  Detect Allan Bredlley MicroLogix serie PLC via enip-cip protocol                                       |
| Allan_Bredlley_PLC-5_enip-cip_detect                  |  Detect Allan Bredlley PLC-5 serie PLC via enip-cip protocol                                            |
| Allan_Bredlley_SLC-500_enip-cip_detect                |  Detect Allan Bredlley SLC-500 serie PLC via enip-cip protocol                                          |


---

# Honeypot detection 

| name                                         | purpose                                                                           |
|----------------------------------------------|------------------------------------------------------------------------------------|
| Ethernet_IP_CIP_conpot_default_config        |  Compare the default configurations of a conpot honeypot based on the cpppo project |
| snap7_honeypot_default_config                |  Detect default config of snap7                                                       |

---


# Login page detection

| name                                         | purpose                                                                           |
|----------------------------------------------|-----------------------------------------------------------------------------------|
| ETIC_telecom_router_login_page               |                                                                                   |
| Siemens_LOGO_login_page                      |                                                                                  |
| SIEMENS_SIMATIC_HMI_Miniweb_panel            |                                                                                  |
| OSASI_login_page                             |                                                                                  |
| MOXA_vpn_router_login_page                   |                                                                                  | 

---

# monitoring page

| name                                         | purpose                                                                           |
|-----------------------------------------------|-----------------------------------------------------------------------------------|
| CAE_Monitoring_page                            | Found the monitoring page aof italian base CAE monitoring system (login page linked in the /cfg/ path)|
| WAGO_web_based_management_panel                | Find default management view of the WAGO  Web based Management            |


---

# Unprotected panel

| name                                          | purpose                                                                           |
|------------------------------------------------|-----------------------------------------------------------------------------------|
| ETIC_telecom_unprotected_admin_panel          |                                                                                   |

---


# Default password detection

| name                                         | purpose                                                                           |
|-----------------------------------------------|-----------------------------------------------------------------------------------|
| LOYETC_PLC_default_password                   | Detect default password on the LOYTEC PLC family                                 |
| SIEMENS_SIMATIC_HMI_Miniweb_default_password  | Detect default password on the SIEMENS SIMATIC Miniweb server                     |
| OSASI_default_credential                      |
| WAGO_default_password_web_panel               | Detect default password on the  Web based Management page                        |

---