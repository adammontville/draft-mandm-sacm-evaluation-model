---
title: Endpoint Attribute Evaluation Model
abbrev: Evaluation Model
docname: draft-mandm-sacm-evaluation-model-latest
stand_alone: true
ipr: trust200902
area: Security
wg: SACM Working Group
kw: Internet-Draft
cat: info
coding: us-ascii
pi:
  toc: yes
  sortrefs: yes
  symrefs: yes

  author:
  - ins: A. Montville
    name: Adam W. Montville
    org: Center for Internet Security
    abbrev: CIS
    email: adam.w.montville@gmail.com
    street: 31 Tech Valley Drive
    code: '12061'
    city: East Greenbush
    region: NY
    country: USA
  - ins: B. Munyan
    name: Bill Munyan
    org: Center for Internet Security
    abbrev: CIS
    email: bill.munyan.ietf@gmail.com
    street: 31 Tech Valley Drive
    code: '12061'
    city: East Greenbush
    region: NY
    country: USA

normative:


informative:



--- abstract

This memo describes an information model (and associated data model) that can be used to encapsulate evaluation of actual endpoint attributes in support of assessment.

--- middle


# Introduction

TBD

# Terms and Definitions

TBD

#  IANA Considerations

TBD

#  Security Considerations

TBD

#  Acknowledgements

TBD

#  Change Log

TBD


# Contributors
TBD

--- back

# Initial XML

```
<evaluation>
	<states>
		<state></state>
	</states>
	<variables>
		<constant-variable></constant-variable>
		<external-variable></external-variable>
		<local-variable>
			[function-groups, literal-component, variable-component, object-component]
		</local-variable>
	</variables>
</evaluation>
```
# The Attic

TBD
