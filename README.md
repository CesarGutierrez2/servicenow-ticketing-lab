# servicenow-ticketing-lab

## Project Overview
A fully configured ServiceNow developer instance demonstrating 
real-world IT help desk operations including incident management, 
service catalog, SLA configuration, and user administration.

## Skills Demonstrated
- User administration and role-based access control
- Incident ticket lifecycle management
- Service catalog creation and configuration
- SLA definition and scheduling
- Group management and ticket routing
- Help desk workflow documentation

## Environment
- Platform: ServiceNow Developer Instance
- Release: Australia
- Access: Cloud-based Personal Developer Instance (PDI)

## Users and Roles Created
| User | Title | Role |
|---|---|---|
| John Smith | Help Desk Technician | itil |
| Michael Davis | IT Manager | itil, itil_manager |
| Sarah Johnson | Marketing Coordinator | End User |

## Incidents Created and Managed
| Incident | Priority | Status |
|---|---|---|
| Unable to access Outlook email | 3 - Moderate | Resolved |
| Laptop screen flickering | 2 - High | Open |
| SharePoint access request | 4 - Low | Open |

## Service Catalog Items
- Password Reset Request — fulfilled within 1 hour
- Software Installation Request — requires manager approval, 24 hour review

## SLA Definitions
| SLA | Type | Duration | Schedule |
|---|---|---|---|
| High Priority Response SLA | Response | 2 Hours | 24x7 |
| Moderate Priority Resolution SLA | Resolution | 8 Hours | 8x5 |

## Troubleshooting Notes
- Navigated UI differences in Australia release vs older ServiceNow versions
- Mapped updated SLA field terminology to correct configuration values

## Tools Used
- ServiceNow Developer Instance (Australia release)
- ServiceNow ITSM modules
