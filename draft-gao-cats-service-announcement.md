---
title: "Service Announcement Methods for CATS"
abbrev: "TODO - Abbreviation"
category: info

docname: draft-gao-cats-service-announcement-latest
submissiontype: IETF  # also: "independent", "editorial", "IAB", or "IRTF"
number:
date:
consensus: true
v: 3
area: "Routing"
workgroup: "Computing-Aware Traffic Steering"
keyword:
 - next generation
 - unicorn
 - sparkling distributed ledger
venue:
  group: "Computing-Aware Traffic Steering"
  type: "Working Group"
  mail: "cats@ietf.org"
  arch: "https://mailarchive.ietf.org/arch/browse/cats/"
  github: "ZhenghaoH/draft-gao-cats-service-announcement-methods-00"
  latest: "https://ZhenghaoH.github.io/draft-gao-cats-service-announcement-methods-00/draft-gao-cats-service-announcement.html"

author:
 -
    
    fullname: "Shuai Gao"
    organization: Beijing Jiaotong University
    email: "shgao@bjtu.edu.cn"
    
    fullname: "Zhenghao Hu"
    organization: Beijing Jiaotong University
    email: "24110054@bjtu.edu.cn"

    fullname: "Xiaoting Ma"
    organization: China Telecom
    email: "maxt3@chinatelecom.cn"

normative:

informative:


--- abstract

This document introduces network-layer service announcement solutions based on architecture defined in [draft-ietf-cats-framework-02]. In particular, the scheme describes how to disseminate computing service information to clients and the control plane through service announcement messages. This draft also proposes to classify the attributes used to describe computing services and analyzes several service querying mechanisms.


--- middle

# Introduction

As described in [draft-ietf-cats-framework-02], steering in CATS aims to select the suitable service contact instance(s) from a set of candidates. Particularly, the CATS architecture gives the exemplifications of the service announcement workflow for distributed design. However, the CATS framework does not provide the detailed description of the specific process of service announcement. Additionally, the application-layer DNS solutions for name resolution in CATS face challenges in adapting to high-frequency dynamic resolution and result in significant signaling overhead.
This document proposes network-layer service announcement solutions for CATS based on identifier resolution and mapping, and classifies the attributes used to describe computing services. Several service querying mechanisms are further analyzed based on the proposed solutions.


# Conventions and Definitions

{::boilerplate bcp14-tagged}
This document makes use of the terms defined in [draft-ietf-cats-framework-02]. In addition, the following terms are defined below:
*  Computing service Attributes (CSA): Attributes that multi-dimensionally describe the computing service.
*  Computing service Demand Attributes (CSDA): Attributes that describe the computing resources and network resources requirements of the computing service.
*  Computing service Information Attributes (CSIA): Attributes that detail the nature of the computing service and the methods of its provision.


# Security Considerations

TODO Security


# IANA Considerations

This document has no IANA actions.


--- back

# Acknowledgments
{:numbered="false"}

TODO acknowledge.
