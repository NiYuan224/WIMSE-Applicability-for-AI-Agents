---
title: "TODO - Your title"
abbrev: "TODO - Abbreviation"
category: info

docname: draft-wimse-agent-id-latest
submissiontype: IETF  # also: "independent", "editorial", "IAB", or "IRTF"
number:
date:
consensus: true
v: 3
# area: AREA
# workgroup: WG Working Group
keyword:
 - next generation
 - unicorn
 - sparkling distributed ledger
venue:
#  group: WG
#  type: Working Group
#  mail: WG@example.com
#  arch: https://example.com/WG
  github: "NiYuan224/WIMSE-Applicability-for-AI-Agents"
  latest: "https://NiYuan224.github.io/WIMSE-Applicability-for-AI-Agents/draft-wimse-agent-id.html"

author:
 -
    fullname: "NiYuan224"
    organization: Your Organization Here
    email: "niyuan1@huawei.com"

normative:

informative:

...

--- abstract

TODO Abstract


--- middle

# Introduction




# Basic Architecture

{::boilerplate bcp14-tagged}
The proposed architecture enables the secure acquisition and management of agent identity credentials，which established a foundation for agent zero-trust access. Key components include:
Trust Domain: a logical grouping of systems that share a common set of security controls and policies. Agent credentials are issued under the authority of a trust domain.
Agent: the autonomous software entity running on a device that initiates the credential request. Agents operate independently and are responsible for authenticating themselves and requesting appropriate credentials within a trust domain.
Identity server: A trust entity issuing the agent identity credential, which serves as the root of trust for a trust domain. For simplicity, this document sometimes uses the term of "server" to indicate the identity server.
Identity proxy: an intermediary component on the device that can request, inspect, replace or augment agent identity credentials. It exposes an Agent API locally to agents running on the device. For simplicity, this document sometimes uses the term of "proxy" to indicate the identity proxy.


# Security Considerations

TODO Security


# IANA Considerations

This document has no IANA actions.


--- back

# Acknowledgments
{:numbered="false"}

TODO acknowledge.
