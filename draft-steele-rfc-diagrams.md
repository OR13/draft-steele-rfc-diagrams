---
title: "Diagrams"
abbrev: "Diagrams"
category: info

docname: draft-steele-rfc-diagrams-latest
submissiontype: IETF  # also: "independent", "editorial", "IAB", or "IRTF"
number:
date:
consensus: true
v: 3
# area: AREA
# workgroup: WG Working Group
keyword:
 - next generation
venue:
#  group: WG
#  type: Working Group
#  mail: WG@example.com
#  arch: https://example.com/WG
  github: "OR13/draft-steele-rfc-diagrams"
  latest: "https://OR13.github.io/draft-steele-rfc-diagrams/draft-steele-rfc-diagrams.html"

author:
 -
    fullname: "Orie Steele"
    organization: Your Organization Here
    email: "orie@transmute.industries"

normative:

informative:


--- abstract

TODO Abstract


--- middle

# Introduction

This draft is for testing the diagram options that come from the I-D tool.


# Conventions and Definitions

{::boilerplate bcp14-tagged}

# AASVG

~~~aasvg
                 .----------.
                |  Artifact  |
                 '----+-----'
~~~

# mermaid

~~~mermaid
erDiagram
    CUSTOMER ||--o{ ORDER : places
    ORDER ||--|{ LINE-ITEM : contains
    CUSTOMER }|..|{ DELIVERY-ADDRESS : uses
~~~

# Security Considerations

TODO Security


# IANA Considerations

This document has no IANA actions.


--- back

# Acknowledgments
{:numbered="false"}

TODO acknowledge.
