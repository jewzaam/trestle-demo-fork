---
x-trestle-set-params:
  ac-6.2_prm_1:
    values:
sort-id: ac-06.02
---

# ac-6.2 - \[Access Control\] Non-privileged Access for Nonsecurity Functions

## Control Statement

The organization requires that users of information system accounts, or roles, with access to {{ insert: param, ac-6.2_prm_1 }}, use non-privileged accounts or roles, when accessing nonsecurity functions.

- \[2_fr\]

## Control Objective

Determine if the organization:

- \[AC-6(2)[1]\] defines security functions or security-relevant information to which users of information system accounts, or roles, have access; and

- \[AC-6(2)[2]\] requires that users of information system accounts, or roles, with access to organization-defined security functions or security-relevant information, use non-privileged accounts, or roles, when accessing nonsecurity functions.

## Control guidance

Examples of security functions include but are not limited to: establishing system accounts, configuring access authorizations (i.e., permissions, privileges), setting events to be audited, and setting intrusion detection parameters, system programming, system and security administration, other privileged functions.
This control enhancement limits exposure when operating from within privileged accounts or roles. The inclusion of roles addresses situations where organizations implement access control policies such as role-based access control and where a change of role provides the same degree of assurance in the change of access authorizations for both the user and all processes acting on behalf of the user as would be provided by a change between a privileged and non-privileged account.