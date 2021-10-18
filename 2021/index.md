---
title: "WoTBAn&Az 2021"
---

The 2021 NSF Cybersecurity Summit Workshop on Token-Based Authentication and Authorization (WoTBAn&Az 2021) will be held online [from 10am to 2pm Eastern Time on Monday, October 18](https://www.timeanddate.com/worldclock/fixedtime.html?msg=WoTBAn%26Az+2021&iso=20211018T10&p1=3723&ah=4), co-located with the [2021 NSF Cybersecurity Summit](https://www.trustedci.org/2021-cybersecurity-summit). Please contact [workshop@sciauth.org](mailto:workshop@sciauth.org) for Zoom coordinates or for any questions.

WoTBAn&Az 2021 was preceded by the October 14-15 [OSG Token Transition Workshop](https://opensciencegrid.org/events/Token-Transition-Workshop/).

Workshop Materials and Recordings
------------------
See the schedule below for links to available workshop materials. Presenters, please submit workshop materials by email to [workshop@sciauth.org](mailto:workshop@sciauth.org) or by opening a GitHub [issue](https://github.com/SciAuth/workshop/issues) or [pull request](https://github.com/SciAuth/workshop/pulls).

We plan to record the workshop - to capture presenter and audience comments and to make sessions available for later replay online.

Workshop Schedule
------------------

Time (Eastern) | Topic | Presenters | Materials
-------------- | ----- | ---------- | ---------
[10:00-10:10](https://www.timeanddate.com/worldclock/fixedtime.html?iso=20211018T1000&p1=3723&am=10) | Intro | Derek Simmel
[10:10-10:50](https://www.timeanddate.com/worldclock/fixedtime.html?iso=20211018T1010&p1=3723&am=40) | Tokens in the Worldwide LHC (Large Hadron Collider) Computing Grid (WLCG) | Hannah Short, Mine Altunay, Jim Basney, Dave Dykstra, Hannah Short, Andrea Ceccanti | [1](https://sciauth.org/workshop/2021/20211018_WoTBAn&Az_WLCG_Introduction.pptx.pdf) [2](https://sciauth.org/workshop/2021/Federation_Status_WoTBAn_10_18_21.pdf) [3](https://sciauth.org/workshop/2021/202110-cilogon-wlcg-tokens.pdf) [4](https://sciauth.org/workshop/2021/Wotbananza_CondorVault_20211018.pdf) [5](https://sciauth.org/workshop/2021/20211018_WoTBAn&Az_WLCG_CERN.pptx.pdf) [6](https://sciauth.org/workshop/2021/20211018-IAM-WOTABANZA.pdf)
[10:50-11:30](https://www.timeanddate.com/worldclock/fixedtime.html?iso=20211018T1050&p1=3723&am=40) | Tokens in the Tapis API Platform | Rich Cardone, Sean Cleveland, and Joe Stubbs | [1](https://sciauth.org/workshop/2021/Tokens-in-The-Tapis-API-Platform-NSF-Cybersecurity-workshop-21.pdf)
[11:30-11:40](https://www.timeanddate.com/worldclock/fixedtime.html?iso=20211018T1130&p1=3723&am=10) | Break
[11:40-12:00](https://www.timeanddate.com/worldclock/fixedtime.html?iso=20211018T1140&p1=3723&am=20) | Using CiLogon OIDC service for users authentication in kubernetes | Dmitry Mishin
[12:00-12:30](https://www.timeanddate.com/worldclock/fixedtime.html?iso=20211018T1200&p1=3723&am=30) | SciTokens at LIGO | James Clark | [1](https://sciauth.org/workshop/2021/LIGOSciTokensOct2021.pdf)
[12:30-1:00 ](https://www.timeanddate.com/worldclock/fixedtime.html?iso=20211018T1230&p1=3723&am=30)  | HTCondor and OSG Token Transition | Brian Bockelman | [1](https://sciauth.org/workshop/2021/HTCondor_OSG_Token_Transition.pdf)
[ 1:00-1:10 ](https://www.timeanddate.com/worldclock/fixedtime.html?iso=20211018T1300&p1=3723&am=10)  | Break
[ 1:10-1:50 ](https://www.timeanddate.com/worldclock/fixedtime.html?iso=20211018T1310&p1=3723&am=40) | Discussion
[ 1:50-2:00 ](https://www.timeanddate.com/worldclock/fixedtime.html?iso=20211018T1350&p1=3723&am=10) | Wrapup | Derek Simmel

About the Workshop
------------------
As the worldwide science, engineering, research and academic communities have become more interdependent to pursue and succeed in their missions, so too has the need for interoperable, usable, and manageable approaches for authentication, authorization and identity (AAI) infrastructure that build upon federated identity and group management solutions to ensure consistent access standards, enforcement and protection of CI resources and assets. Decades of effort in establishing international trust federations and standards for PKI and secure interoperation using digital credentials in the research and education communities have enabled essential interoperability, security and trust for national and international science collaborations. As more web-based computational science and data applications, workflows and automated pipelines are deployed, a more robust, interoperable AAI infrastructure is needed - enter JSON Web Tokens (JWT), an open IETF standard (RFC 7519) for securely exchanging information in digitally signed JSON objects. Many large institutions, science collaborations and national CIs are working to migrate their regional and project-specific AAI infrastructures to JWT-based methods -- typically however, in isolation and attending primarily to their local needs and maintaining compatibility with their existing AAI infrastructures. Coupled with international standards for security and authorization information to be contained in these JWTs, we have both an opportunity and an obligation to ensure that best practices are developed and observed to ensure compatibility, interoperability, usability and trust in these implementations.

The inaugural Workshop on Token-Based Authentication and Authorization ([WoTBAn&Az 2020](https://indico.rnp.br/event/33/)) convened online via Zoom on November 30 and December 1, 2020, hosted by [TAGPMA](http://www.tagpma.org/). This workshop gathered major R&E CI developers, operators, and service providers, including representatives from Fermilab, Globus, LIGO, SciTokens, WLCG and XSEDE, to present and discuss early implementations of token-based authentication and authorization infrastructures and solutions to understand the challenges faced in migrating to JWT-based AAI, and to identify opportunities and requirements to build common best practices, standards, and trust for token-based authentication and authorization. Several needs emerged from the presentation and discussions, as well as a demonstrated eagerness within the community to collaborate in developing common best practices.

The NSF Cybersecurity Summit offers a unique opportunity to broaden awareness, participation and input to inform the JWT-based AAI development community, and to ensure access to best practices in JWT-based AAI for NSF-sponsored CI stakeholders. The 2021 NSF CyberSecurity Summit Workshop on Token-Based Authentication and Authorization (WoTBAn&Az 2021) will build on the findings, community interest and momentum created by the 2020 workshop to focus on three primary needs: (1) use cases to drive development of interoperable solutions, (2) best practices for token handling by issuers, developers, service operators and users, and (3) security requirements and responsibilities for trust and operations through token lifecycles. The workshop will invite current and prospective developers and stakeholders to contribute their experience and requirements in these areas.

Presentations at the 2020 WoTBAn&Az workshop included:
* Token Based Authorisation for WLCG
* Globus Auth: expanding the services ecosystem for protected data
* LIGO's use of SciTokens
* XSEDE's Perspective on Token Assurance for Authentication and Authorization
* Fermilab's experience transitioning to token-based AAI technologies

Workshop Chairs
---------------
* Derek Simmel, Pittsburgh Supercomputing Center
* Jim Basney, National Center for Supercomputing Applications
* Brian Bockelman, Morgridge Institute for Research
* Derek Weitzel, University of Nebraska-Lincoln

Intended Audience
--------------------------------------
The intended audience includes developers, operators, and stakeholders in interoperable JWT-based AAI for the worldwide science, engineering, research and academic communities.

Contact Information
-------------------
* Derek Simmel <dsimmel@psc.edu>
* Jim Basney <jbasney@illinois.edu>
* Brian Bockelman <bbockelman@morgridge.org>
* Derek Weitzel <dweitzel@unl.edu>

Acknowledgements
----------------
The workshop is co-organized by [SciAuth](https://sciauth.org/) and [TAGPMA](http://www.tagpma.org/).
