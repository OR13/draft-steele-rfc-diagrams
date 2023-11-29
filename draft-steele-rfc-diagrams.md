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

# Mermaid

~~~mermaid
erDiagram
    Issuer ||--o{ Holder : "issues credential"
    Holder ||--o{ Verifier :  "proves credential"
    Verifier ||--o{ Issuer : "checks status"
~~~


~~~mermaid
flowchart
  alice
  bob
  alice --> bob
~~~

~~~mermaid
sequenceDiagram
    Alice->>John: Hello John, how are you?
    John-->>Alice: Great!
    Alice-)John: See you later!
~~~

# Mscgen

~~~mscgen
# Fictional client-server protocol
msc {
 arcgradient = 8;

 a [label="Client"],b [label="Server"];

 a=>b [label="data1"];
 a-xb [label="data2"];
 a=>b [label="data3"];
 a<=b [label="ack1, nack2"];
 a=>b [label="data2", arcskip="1"];
 |||;
 a<=b [label="ack3"];
 |||;
}
~~~

# Plantuml

~~~plantuml
@startuml
skinparam roundCorner 15
actor actor
agent agent
artifact artifact
boundary boundary
card card
circle circle
cloud cloud
collections collections
component component
control control
database database
entity entity
file file
folder folder
frame frame
hexagon hexagon
interface interface
label label
node node
package package
person person
queue queue
rectangle rectangle
stack stack
storage storage
usecase usecase
@enduml
~~~

# Security Considerations

TODO Security


# IANA Considerations

This document has no IANA actions.


--- back

# Acknowledgments
{:numbered="false"}

TODO acknowledge.
