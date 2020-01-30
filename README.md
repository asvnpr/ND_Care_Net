# Care-Net

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/asvnpr/ND_Care_Net/master)

## Rationale Overview

*"South Bend, Indiana, a post-industrial city of over 100,000 residents and a poverty rate double the national average, 
has an extensive network of formal and informal social services. Despite this, residents and local providers have expressed 
difficulty in finding and accessing services that are active. In an initial inquiry, stakeholders supporting formerly 
incarcerated individuals highlighted this challenge as critical. Researchers at the University of Notre Dame have the 
opportunity to address this issue by bringing together technical expertise with community partnerships.*

*The Indiana 211 Partnership works with Indiana United Ways and its local subsidiaries to maintain an information database
and provide a referral service. Annually, Indiana 211 reaches out to service providers to verify the accuracy of database
records. Due to the overwhelming capacity requirements of this approach, over 1,100 organization updates are past due as of
May 2019, and the oldest outdated record should have been updated in May 2018. Generally, accounts are expected to be removed
if an organization does not respond within 90 days of missing the database record verification. However, Indiana 211 often
keeps records active despite the lack of verification based on the importance of the services or the assumption that services
are continued. This approach has lead to an abundance of obsolete and inaccurate data, wasting time and resources for
populations in need and those who support them. This problem is compounded for those with complex needs that demand multiple
services from various providers or for populations where the service network is highly informal and consisting of activists
and volunteers.".*

## Broad Goals:
1. Refactor 211 IN Programs & Providers dataset as an attributed [Heterogeneous Information Network](https://arxiv.org/pdf/1511.04854.pdf)
2. Transform our originally unstructured, text data into quantitative data using:
  - attributed network embeddings to convert node and contents into a vector
  - that capture structural (network) and semantic (content/text) similarities 
  - using existing and/or modified state-of-the-art Deep Learning methods
 3. Based on clustering of these network nodes, recommend services to users based on their queries and eventually their user data
 4. Explore methods of effective crowdsourcing of updated information and new resources
 5. Usability testing in the city of South Bend
 
 ## Documentation TODO 
 - Briefly describe notebooks and organization
 - Describe how data is expected to be formatted
 - document code, rationale for model choices, etc
 
 ## Features TODO
 - Make final choice of network embedding method(s)
 - Implement clustering of embeddings
 - Test clustering metrics of several embedding methods
 - Recommend over clustering or other method
 - Visualization of embeddings, clusters, and topic modeling
