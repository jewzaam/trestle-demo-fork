---
x-trestle-set-params:
  au-8_prm_1:
    values:
sort-id: au-08
---

# au-8 - \[Audit and Accountability\] Time Stamps

## Control Statement

The information system:

- \[a.\] Uses internal system clocks to generate time stamps for audit records; and

- \[b.\] Records time stamps for audit records that can be mapped to Coordinated Universal Time (UTC) or Greenwich Mean Time (GMT) and meets {{ insert: param, au-8_prm_1 }}.

## Control Objective

Determine if:

- \[AU-8(a)\] the information system uses internal system clocks to generate time stamps for audit records;

- \[AU-8(b)\]

  - \[AU-8(b)[1]\] the information system records time stamps for audit records that can be mapped to Coordinated Universal Time (UTC) or Greenwich Mean Time (GMT);
  - \[AU-8(b)[2]\] the organization defines the granularity of time measurement to be met when recording time stamps for audit records; and
  - \[AU-8(b)[3]\] the organization records time stamps for audit records that meet the organization-defined granularity of time measurement.

## Control guidance

Time stamps generated by the information system include date and time. Time is commonly expressed in Coordinated Universal Time (UTC), a modern continuation of Greenwich Mean Time (GMT), or local time with an offset from UTC. Granularity of time measurements refers to the degree of synchronization between information system clocks and reference clocks, for example, clocks synchronizing within hundreds of milliseconds or within tens of milliseconds. Organizations may define different time granularities for different system components. Time service can also be critical to other security capabilities such as access control and identification and authentication, depending on the nature of the mechanisms used to support those capabilities.