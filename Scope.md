# Scope

[Include a detailed description of this Working Group’s Scope.  This Scope is important is it establishes the bounds of each contributor's and licensee's patent commitment. For guidance on drafting an appropriate Scope, you may find [ISO's guidance (see page 5)](https://www.iso.org/files/live/sites/isoorg/files/developing_standards/docs/en/how-to-write-standards.pdf "ISO How To Write Standards Guide") helpful.]

Establish vendor neutral cross-cloud measures for key cost & usage dimensions/metrics. These measures and their derivations establish a baseline schema that enables cloud billing data to be surfaced in a common FinOps serviceable format.

There is no standard for surfacing key cloud cost & usage measures across multiple Cloud Service Providers (CSPs) as of November 2022. This creates challenges for stakeholders when making decisions and quantifying the business value of cloud.  This specification will produce a consistent set of measures, describing their origins, and a prescribed approach for surfacing the corresponding billing data via a shared data schema that is serviceable across all CSPs. This FinOps open-billing specification will be critical for the FinOps community, especially as more and more service providers continue to enter the market with their own billing data formats and measures.

Deliverables:
* Matrix of dimensions & metrics that cross-reference with their corresponding CSP native metrics that are being leveraged from the datasource gaps are highlighted with guidance (if available/applicable) (optional) links to CSP support documentation for those native metrics referenced
* Schema Scope - a vendor neutral FinOps standard term for each dimension and metric a FinOps relevant definition for each dimension and metric list of Cloud Service Providers and corresponding billing data formats that will represent the input source for developing the logic for these metrics a description of possible applications / use casess being addressed as supplemental context
* Slide Presentation - capture a summary of the deliverables listed above to share with the F2 community

This specification will provide standards for any cloud service provider who generates billing data, will provide a standard way for any FinOps tool or platform which ingests cloud billing data to use, and will provide a common set of terminology for FinOps practitioners to use when communicating with both CSPs and tool providers or building custom tooling in-house. 

Contributions to this work will come from both CSPs in documenting their cloud billing data, from FinOps platforms and tool vendors who currently ingest CSP billing data, and from FinOps Practitioners and their companies who now build custom tooling and analysis using insights, and will be available under license for use by all.

Any changes of Scope are not retroactive. 
