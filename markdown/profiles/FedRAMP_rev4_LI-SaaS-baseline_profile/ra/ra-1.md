---
x-trestle-global:
  profile-title: FedRAMP Rev 4 Tailored Low Impact Software as a Service (LI-SaaS)
    Baseline
x-trestle-set-params:
  ra-1_prm_1:
    values:
  ra-1_prm_2:
    values:
  ra-1_prm_3:
    values:
sort-id: ra-01
x-trestle-add-props:
  # Add or modify control properties here
  # Properties may be at the control or part level
  # Add control level properties like this:
  #   - name: ac1_new_prop
  #     value: new property value
  #
  # Add properties to a statement part like this, where "b." is the label of the target statement part
  #   - name: ac1_new_prop
  #     value: new property value
  #     smt-part: b.
  #
  - name: method
    value: ATTEST
---

# ra-1 - \[Risk Assessment\] Risk Assessment Policy and Procedures

## Control Statement

The organization:

- \[a.\] Develops, documents, and disseminates to {{ insert: param, ra-1_prm_1 }}:

  - \[1.\] A risk assessment policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
  - \[2.\] Procedures to facilitate the implementation of the risk assessment policy and associated risk assessment controls; and

- \[b.\] Reviews and updates the current:

  - \[1.\] Risk assessment policy {{ insert: param, ra-1_prm_2 }}; and
  - \[2.\] Risk assessment procedures {{ insert: param, ra-1_prm_3 }}.

## Control Objective

Determine if the organization:

- \[RA-1(a)\]

  - \[RA-1(a)(1)\]

    - \[RA-1(a)(1)[1]\] develops and documents a risk assessment policy that addresses:

      - \[RA-1(a)(1)[1][a]\] purpose;
      - \[RA-1(a)(1)[1][b]\] scope;
      - \[RA-1(a)(1)[1][c]\] roles;
      - \[RA-1(a)(1)[1][d]\] responsibilities;
      - \[RA-1(a)(1)[1][e]\] management commitment;
      - \[RA-1(a)(1)[1][f]\] coordination among organizational entities;
      - \[RA-1(a)(1)[1][g]\] compliance;

    - \[RA-1(a)(1)[2]\] defines personnel or roles to whom the risk assessment policy is to be disseminated;
    - \[RA-1(a)(1)[3]\] disseminates the risk assessment policy to organization-defined personnel or roles;

  - \[RA-1(a)(2)\]

    - \[RA-1(a)(2)[1]\] develops and documents procedures to facilitate the implementation of the risk assessment policy and associated risk assessment controls;
    - \[RA-1(a)(2)[2]\] defines personnel or roles to whom the procedures are to be disseminated;
    - \[RA-1(a)(2)[3]\] disseminates the procedures to organization-defined personnel or roles;

- \[RA-1(b)\]

  - \[RA-1(b)(1)\]

    - \[RA-1(b)(1)[1]\] defines the frequency to review and update the current risk assessment policy;
    - \[RA-1(b)(1)[2]\] reviews and updates the current risk assessment policy with the organization-defined frequency;

  - \[RA-1(b)(2)\]

    - \[RA-1(b)(2)[1]\] defines the frequency to review and update the current risk assessment procedures; and
    - \[RA-1(b)(2)[2]\] reviews and updates the current risk assessment procedures with the organization-defined frequency.

## Control guidance

This control addresses the establishment of policy and procedures for the effective implementation of selected security controls and control enhancements in the RA family. Policy and procedures reflect applicable federal laws, Executive Orders, directives, regulations, policies, standards, and guidance. Security program policies and procedures at the organization level may make the need for system-specific policies and procedures unnecessary. The policy can be included as part of the general information security policy for organizations or conversely, can be represented by multiple policies reflecting the complex nature of certain organizations. The procedures can be established for the security program in general and for particular information systems, if needed. The organizational risk management strategy is a key factor in establishing policy and procedures.

# Editable Content

<!-- Make additions and edits below -->
<!-- The above represents the contents of the control as received by the profile, prior to additions. -->
<!-- If the profile makes additions to the control, they will appear below. -->
<!-- The above markdown may not be edited but you may edit the content below, and/or introduce new additions to be made by the profile. -->
<!-- If there is a yaml header at the top, parameter values may be edited. Use --set-parameters to incorporate the changes during assembly. -->
<!-- The content here will then replace what is in the profile for this control, after running profile-assemble. -->
<!-- The added parts in the profile for this control are below.  You may edit them and/or add new ones. -->
<!-- Each addition must have a heading either of the form ## Control my_addition_name -->
<!-- or ## Part a. (where the a. refers to one of the control statement labels.) -->
<!-- "## Control" parts are new parts added after the statement part. -->
<!-- "## Part" parts are new parts added into the top-level statement part with that label. -->
<!-- Subparts may be added with nested hash levels of the form ### My Subpart Name -->
<!-- underneath the parent ## Control or ## Part being added -->
<!-- See https://ibm.github.io/compliance-trestle/tutorials/ssp_profile_catalog_authoring/ssp_profile_catalog_authoring for guidance. -->