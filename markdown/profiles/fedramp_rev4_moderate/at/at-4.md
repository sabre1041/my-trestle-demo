---
x-trestle-global:
  profile:
    title: FedRAMP Rev 4 Moderate Baseline
  sort-id: at-04
x-trestle-set-params:
  # You may set values for parameters in the assembled Profile by adding
  #
  # profile-values:
  #   - value 1
  #   - value 2
  #
  # below a section of values:
  # The values list refers to the values in the catalog, and the profile-values represent values
  # in SetParameters of the Profile.
  #
  at-4_prm_1:
    profile-values:
    values:
sort-id: at-04
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
  - name: CORE
    value: 'true'
    ns: https://fedramp.gov/ns/oscal
    smt-part: at-4
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: at-4.a_obj.1
  - name: method
    value: EXAMINE
    smt-part: at-4.a_obj.1
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: at-4.a_obj.2
  - name: method
    value: INTERVIEW
    smt-part: at-4.a_obj.2
  - name: method
    value: TEST
    smt-part: at-4.a_obj.2
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: at-4.b_obj.1
  - name: method
    value: EXAMINE
    smt-part: at-4.b_obj.1
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: at-4.b_obj.2
  - name: method
    value: INTERVIEW
    smt-part: at-4.b_obj.2
  - name: method
    value: TEST
    smt-part: at-4.b_obj.2
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: a.
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: b.
---

# at-4 - \[Awareness and Training\] Security Training Records

## Control Statement

The organization:

- \[a.\] Documents and monitors individual information system security training activities including basic security awareness training and specific information system security training; and

- \[b.\] Retains individual training records for {{ insert: param, at-4_prm_1 }}.

## Control Objective

Determine if the organization:

- \[AT-4(a)\]

  - \[AT-4(a)[1]\] documents individual information system security training activities including:

    - \[AT-4(a)[1][a]\] basic security awareness training;
    - \[AT-4(a)[1][b]\] specific role-based information system security training;

  - \[AT-4(a)[2]\] monitors individual information system security training activities including:

    - \[AT-4(a)[2][a]\] basic security awareness training;
    - \[AT-4(a)[2][b]\] specific role-based information system security training;

- \[AT-4(b)\]

  - \[AT-4(b)[1]\] defines a time period to retain individual training records; and
  - \[AT-4(b)[2]\] retains individual training records for the organization-defined time period.

## Control guidance

Documentation for specialized training may be maintained by individual supervisors at the option of the organization.

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