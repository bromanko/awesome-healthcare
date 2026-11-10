# Catalog review inventory

**34 proposed changes · 32 uncertain · 10 unresolved keeps**

232 entries researched. 156 saved reviews for recurring runs.

Research recommendations from the initial Opus review. The full set has not passed prior-discussion or patch validation. Proposed diffs are previews, not approved patches. Nothing was applied or submitted.

Catalog: `4a9c564f7c277080e9353ecbb19d71ece381350d` · README SHA-256: `b7db38a8eda79fe4dea1465a6a18789a9c49c13b6501cf1c16a1f5454210fefa`

## Proposed changes

<h3>HospitalRun — remove</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -46,7 +46,6 @@
   * [GNU Health](https://www.gnuhealth.org) - Electronic Health Record, Hospital Management, and Health Information System.
   * [GNUmed](https://www.gnumed.de/documentation/) - Electronic Medical Record software.
   * [HasteHealth](https://github.com/HasteHealth/HasteHealth) - Scalable FHIR server and clinical data repository.
-  * [HospitalRun](https://hospitalrun.io) - Helps provide the most modern Hospital Information System possible to the least resourced environments.
   * [HOSxP](https://hosxp.net/wordpress/) - Thai Hospital Information System that aims to ease the healthcare workflow of health centers and central hospitals.
   * [ICTHospital](https://github.com/ictinnovations/ICTHospital) - Hospital management software with built-in unified communications, built on Laravel.
   * [LibreHealth EHR](https://librehealth.io/projects/lh-ehr/) - Clinically-focused Electronic Health Record System.
```

<details>
<summary>Evidence and limitations</summary>

<p>The official site states &#x27;The project has been archived.&#x27; Both GitHub repos, HospitalRun/hospitalrun (v2 monorepo) and HospitalRun/hospitalrun-frontend, were archived by the owner on Jan 9, 2023. No successor is documented. The list rules say code must not be abandoned or discontinued. Removal should be proposed via an issue, as the contribution rules require.</p>

<p>https://hospitalrun.io/ — HTTP 200. Banner: &#x27;The project has been archived. Thank you to all contributors, maintainers, friends and sponsors.&#x27;</p>

<p>https://github.com/HospitalRun/hospitalrun — &#x27;This repository has been archived by the owner on Jan 9, 2023. It is now read-only.&#x27; Last commit feed entry: 2021-02-05.</p>

<p>https://github.com/HospitalRun/hospitalrun-frontend — Archived by the owner on Jan 9, 2023. Last commit feed entry: 2022-02-12.</p>

<p>Caveats: Existing deployments may still use the software, but no maintained successor is documented.</p>

<p>Independent source check: The official project site explicitly announces archival. This is affirmative project-status evidence, not a conclusion based solely on old commits. A removal proposal must still follow the catalog’s issue-first rule.</p>

<p>https://hospitalrun.io/ — Official site states that the project has been archived.</p>

<p>https://github.com/kakoni/awesome-healthcare/blob/master/CONTRIBUTING.md — List rules exclude abandoned projects and require an issue before removals.</p>

</details>

<h3>Ripple — remove</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -62,7 +62,6 @@
   * [OSCAR EMR](https://bitbucket.org/oscaremr/oscar) - OSCAR McMaster Project.
   * [Ottehr](https://github.com/masslight/ottehr) - Modular, Production-Ready, Open-Source EHR
   * [Ozone HIS](https://www.ozone-his.com) - The entreprise-grade integrated health information system built with OpenMRS 3
-  * [Ripple](https://www.ripple.foundation) -  NHS-funded, community led initiative working towards an integrated Digital Care Record Platform.
 
 ### Scribe
   * [OpenScribe](https://github.com/sammargolis/OpenScribe) - Open source, local-first medical scribe platform for recording clinical encounters, transcribing audio, and generating structured draft clinical notes.
```

<details>
<summary>Evidence and limitations</summary>

<p>Ripple Foundation&#x27;s own news post (2020-09-20, still the latest on the site) says its founders &quot;have chosen to move onto new challenges this year&quot;. It adds that the site &quot;will remain openly available as a signpost&quot; and that its work remains available to reuse. The initiative is therefore no longer &quot;working towards&quot; a Digital Care Record Platform. That is affirmative official evidence that the listed initiative is discontinued, which the rules say must not be listed. Removal must go through an issue, as the contribution rules require.</p>

<p>https://www.ripple.foundation/2020/09/changes-challenges-choices/ — &#x27;the founders of the Ripple Foundation have chosen to move onto new challenges this year... all the good work that the Ripple Foundation has pioneered remains openly available... The Ripple Foundation site and resources will remain openly available as a signpost&#x27;.</p>

<p>https://www.ripple.foundation/ — Homepage uses past tense (&#x27;has supported open source...&#x27;). The newest news items are from 2019–2020.</p>

<p>Caveats: Component projects (PulseTile, QEWD, EtherCIS) may continue independently. None was confirmed as an official successor to the Ripple platform, so no replacement is proposed.; &#x27;NHS-funded&#x27; was not re-verified.</p>

</details>

<h3>Continuity of Care Document — update</h3>

<p>0 proposed change(s); 1 held for unresolved questions.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The listed URL (product_id=7) is HL7&#x27;s product brief for &quot;CDA® Release 2&quot;, the base Clinical Document Architecture, not the Continuity of Care Document. That page links CCD as a related document via product_id=6, whose brief is titled &quot;HL7/ASTM Implementation Guide for CDA® R2 - Continuity of Care Document (CCD®) Release 1&quot;. The URL is a confirmed identity mismatch, and the fix is to point at product_id=6. The live hl7.org pages currently serve an AWS WAF bot challenge (HTTP 202, empty body), so content was read from Wayback captures.</p>

<p>http://web.archive.org/web/20261015200659/https://www.hl7.org/implement/standards/product_brief.cfm?product_id=7 — Title &#x27;HL7 Standards Product Brief - CDA® Release 2&#x27;. Description: &#x27;The HL7 Version 3 Clinical Document Architecture (CDA®) is a document markup standard...&#x27;. Related documents include &#x27;HL7/ASTM Implementation Guide for CDA® R2 - Continuity of Care Document (CCD®) Release 1&#x27;, linked as product_id=6.</p>

<p>http://web.archive.org/web/20241110220505/http://www.hl7.org/implement/standards/product_brief.cfm?product_id=6 — Title &#x27;HL7/ASTM Implementation Guide for CDA® R2 - Continuity of Care Document (CCD®) Release 1&#x27;. &#x27;The Continuity of Care Document (CCD) is a joint effort of HL7 International and ASTM...&#x27;</p>

<p>https://www.hl7.org/implement/standards/product_brief.cfm?product_id=7 — Live fetch returns HTTP 202 with an AWS WAF challenge page, so it could not be read directly.</p>

<p>Blocking questions: The latest successful (HTTP 200) capture of product_id=6 is from 2024-11-10. All 2026 captures are WAF challenges, so the page&#x27;s current live content could not be confirmed. It is still linked from the Oct 2026 product_id=7 page.</p>

<p>Caveats: In US practice CCD is largely superseded by C-CDA (product_id=492, &#x27;Consolidated CDA Templates for Clinical Notes, Edition 4&#x27;). Whether to list CCD or C-CDA is an editorial choice.</p>

</details>

<h3>FHIR — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -71,7 +71,7 @@
 ### Specifications
   * [Continuity of Care Document](https://www.hl7.org/implement/standards/product_brief.cfm?product_id=7) - Continuity of Care Document specifications
   * [DICOM Standards Browser](https://dicom.innolitics.com/ciods) - Provides an effective way to learn the DICOM standard and inspect DICOM attributes.
-  * [FHIR](https://www.hl7.org/fhir/) - Fast Health Interoperability Resources.
+  * [FHIR](https://www.hl7.org/fhir/) - Fast Healthcare Interoperability Resources.
   * [HL7 Version 2](https://www.hl7.org/implement/standards/product_brief.cfm?product_id=185) - Specifications for all versions of HL7v2
   * [OHDSI OMOP Common Data Model](https://www.ohdsi.org/data-standardization/) - Standardized data model for many healthcare concepts, awesome Github presence including scripts for many major relational databases.
   * [OpenEHR](https://www.openehr.org) - Open specification upon which software can be built.
```

<details>
<summary>Evidence and limitations</summary>

<p>www.hl7.org/fhir/ resolves (200) to the current FHIR specification (R5, v5.0.0), so the link and fit are fine. But the description expands the acronym as &quot;Fast Health Interoperability Resources&quot;. The official spec pages give &quot;Fast Healthcare Interoperability Resources&quot;. This is an explicit factual wording error.</p>

<p>https://www.hl7.org/fhir/ — Live page is the FHIR specification home, v5.0.0 (R5).</p>

<p>https://www.hl7.org/fhir/summary.html — Page text contains &#x27;Fast Healthcare Interoperability Resources&#x27;.</p>

<p>https://hl7.org/fhir/overview.html — Page text contains &#x27;Fast Healthcare Interoperability Resources&#x27;.</p>

<p>Caveats: The &#x27;/fhir/&#x27; path tracks the current published version, which may change (for example to R6).</p>

</details>

<h3>Dicoogle — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -86,7 +86,7 @@
   * [Cornerstone3D](https://github.com/cornerstonejs/cornerstone3D) - JavaScript libraries for building web-based medical imaging platforms.
   * [dcm2niix](https://github.com/rordenlab/dcm2niix) - DICOM to NIfTI converter.
   * [dcm4che](https://www.dcm4che.org/) - Clinical Image and Object Management.
-  * [Dicoogle](https://github.com/bioinformatics-ua/dicoogle) - Dicoogle is an extensible, platform-independent and open-source PACS
+  * [Dicoogle](https://github.com/dicoogle/dicoogle) - Dicoogle is an extensible, platform-independent and open-source PACS
   * [Drishti](https://github.com/nci/drishti/wiki) - Tomography and electron-microscopy data visualizer for both scientists and lay people.
   * [DICOMcloud](https://github.com/DICOMcloud/DICOMcloud) - A standalone DICOMweb server with RESTful implementation of the DICOMweb/WADO services.
   * [DICOM Server](https://github.com/microsoft/dicom-server) - OSS Implementation of DICOMweb standard.
```

<details>
<summary>Evidence and limitations</summary>

<p>The listed URL github.com/bioinformatics-ua/dicoogle redirects to github.com/dicoogle/dicoogle, which GitHub serves as the canonical repository. It is active and not archived. The README confirms the description (&#x27;extensible, platform-independent and open-source PACS&#x27;), so only the URL needs changing; the name stays the same.</p>

<p>https://github.com/dicoogle/dicoogle — Requesting https://github.com/bioinformatics-ua/dicoogle ends at https://github.com/dicoogle/dicoogle with HTTP 200. The repository description is &#x27;Dicoogle - Open Source PACS&#x27; and it is not archived.</p>

<p>https://raw.githubusercontent.com/dicoogle/dicoogle/dev/README.md — &#x27;Dicoogle is an extensible, platform-independent and open-source PACS archive software...&#x27; The dev branch is for Dicoogle 3, and the Dicoogle 2 line is &#x27;being phased out&#x27;.</p>

<p>https://github.com/dicoogle/dicoogle/commits/dev.atom — Latest dev commit is dated 2026-10-28.</p>

<p>Caveats: The README still links to the release/2.X branch under the old bioinformatics-ua path, which GitHub redirects. I did not examine the 2.X legacy line&#x27;s maintenance beyond the README saying it is being phased out.; The description has no trailing period, unlike the list format. That is cosmetic and not changed here.</p>

</details>

<h3>DICOM Server — remove</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -89,7 +89,6 @@
   * [Dicoogle](https://github.com/bioinformatics-ua/dicoogle) - Dicoogle is an extensible, platform-independent and open-source PACS
   * [Drishti](https://github.com/nci/drishti/wiki) - Tomography and electron-microscopy data visualizer for both scientists and lay people.
   * [DICOMcloud](https://github.com/DICOMcloud/DICOMcloud) - A standalone DICOMweb server with RESTful implementation of the DICOMweb/WADO services.
-  * [DICOM Server](https://github.com/microsoft/dicom-server) - OSS Implementation of DICOMweb standard.
   * [DICOM Web Viewer](https://ivmartel.github.io/dwv/) - JavaScript/HTML5-based DICOM viewer with standard tools and a focus on supporting various screen sizes.
   * [Fiji](https://imagej.net/software/fiji/) - Open-source platform for biological-image analysis.
   * [highdicom](https://github.com/ImagingDataCommons/highdicom) - High-level DICOM abstractions for Python, including segmentations, structured reports and annotations.
```

<details>
<summary>Evidence and limitations</summary>

<p>Microsoft has officially announced it is archiving the OSS DICOM server so it can focus on the managed Azure DICOM service. The main branch now contains only client code, and the server implementation was moved to an &#x27;archived&#x27; branch kept &#x27;for reference&#x27;. The listed repository therefore no longer provides an open-source DICOMweb server. The Azure managed service is a commercial cloud offering, not an open-source successor, so &#x27;replace&#x27; does not apply. Under the rules this should be raised in a removal issue, not a patch.</p>

<p>https://raw.githubusercontent.com/microsoft/dicom-server/main/README.md — &#x27;our team is planning to archive the DICOM server project to allow us to focus on delivering customer value to our managed service offering on Azure&#x27;. &#x27;All code except for the client has been removed... preserved in an archived branch for reference.&#x27;</p>

<p>https://github.com/microsoft/dicom-server/discussions/3401 — Maintainer post dated 2024-03-28 says: &#x27;Our current plans are to archive this project on April 30th, 2024&#x27; and directs feedback to the Azure DICOM service forums.</p>

<p>https://github.com/microsoft/dicom-server/commits/main.atom — Latest commit on main is dated 2024-12-18. The repository is not formally archived on GitHub (no banner), even though the server code has been removed.</p>

<p>Caveats: The &#x27;archived&#x27; branch still holds the historical server code as a reference. I did not examine its contents in depth and make no claim about its maintenance status.; GitHub has not set the repository&#x27;s archived flag, despite the announcement.</p>

</details>

<h3>DentalPin — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -118,7 +118,7 @@
   * [Weasis](https://github.com/nroduit/Weasis) - Standalone and web-based DICOM viewer.
 
 ### Dental
-  * [DentalPin](https://github.com/martinezsalmeron/dentalpin) - Dental practice management with an AI agent that runs real operations.
+  * [DentalPin](https://github.com/dentalpin/dentalpin) - Dental practice management with an AI agent that runs real operations.
   * [Open Dental](https://www.opendental.com) - Dental Practice Management Software.
   * [OpenMolar](https://openmolar.com/) - Dental Practice Management Software. 
 
```

<details>
<summary>Evidence and limitations</summary>

<p>The listed URL github.com/martinezsalmeron/dentalpin redirects. GitHub API metadata gives the canonical repo as dentalpin/dentalpin (same project, active, release v2.10.0 on 2026-11-06), so the URL should be updated. The description is supported: the README describes dental clinic management with a built-in agentic AI copilot that runs real operations on clinic data. Separately, the project is licensed under BSL 1.1. Its LICENSE file says the BSL &#x27;is not an Open Source license&#x27;. Under the contribution rules, the entry would need a &#x27;(Commercial Software)&#x27;-style note or a maintainer decision on fit.</p>

<p>https://github.com/dentalpin/dentalpin — The API request for martinezsalmeron/dentalpin resolves to dentalpin/dentalpin. Description: &#x27;The open source agentic dental software. Built for AI.&#x27; Not archived, release v2.10.0 (2026-11-06).</p>

<p>https://raw.githubusercontent.com/dentalpin/dentalpin/main/README.md — Says it is &#x27;Source-available (BSL 1.1) dental clinic management software&#x27;, with a &#x27;built-in agentic AI assistant&#x27; that &#x27;runs real tools — search patients, book or reschedule appointments, record a payment&#x27;.</p>

<p>https://raw.githubusercontent.com/dentalpin/dentalpin/main/LICENSE — The license is Business Source License 1.1 and states &#x27;The Business Source License ... is not an Open Source license&#x27;. It converts to Apache-2.0 four years after publication.</p>

<p>https://raw.githubusercontent.com/dentalpin/dentalpin/main/docs/adr/0004-bsl-license.md — ADR dated 2026-04-27 adopting BSL 1.1, with a restriction on competing commercial SaaS use.</p>

<p>Caveats: Licensing fit is a separate maintainer decision. The rules require free/open source software or an explicit &#x27;(Commercial Software)&#x27; note. BSL 1.1 is source-available, not FSF/OSI-approved, so the maintainer may want to add a note or open a removal issue. That does not affect the URL correction.; Did not run the software or the demo.</p>

</details>

<h3>Open Dental — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -119,7 +119,7 @@
 
 ### Dental
   * [DentalPin](https://github.com/martinezsalmeron/dentalpin) - Dental practice management with an AI agent that runs real operations.
-  * [Open Dental](https://www.opendental.com) - Dental Practice Management Software.
+  * [Open Dental](https://www.opendental.com) - Dental Practice Management Software (Commercial Software).
   * [OpenMolar](https://openmolar.com/) - Dental Practice Management Software. 
 
 ### Laboratory
```

<details>
<summary>Evidence and limitations</summary>

<p>Open Dental&#x27;s official license page says that &#x27;In version 24.4, the Open Dental license changed from open source GPL to proprietary.&#x27; The site sells the product. The contribution rules require non-open-source software to carry a &#x27;(Commercial Software)&#x27; note, and the entry has none. The practice-management description itself is still accurate.</p>

<p>https://www.opendental.com/site/license.html — States &#x27;In version 24.4, the Open Dental license changed from open source GPL to proprietary.&#x27;</p>

<p>https://www.opendental.com/ — Live. Describes itself as &#x27;Comprehensive, highly customizable dental practice management software at an affordable price&#x27; with an &#x27;Order Open Dental&#x27; option. Current versions are 26.x.</p>

<p>Caveats: The maintainer may instead prefer to open a removal issue, since the list is aimed at open source software. The rules permit commercial entries with the note, so updating is the minimal compliant change.</p>

</details>

<h3>OpenMolar — remove</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -120,7 +120,6 @@
 ### Dental
   * [DentalPin](https://github.com/martinezsalmeron/dentalpin) - Dental practice management with an AI agent that runs real operations.
   * [Open Dental](https://www.opendental.com) - Dental Practice Management Software.
-  * [OpenMolar](https://openmolar.com/) - Dental Practice Management Software. 
 
 ### Laboratory
   * [MISO](https://github.com/miso-lims/miso-lims) - Laboratory information management system for NGS sequencing centres.
```

<details>
<summary>Evidence and limitations</summary>

<p>Recommendation for a removal issue, not a patch. The official OpenMolar site says the project has been discontinued. Its OpenMolar1 page states &#x27;This is now a mothballed project. Neil Wallace 9th January 2018&#x27; and that it was used in practice only until 19 January 2017. The homepage says OM1 &#x27;is no longer utilised in practice&#x27; and that OpenMolar2 &#x27;is effectively a dead project&#x27;. The OM1 source repo&#x27;s last commits are from February 2017. The rules say &#x27;Code must not be abandoned/discontinued&#x27;. The homepage also says hobby development of OM1 &#x27;continues&#x27;, which conflicts with the mothballed note, so the maintainer should weigh that.</p>

<p>https://openmolar.com/om1 — Says OpenMolar1 &#x27;was used daily in the Academy Dental Practice ... until the 19th January 2017&#x27; and &#x27;This is now a mothballed project. Neil Wallace 9th January 2018.&#x27;</p>

<p>https://openmolar.com/ — Says OpenMolar1 &#x27;is no longer utilised in practice, although development continues as a hobby project&#x27; and OpenMolar2 &#x27;is effectively a dead project as it has not been ported to Python3 or Qt5&#x27;.</p>

<p>https://github.com/rowinggolfer/openmolar1 — Not archived. The latest commits are dated 2017-02-16, 2017-02-04 and 2017-01-09, although the repo shows a push on 2024-02-16.</p>

<p>Caveats: Removal requires opening an issue under the contribution rules. This is a recommendation for that discussion.; The 2024 push to openmolar1 was not traced to specific content.</p>

</details>

<h3>API Server — remove</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -128,7 +128,6 @@
   * [SENAITE](https://www.senaite.com) - Laboratory Information Management System.
 
 ### Frameworks
-  * [API Server](https://github.com/smart-on-fhir/api-server) - FHIR Server to support patient- and clinician-facing apps.
   * [Blaze](https://github.com/samply/blaze) - A FHIR Store with internal, fast CQL Evaluation Engine
   * [CareKit](https://github.com/carekit-apple/CareKit/) - Open source software framework for creating apps that help people better understand and manage their health.
   * [CHT](https://communityhealthtoolkit.org/) - Community Health Toolkit - set of Open Source tools that support community healthcare
```

<details>
<summary>Evidence and limitations</summary>

<p>The repo&#x27;s own README opens with &#x27;This project is no longer maintained&#x27; and points readers to other open-source FHIR servers. The last commit was in October 2017. The README calls it &#x27;highly experimental&#x27;, requires Java 7 (explicitly not Java 8) and Grails, and its examples use the DiagnosticOrder resource from pre-STU3 FHIR. The pinned rules require code that is not abandoned or discontinued and is of GA quality. Recommend raising removal in an issue, as the rules require; no official successor is named.</p>

<p>https://raw.githubusercontent.com/smart-on-fhir/api-server/master/README.md — First line: &#x27;## This project is no longer maintained, but there is a list of other open source FHIR servers [here]&#x27;. It also says &#x27;Still highly experimental&#x27;, lists Oracle Java 7 (&#x27;not Java 8&#x27;) as a prerequisite, and its examples use the DiagnosticOrder resource.</p>

<p>https://github.com/smart-on-fhir/api-server/commits/master.atom — Latest commit on master is dated 2017-10-17.</p>

<p>Caveats: The repo is not archived on GitHub (per the packet snapshot). The removal case rests on the explicit README notice.; Didn&#x27;t check whether the linked live demo endpoints still respond.</p>

</details>

<h3>FHIRBase — remove</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -135,7 +135,6 @@
   * [Clinical Meteor project](https://github.com/clinical-meteor) - Meteor for FDA, HIPAA, and HL7 compliant applications.
   * [Clinical Quality Language](https://github.com/cqframework/clinical_quality_language) - Clinical Quality Language is a HL7 standard for the expression of clinical knowledge.
   * [CyclOps](https://github.com/VectorInstitute/cyclops) - Framework for healthcare ML implementation.
-  * [FHIRBase](https://fhirbase.github.io) - Storage based on the FHIR Standard.
   * [FHIR Proxy](https://github.com/microsoft/fhir-proxy) - secure application that acts as an intermediary in the transfer of FHIR data to and from Azure API.
   * [FHIR Works on AWS](https://github.com/awslabs/fhir-works-on-aws-deployment) - FHIR Works on AWS deployment.
   * [FHIR Server for Azure](https://github.com/Microsoft/fhir-server) - A .NET Core implementation of the FHIR standard.
```

<details>
<summary>Evidence and limitations</summary>

<p>The listed URL (fhirbase.github.io) now does a meta-refresh to health-samurai.io/fhirbase, which redirects to Health Samurai&#x27;s commercial Aidbox FHIR server page. The link no longer presents FHIRBase. The official fhirbase/fhirbase README has a Status section saying &#x27;this project is frozen untill new hero will support it. Most of ideas from fhirbase is moved and developed in Aidbox FHIR Platform&#x27;. The last commit was in February 2022. Aidbox is a commercial product, not an open-source successor, so it can&#x27;t replace the entry here. Recommend raising removal in an issue, as the contribution rules require.</p>

<p>https://fhirbase.github.io/ — The page body is &#x27;Redirecting to a new Fhirbase Homepage...&#x27; with a meta refresh to https://health-samurai.io/fhirbase/.</p>

<p>https://health-samurai.io/fhirbase/ — Final URL is https://www.health-samurai.io/fhir-server, an Aidbox product page (&#x27;Free FHIR Server for Dev, Enterprise-Ready | Aidbox&#x27;). Nothing on it describes FHIRBase.</p>

<p>https://raw.githubusercontent.com/fhirbase/fhirbase/master/README.md — Status section: &#x27;this project is frozen untill new hero will support it. Most of ideas from fhirbase is moved and developed in Aidbox FHIR Platform&#x27;.</p>

<p>https://github.com/fhirbase/fhirbase/commits/master.atom — Latest commit on master is dated 2022-02-06. The repo is not archived.</p>

<p>Caveats: An alternative is to repoint the entry to https://github.com/fhirbase/fhirbase if the maintainer wants to keep historical resources. The frozen status conflicts with the &#x27;not abandoned&#x27; rule, though.</p>

</details>

<h3>FHIR Proxy — replace</h3>

<p>0 proposed change(s); 1 held for unresolved questions.</p>

<details>
<summary>Evidence and limitations</summary>

<p>microsoft/fhir-proxy is archived. Its README says that as of April 19, 2023 it is &#x27;no longer being developed or maintained&#x27; and explicitly recommends the &#x27;new Azure Health Data Services Toolkit&#x27;. That toolkit is active (commit 2026-09-16) and is a .NET 8 toolkit for building custom operations that change the behavior of the Azure Health Data Services FHIR service. The proxy&#x27;s pre/post-processing role fits this description. It is an officially documented successor, but the maintainer should check category fit.</p>

<p>https://raw.githubusercontent.com/microsoft/fhir-proxy/main/README.md — &#x27;As of April 19, 2023, this repository is no longer being developed or maintained. We recommend that you use the new Azure Health Data Services Toolkit&#x27; (links to github.com/microsoft/azure-health-data-services-toolkit).</p>

<p>https://raw.githubusercontent.com/microsoft/azure-health-data-services-toolkit/main/README.md — &#x27;helps you extend the functionality of Azure Health Data Services by providing a consistent toolset to build custom operations to modify the core service behavior&#x27;. Ships as NuGet packages (.NET 8). Its FHIR use cases include unsupported operations and organization-specific operations.</p>

<p>https://github.com/microsoft/azure-health-data-services-toolkit/commits/main.atom — Latest commit on main is dated 2026-09-16. The repo page shows no archive banner.</p>

<p>Blocking questions: The successor is a developer toolkit (libraries plus samples), not a ready-to-deploy secure proxy. A maintainer should confirm it suits this list and meets the &#x27;reasonably recognized and adopted&#x27; rule. Otherwise, removing the entry via an issue is the alternative.</p>

<p>Caveats: Didn&#x27;t run the toolkit.; Didn&#x27;t verify the toolkit&#x27;s license text, though Microsoft open-source repos are typically MIT.</p>

</details>

<h3>FHIR Works on AWS — remove</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -137,7 +137,6 @@
   * [CyclOps](https://github.com/VectorInstitute/cyclops) - Framework for healthcare ML implementation.
   * [FHIRBase](https://fhirbase.github.io) - Storage based on the FHIR Standard.
   * [FHIR Proxy](https://github.com/microsoft/fhir-proxy) - secure application that acts as an intermediary in the transfer of FHIR data to and from Azure API.
-  * [FHIR Works on AWS](https://github.com/awslabs/fhir-works-on-aws-deployment) - FHIR Works on AWS deployment.
   * [FHIR Server for Azure](https://github.com/Microsoft/fhir-server) - A .NET Core implementation of the FHIR standard.
   * [HAPI FHIR JPA Server Starter](https://github.com/hapifhir/hapi-fhir-jpaserver-starter) - Ready-to-deploy FHIR server built on HAPI FHIR.
   * [Helios FHIR Server](https://github.com/HeliosSoftware/hfs) - FHIR server written in Rust, optimized for clinical analytics workloads.
```

<details>
<summary>Evidence and limitations</summary>

<p>The listed repo is archived, and its README says it migrated to aws-solutions/fhir-works-on-aws. That destination is also archived (Jan 31, 2024), and its README declares End of Life: &#x27;FHIR Works on AWS has reached End of Life… will no longer receive any new feature updates, bug fixes or security updates from AWS.&#x27; AWS&#x27;s migration guidance doesn&#x27;t name an open-source successor. This conflicts with the &#x27;not abandoned/discontinued&#x27; rule. Recommend raising removal in an issue.</p>

<p>https://raw.githubusercontent.com/awslabs/fhir-works-on-aws-deployment/mainline/README.md — &#x27;This GitHub repository has been migrated. You can now find FHIR Works on AWS at https://github.com/aws-solutions/fhir-works-on-aws.&#x27;</p>

<p>https://raw.githubusercontent.com/aws-solutions/fhir-works-on-aws/main/README.md — &#x27;# End of Life — FHIR Works on AWS has reached End of Life. This repository will be archived and set as read only.&#x27; The EOL date is January 31, 2024, with no further feature, bug or security updates after that.</p>

<p>https://github.com/aws-solutions/fhir-works-on-aws — &#x27;This repository was archived by the owner on Jan 31, 2024&#x27;.</p>

<p>Caveats: Didn&#x27;t read the full &#x27;Where should I migrate to?&#x27; section. It appears to point to AWS managed services, which wouldn&#x27;t count as an open-source successor.</p>

</details>

<h3>Intervention Engine FHIR Server — remove</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -142,7 +142,6 @@
   * [HAPI FHIR JPA Server Starter](https://github.com/hapifhir/hapi-fhir-jpaserver-starter) - Ready-to-deploy FHIR server built on HAPI FHIR.
   * [Helios FHIR Server](https://github.com/HeliosSoftware/hfs) - FHIR server written in Rust, optimized for clinical analytics workloads.
   * [Inferno](https://inferno-framework.github.io) - providing testing tools for the FHIR
-  * [Intervention Engine FHIR Server](https://github.com/intervention-engine/fhir) - Generic FHIR server implementation in GoLang.
   * [LinuxForHealth FHIR Server](https://github.com/LinuxForHealth/FHIR) - Modular Java implementation of version 4 of the HL7 FHIR specification.
   * [Medblocks UI](https://github.com/medblocks/medblocks-ui) - Web Components for rapid development of openEHR and FHIR systems.
   * [Opal](https://github.com/openhealthcare/opal) - Framework for building clinical applications.
```

<details>
<summary>Evidence and limitations</summary>

<p>The README says: &#x27;This project is not under active development. Others have forked and continue work on the code.&#x27; The last commit was in August 2018. The default branch targets FHIR DSTU2, and the README calls it a library that &#x27;is not a complete implementation of FHIR&#x27;. The only fork listed (eug48/fhir) is a community fork last updated July 2020, not an officially maintained successor. This conflicts with the &#x27;not abandoned&#x27; rule. Recommend raising removal in an issue.</p>

<p>https://raw.githubusercontent.com/intervention-engine/fhir/master/README.md — &#x27;NOTE: This project is not under active development. Others have forked and continue work on the code.&#x27; Provides &#x27;HL7 FHIR DSTU2 models and server components implemented in Go&#x27;. Older STU3 variants live on branches (stu3_mar2017 and others). &#x27;This is a library… not a complete implementation of FHIR.&#x27;</p>

<p>https://github.com/intervention-engine/fhir/commits/master.atom — Latest commit on master is dated 2018-08-27.</p>

<p>https://github.com/eug48/fhir/commits/master.atom — The listed &#x27;active fork&#x27; was last committed to on 2020-07-13, so it&#x27;s also not maintained.</p>

<p>Caveats: Didn&#x27;t check the commit dates of the STU3 legacy branches. Their existence says nothing about maintenance.</p>

</details>

<h3>Clinical Meteor project — replace</h3>

<p>0 proposed change(s); 1 held for unresolved questions.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The packet snapshot was unavailable, so this relies on direct page fetches. The github.com/clinical-meteor org is titled &#x27;clinical-meteor (deprecated)&#x27; and its profile says: &#x27;This repository is now in read-only mode. Use at your own risk; as it is unsupported. All new development is at node-on-fhir&#x27;. Its repos show as &#x27;Public archive&#x27;. The org itself names the successor, which is the github.com/node-on-fhir org (&#x27;Adding HIPAA security, FDA precertification, and EHR interoperability to Node/Javascript software&#x27;). The successor is active: node-on-fhir/core (&#x27;Meteor v3 rewrite of Node on FHIR&#x27;) was committed to on 2026-11-01.</p>

<p>https://github.com/clinical-meteor — Org title &#x27;clinical-meteor (deprecated)&#x27;. Description: &#x27;This repository is now in read-only mode. Use at your own risk; as it is unsupported. All new development is at node-on-fhir&#x27; (links to https://github.com/node-on-fhir/). Listed repos are marked &#x27;Public archive&#x27;.</p>

<p>https://github.com/node-on-fhir — Org &#x27;Node on FHIR&#x27;. Meta description: &#x27;Adding HIPAA security, FDA precertification, and EHR interoperability to Node/Javascript software.&#x27; Repos include core (&#x27;Meteor v3 rewrite of Node on FHIR&#x27;), ohif-fhir-viewer and radiology-workflow, updated through Nov 2026.</p>

<p>https://github.com/node-on-fhir/core/commits/main.atom — Latest commit on main is dated 2026-11-01.</p>

<p>Blocking questions: Unverified whether Node on FHIR meets the &#x27;reasonably recognized and adopted&#x27; and GA-quality rules. Its core README couldn&#x27;t be read, so production readiness and license are unconfirmed.</p>

<p>Caveats: The node-on-fhir/core README couldn&#x27;t be fetched from the raw endpoint (404 on the main/master/develop paths), so capability claims rely on the org and repo descriptions.; Didn&#x27;t verify licensing of the node-on-fhir repos.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Spark — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -147,7 +147,7 @@
   * [Medblocks UI](https://github.com/medblocks/medblocks-ui) - Web Components for rapid development of openEHR and FHIR systems.
   * [Opal](https://github.com/openhealthcare/opal) - Framework for building clinical applications.
   * [ResearchKit](https://github.com/ResearchKit/ResearchKit) - Software framework that makes it easy to create apps for medical research or for other research projects.
-  * [Spark](https://github.com/FirelyTeam/spark) - Public domain FHIR server developed in C#.
+  * [Spark](https://github.com/FirelyTeam/spark) - Open-source FHIR server developed in C#.
   * [Spezi](https://github.com/StanfordSpezi/Spezi) - Stanford framework for building interoperable digital health apps on Apple platforms.
   * [Sushi](https://github.com/FHIR/sushi) - a reference implementation command-line interpreter/compiler for FHIR
   * [Swift-SMART](https://github.com/smart-on-fhir/Swift-SMART) - Swift SMART on FHIR framework for iOS and OS X.
```

<details>
<summary>Evidence and limitations</summary>

<p>The identity and fit are fine: FirelyTeam/spark is an active C# FHIR server. The &quot;Public domain&quot; claim is wrong, though. The README now says &quot;open-source FHIR server developed in C#&quot;, and GitHub reports a BSD-3-Clause license, which is not public domain.</p>

<p>https://raw.githubusercontent.com/FirelyTeam/spark/master/README.md — &quot;Spark is an open-source FHIR server developed in C#, initially built by Firely. Further development and maintenance is now done by Incendi.&quot; Supports R4/R4B/R5/R6 and STU3.</p>

<p>https://github.com/FirelyTeam/spark — GitHub API: archived=false, last push 2026-11-06, license BSD-3-Clause, description &quot;Firely and Incendi&#x27;s open source FHIR server&quot;.</p>

<p>Caveats: I took the license from GitHub&#x27;s detected SPDX field and did not read the LICENSE file directly.</p>

</details>

<h3>Sushi — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -149,7 +149,7 @@
   * [ResearchKit](https://github.com/ResearchKit/ResearchKit) - Software framework that makes it easy to create apps for medical research or for other research projects.
   * [Spark](https://github.com/FirelyTeam/spark) - Public domain FHIR server developed in C#.
   * [Spezi](https://github.com/StanfordSpezi/Spezi) - Stanford framework for building interoperable digital health apps on Apple platforms.
-  * [Sushi](https://github.com/FHIR/sushi) - a reference implementation command-line interpreter/compiler for FHIR
+  * [Sushi](https://github.com/FHIR/sushi) - a reference implementation command-line interpreter/compiler for FHIR Shorthand (FSH).
   * [Swift-SMART](https://github.com/smart-on-fhir/Swift-SMART) - Swift SMART on FHIR framework for iOS and OS X.
 
 ### Libraries
```

<details>
<summary>Evidence and limitations</summary>

<p>FHIR/sushi is active and Apache-2.0 licensed. The description is truncated in a way that changes its meaning: SUSHI is a compiler for FHIR Shorthand (FSH), the language used to author FHIR implementation guides, not for &quot;FHIR&quot; itself. The fix is to restore the official wording.</p>

<p>https://raw.githubusercontent.com/FHIR/sushi/master/README.md — &quot;SUSHI ... is a reference implementation command-line interpreter/compiler for FHIR Shorthand (FSH).&quot; Supports creating IGs for R4, R4B and R5; maintained by the HL7 community.</p>

<p>https://github.com/FHIR/sushi — GitHub API: archived=false, last push 2026-11-09, Apache-2.0.</p>

<p>Caveats: It is debatable whether a compiler belongs under Frameworks rather than a tools section, but that is outside the scope of this edit.</p>

</details>

<h3>Android FHIR SDK — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -153,7 +153,7 @@
   * [Swift-SMART](https://github.com/smart-on-fhir/Swift-SMART) - Swift SMART on FHIR framework for iOS and OS X.
 
 ### Libraries
-  * [Android FHIR SDK](https://github.com/google/android-fhir) - The Android FHIR SDK 
+  * [Android FHIR SDK](https://github.com/ohs-foundation/android-fhir) - The Android FHIR SDK 
   * [Archie](https://github.com/openehr/archie) - OpenEHR Library written in Java.
   * [Asymmetrik FHIR API Server](https://github.com/bluehalo/node-fhir-server-core) - A secure REST implementation for the HL7 FHIR Specification.
   * [Datamol](https://github.com/datamol-io/datamol) - Molecular Manipulation Made Easy. A light Python wrapper build on top of RDKit.
```

<details>
<summary>Evidence and limitations</summary>

<p>github.com/google/android-fhir now returns a 301 redirect to github.com/ohs-foundation/android-fhir. The GitHub API also resolves the repository to ohs-foundation/android-fhir, which is consistent with an official transfer. The project is active, Apache-2.0 licensed, and still the Android FHIR SDK, so the URL should be updated to the canonical location.</p>

<p>https://github.com/google/android-fhir — HTTP 301 → https://github.com/ohs-foundation/android-fhir (200).</p>

<p>https://raw.githubusercontent.com/ohs-foundation/android-fhir/master/README.md — &quot;The Android FHIR SDK is a set of Kotlin libraries for building offline-capable, mobile-first healthcare applications using the HL7® FHIR® standard on Android.&quot;</p>

<p>https://github.com/ohs-foundation/android-fhir — GitHub API full_name ohs-foundation/android-fhir, archived=false, last push 2026-03-25, Apache-2.0.</p>

<p>Caveats: The README badges and docs link still point to google/android-fhir and google.github.io paths.; Optionally, the near-empty description could be expanded using the README sentence; it is not wrong as written.</p>

</details>

<h3>Asymmetrik FHIR API Server — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -155,7 +155,7 @@
 ### Libraries
   * [Android FHIR SDK](https://github.com/google/android-fhir) - The Android FHIR SDK 
   * [Archie](https://github.com/openehr/archie) - OpenEHR Library written in Java.
-  * [Asymmetrik FHIR API Server](https://github.com/bluehalo/node-fhir-server-core) - A secure REST implementation for the HL7 FHIR Specification.
+  * [BlueHalo FHIR API Server](https://github.com/bluehalo/node-fhir-server-core) - A secure REST implementation for the HL7 FHIR Specification.
   * [Datamol](https://github.com/datamol-io/datamol) - Molecular Manipulation Made Easy. A light Python wrapper build on top of RDKit.
   * [dcmjs](https://github.com/dcmjs-org/dcmjs) - JavaScript implementation of DICOM manipulation.
   * [DCMTK](https://dicom.offis.de/dcmtk.php.en) - DICOM Toolkit.
```

<details>
<summary>Evidence and limitations</summary>

<p>The URL and description are correct: the README states &quot;A Secure Rest implementation for the HL7 FHIR Specification&quot; and the project is MIT-licensed. The display name is outdated. The project now calls itself the Bluehalo/BlueHalo FHIR API Server, and Asymmetrik no longer appears in its README branding.</p>

<p>https://raw.githubusercontent.com/bluehalo/node-fhir-server-core/master/README.md — Title &quot;# Bluehalo FHIR API Server&quot;; &quot;A Secure Rest implementation for the HL7 FHIR Specification&quot;; body uses &quot;The BlueHalo Extensible Server Framework for Healthcare&quot;.</p>

<p>https://github.com/bluehalo/node-fhir-server-core — GitHub API: bluehalo/node-fhir-server-core, archived=false, last push 2026-02-15, MIT; repo description still links an Asymmetrik wiki URL.</p>

<p>Caveats: The README is inconsistent about capitalization (&quot;Bluehalo&quot; in the heading, &quot;BlueHalo&quot; in the body). I chose the company&#x27;s styling, BlueHalo.; The README still lists DSTU2/STU3/R4 support and references Travis CI, so its documentation may be stale.</p>

</details>

<h3>DCMTK — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -158,7 +158,7 @@
   * [Asymmetrik FHIR API Server](https://github.com/bluehalo/node-fhir-server-core) - A secure REST implementation for the HL7 FHIR Specification.
   * [Datamol](https://github.com/datamol-io/datamol) - Molecular Manipulation Made Easy. A light Python wrapper build on top of RDKit.
   * [dcmjs](https://github.com/dcmjs-org/dcmjs) - JavaScript implementation of DICOM manipulation.
-  * [DCMTK](https://dicom.offis.de/dcmtk.php.en) - DICOM Toolkit.
+  * [DCMTK](https://dicom.offis.de/en/dcmtk/) - DICOM Toolkit.
   * [deid](https://github.com/pydicom/deid) - De-identification of DICOM images in Python.
   * [dicom](https://github.com/suyashkumar/dicom) - High Performance DICOM Medical Image Parser in GoLang.
   * [dicom-rs](https://github.com/Enet4/dicom-rs) - Rust implementation of the DICOM standard.
```

<details>
<summary>Evidence and limitations</summary>

<p>The listed URL https://dicom.offis.de/dcmtk.php.en returns a 301 permanent redirect to https://dicom.offis.de/en/dcmtk/ on the same official OFFIS domain. The URL should be updated to that destination. DCMTK itself is active, as the official GitHub mirror shows, and is still a DICOM toolkit.</p>

<p>https://dicom.offis.de/dcmtk.php.en — HTTP 301 → https://dicom.offis.de/en/dcmtk/, which then 302s to a BunkerWeb bot-challenge page (403 without JavaScript).</p>

<p>https://github.com/DCMTK/dcmtk — &quot;Official DCMTK Github Mirror&quot;, homepage git.dcmtk.org, last push 2026-11-07.</p>

<p>https://raw.githubusercontent.com/DCMTK/dcmtk/master/README — &quot;This DICOM toolkit (DCMTK) package consists of source code ... libraries and applications implementing part of the DICOM/MEDICOM Standard.&quot;</p>

<p>Caveats: A JavaScript bot challenge blocked me from reading the destination page&#x27;s body. I verified its identity only from the same-domain 301 redirect and the official mirror.; The old URL still works through the redirect, so this change is low priority.</p>

</details>

<h3>Fellow Oak DICOM — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -164,7 +164,7 @@
   * [dicom-rs](https://github.com/Enet4/dicom-rs) - Rust implementation of the DICOM standard.
   * [ehrapy](https://github.com/theislab/ehrapy/) - Electronic Health Record analysis in Python.
   * [Evil-DICOM](https://github.com/rexcardan/Evil-DICOM) - C# DICOM Library.
-  * [Fellow Oak DICOM](https://github.com/fo-dicom/fo-dicom) - DICOM for .NET, .NET Core, Universal Windows, Android, iOS, Mono, and Unity.
+  * [Fellow Oak DICOM](https://github.com/fo-dicom/fo-dicom) - DICOM library for .NET.
   * [FHIRKit Client](https://github.com/Vermonster/fhir-kit-client) - Node FHIR client library.
   * [FHIRModels](https://github.com/apple/FHIRModels) - FHIRModels is a Swift library for FHIR resource data models.
   * [FHIR .NET API](https://github.com/FirelyTeam/firely-net-sdk) - The official .NET API for HL7 FHIR.
```

<details>
<summary>Evidence and limitations</summary>

<p>fo-dicom is active and still a DICOM library for .NET. The platform list in the description is outdated. The README now says it &quot;officially supports&quot; only .NET 8.0, 9.0 and 10.0, and the core csproj targets only net8.0;net9.0;net10.0. The listed Universal Windows, Mono and Unity targets are no longer documented as supported.</p>

<p>https://raw.githubusercontent.com/fo-dicom/fo-dicom/development/README.md — &quot;Fellow Oak DICOM officially supports the following runtimes: .NET 8.0, .NET 9.0, .NET 10.0. Other runtimes may work...&quot;; MS-PL license.</p>

<p>https://raw.githubusercontent.com/fo-dicom/fo-dicom/development/FO-DICOM.Core/FO-DICOM.Core.csproj — &lt;TargetFrameworks&gt;net8.0;net9.0;net10.0&lt;/TargetFrameworks&gt; (no netstandard target).</p>

<p>https://github.com/fo-dicom/fo-dicom — GitHub API: archived=false, last push 2026-11-02; repo description still shows the old platform list.</p>

<p>Caveats: The README notes that other runtimes may work, and a single sentence still mentions Xamarin platforms. The proposed wording avoids volatile platform lists.; Older fo-dicom 4.x releases did support the listed platforms; I did not check whether they are still maintained.</p>

</details>

<h3>FHIR .NET API — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -167,7 +167,7 @@
   * [Fellow Oak DICOM](https://github.com/fo-dicom/fo-dicom) - DICOM for .NET, .NET Core, Universal Windows, Android, iOS, Mono, and Unity.
   * [FHIRKit Client](https://github.com/Vermonster/fhir-kit-client) - Node FHIR client library.
   * [FHIRModels](https://github.com/apple/FHIRModels) - FHIRModels is a Swift library for FHIR resource data models.
-  * [FHIR .NET API](https://github.com/FirelyTeam/firely-net-sdk) - The official .NET API for HL7 FHIR.
+  * [Firely .NET SDK](https://github.com/FirelyTeam/firely-net-sdk) - Firely's official .NET SDK for HL7 FHIR.
   * [fhir.js](https://github.com/FHIR/fhir.js) - JavaScript client for FHIR.
   * [fhir.resources](https://github.com/nazrulworld/fhir.resources) - Pydantic-based FHIR resource models for Python.
   * [fhir-py](https://github.com/beda-software/fhir-py) - Async and sync FHIR client for Python.
```

<details>
<summary>Evidence and limitations</summary>

<p>Repository resolves to FirelyTeam/firely-net-sdk and remains active (README covers STU3/R4/R4B/R5 support, 6.0 release branch). The project now identifies itself as the &#x27;Firely .NET SDK&#x27; and &#x27;Firely&#x27;s official support SDK&#x27;, not &#x27;FHIR .NET API&#x27;. The current wording &#x27;The official .NET API for HL7 FHIR&#x27; can be read as an HL7-official claim. Suggest updating the name to match the official identity and making clear it is Firely&#x27;s official SDK. The URL is unchanged.</p>

<p>https://github.com/FirelyTeam/firely-net-sdk — HTTP 200, no redirect, not archived. Repo description: &#x27;The official Firely .NET SDK for HL7 FHIR&#x27;.</p>

<p>https://raw.githubusercontent.com/FirelyTeam/firely-net-sdk/develop/README.md — &#x27;This is Firely&#x27;s official support SDK for working with HL7 FHIR on the Microsoft .NET (dotnet) platform.&#x27; Lists POCO models, XML/JSON parsers, REST client, validation and FhirPath. STU3, R4, R4B and R5 are all fully supported through NuGet Hl7.Fhir.* packages.</p>

<p>Caveats: Did not build or run the SDK.; The renaming is minor and the old name is still recognizable, so this is optional wording cleanup at maintainer discretion.</p>

</details>

<h3>nhs-number — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -182,7 +182,7 @@
   * [MITK](https://www.mitk.org/) - The Medical Imaging Interaction Toolkit.
   * [nHapi](https://github.com/nHapiNET/nHapi) - .NET port of the HAPI HL7 v2 library.
   * [nhs-number](https://github.com/wardle/nhs-number) - A Clojure/Script library providing validation, formatting and generation of UK NHS Numbers
-  * [nhs-number](https://github.com/uk-fci/nhs-number) - Python package to provide utilities for NHS Numbers, including validity checks, normalisation, and generation.
+  * [nhs-number](https://github.com/ohtf/nhs-number-py) - Python package to provide utilities for NHS Numbers, including validity checks, normalisation, and generation.
   * [Node HL7](https://github.com/MatthewVita/node-hl7-complete) - Node module that is bridged with the Java Hapi HL7 library.
   * [Node-hl7-parser](https://github.com/RedoxEngine/redox-hl7-v2) - Open source version of Redox's HL7 v2 to schema-fied JSON parser.
   * [php-fhir](https://github.com/dcarbone/php-fhir) - Tools for creating PHP classes from the HL7 FHIR Specification.
```

<details>
<summary>Evidence and limitations</summary>

<p>https://github.com/uk-fci/nhs-number redirects to https://github.com/ohtf/nhs-number-py, so the repo has moved to the Open Health Technology Foundation org. The README there keeps the same package name (nhs-number) and the same description, so only the URL needs updating.</p>

<p>https://github.com/uk-fci/nhs-number — Final URL after redirects is https://github.com/ohtf/nhs-number-py (HTTP 200), with the same description text.</p>

<p>https://raw.githubusercontent.com/ohtf/nhs-number-py/main/README.md — Heading &#x27;# nhs-number&#x27;. &#x27;Python package to provide utilities for NHS Numbers, including validity checks, normalisation, and generation.&#x27; PyPI badges for nhs-number.</p>

<p>https://github.com/ohtf — Org description: &#x27;Global, independent foundation to curate open source health technology projects - Open Health Technology Foundation&#x27;.</p>

<p>Caveats: Did not inspect the transfer history beyond the GitHub redirect.</p>

</details>

<h3>Python 835 Parser — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -190,7 +190,7 @@
   * [pynetdicom](https://github.com/pydicom/pynetdicom) - A Python implementation of the DICOM networking protocol.
   * [Python HL7](https://github.com/johnpaulett/python-hl7) - Simple library for parsing messages of HL7 version 2.x into Python objects.
   * [Python SMART on FHIR client](https://github.com/smart-on-fhir/client-py) - Flexible Python client for FHIR servers supporting the SMART on FHIR protocol.
-  * [Python 835 Parser](https://github.com/keironstoddart/edi-835-parser) - A simple-to-use Python interface to EDI 835 Health Care Claim Payment and Remittance Advice files.
+  * [Python 835 Parser](https://github.com/keiron-stoddart/edi-835-parser) - A simple-to-use Python interface to EDI 835 Health Care Claim Payment and Remittance Advice files.
   * [Ruby FHIR](https://github.com/fhir-crucible/fhir_client) - FHIR client implementation in Ruby.
   * [Ruby HL7](https://github.com/segfault/ruby-hl7) - Ruby HL7 library.
   * [Rust FHIR](https://github.com/itsbalamurali/rust-fhir) - Rust SDK for HL7 FHIR
```

<details>
<summary>Evidence and limitations</summary>

<p>The listed URL redirects: github.com/keironstoddart/edi-835-parser now lands on github.com/keiron-stoddart/edi-835-parser. That is a GitHub owner rename, and the packet snapshot also resolves the repository as keiron-stoddart/edi-835-parser. The description still matches the README word for word, so only the URL needs correcting.</p>

<p>https://github.com/keironstoddart/edi-835-parser — Returns 301 and ends at https://github.com/keiron-stoddart/edi-835-parser (200).</p>

<p>https://raw.githubusercontent.com/keiron-stoddart/edi-835-parser/HEAD/README.md — &#x27;This package provides a simple-to-use Python interface to EDI 835 Health Care Claim Payment and Remittance Advice files.&#x27; Install with pip install edi-835-parser. The README badges still link to the old keironstoddart owner path.</p>

<p>https://raw.githubusercontent.com/keiron-stoddart/edi-835-parser/HEAD/pyproject.toml — name &#x27;edi-835-parser&#x27;, version 1.8.0, license MIT, author Keiron Stoddart.</p>

<p>https://github.com/keiron-stoddart/edi-835-parser/commits.atom — Latest commit 2024-06-03. The latest PyPI upload is also from 2024-06-03. The repository is not archived.</p>

<p>Caveats: The last activity was mid-2024. That alone does not show the project is abandoned, and nothing official says it is discontinued.</p>

</details>

<h3>Ruby FHIR — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -191,7 +191,7 @@
   * [Python HL7](https://github.com/johnpaulett/python-hl7) - Simple library for parsing messages of HL7 version 2.x into Python objects.
   * [Python SMART on FHIR client](https://github.com/smart-on-fhir/client-py) - Flexible Python client for FHIR servers supporting the SMART on FHIR protocol.
   * [Python 835 Parser](https://github.com/keironstoddart/edi-835-parser) - A simple-to-use Python interface to EDI 835 Health Care Claim Payment and Remittance Advice files.
-  * [Ruby FHIR](https://github.com/fhir-crucible/fhir_client) - FHIR client implementation in Ruby.
+  * [Ruby FHIR](https://github.com/inferno-framework/fhir_client) - FHIR client implementation in Ruby.
   * [Ruby HL7](https://github.com/segfault/ruby-hl7) - Ruby HL7 library.
   * [Rust FHIR](https://github.com/itsbalamurali/rust-fhir) - Rust SDK for HL7 FHIR
   * [sct](https://github.com/pacharanero/sct) - File-based SNOMED-CT toolset built in Rust.
```

<details>
<summary>Evidence and limitations</summary>

<p>The listed URL redirects: github.com/fhir-crucible/fhir_client now lands on github.com/inferno-framework/fhir_client, which indicates a GitHub repository transfer. The packet snapshot also resolves to inferno-framework/fhir_client. The project is actively released, and &#x27;FHIR client implementation in Ruby&#x27; remains accurate, so only the URL needs correcting.</p>

<p>https://github.com/fhir-crucible/fhir_client — Redirects to https://github.com/inferno-framework/fhir_client (200).</p>

<p>https://raw.githubusercontent.com/inferno-framework/fhir_client/HEAD/README.md — &#x27;Ruby FHIR client.&#x27; Supports FHIR R5, R4B, R4, STU3 and DSTU2; CRUD, search, operations and OAuth2.</p>

<p>https://rubygems.org/api/v1/gems/fhir_client.json — fhir_client 6.2.0 was released 2026-04-30 under Apache-2.0. The gem homepage metadata still says github.com/fhir-crucible/fhir_client.</p>

<p>https://github.com/inferno-framework/fhir_client/commits.atom — Latest commit 2026-04-30.</p>

<p>Caveats: The gemspec and rubygems homepage still point to the old fhir-crucible URL, which redirects. The GitHub redirect is the evidence of the current canonical owner.</p>

</details>

<h3>Ruby HL7 — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -192,7 +192,7 @@
   * [Python SMART on FHIR client](https://github.com/smart-on-fhir/client-py) - Flexible Python client for FHIR servers supporting the SMART on FHIR protocol.
   * [Python 835 Parser](https://github.com/keironstoddart/edi-835-parser) - A simple-to-use Python interface to EDI 835 Health Care Claim Payment and Remittance Advice files.
   * [Ruby FHIR](https://github.com/fhir-crucible/fhir_client) - FHIR client implementation in Ruby.
-  * [Ruby HL7](https://github.com/segfault/ruby-hl7) - Ruby HL7 library.
+  * [Ruby HL7](https://github.com/ruby-hl7/ruby-hl7) - Ruby HL7 library.
   * [Rust FHIR](https://github.com/itsbalamurali/rust-fhir) - Rust SDK for HL7 FHIR
   * [sct](https://github.com/pacharanero/sct) - File-based SNOMED-CT toolset built in Rust.
   * [Scanpy](https://scanpy.readthedocs.io/) - Single-cell RNA-seq analysis library in Python.
```

<details>
<summary>Evidence and limitations</summary>

<p>segfault/ruby-hl7 still resolves, but its last commit was 2013-07-12 and its README links only to dead 2009-era RubyForge and trac resources. The official ruby-hl7 gem (1.4.0, released 2025-01, same author Mark Guzman) names github.com/ruby-hl7/ruby-hl7 as its homepage and source. That repository&#x27;s gemspec and README say the same, and it lists current maintainers. This is the same library&#x27;s current canonical home, not a competitor. The description &#x27;Ruby HL7 library.&#x27; still holds.</p>

<p>https://github.com/segfault/ruby-hl7/commits.atom — Latest commit 2013-07-12. The repo is not archived and does not redirect.</p>

<p>https://raw.githubusercontent.com/segfault/ruby-hl7/HEAD/README — Old README pointing to trac.hasno.info, Subversion and rubyforge.org; &#x27;Copyright (c) 2006-2009 Mark Guzman&#x27;.</p>

<p>https://rubygems.org/api/v1/gems/ruby-hl7.json — ruby-hl7 1.4.0 was released 2025-01-07, author Mark Guzman. homepage_uri and source_code_uri are https://github.com/ruby-hl7/ruby-hl7.</p>

<p>https://raw.githubusercontent.com/ruby-hl7/ruby-hl7/HEAD/README.md — &#x27;Ruby HL7 Library — A simple way to parse and create HL7 2.x messages with Ruby.&#x27; Git: https://github.com/ruby-hl7/ruby-hl7.git. It lists maintainers (trisano, onemedical, LucasMontorio).</p>

<p>https://github.com/ruby-hl7/ruby-hl7/commits.atom — Latest commit 2025-01-27.</p>

<p>Caveats: Whether ruby-hl7/ruby-hl7 is a GitHub fork of segfault/ruby-hl7 could not be confirmed (API rate-limited). The identity link rests on rubygems metadata and the shared author and gem name.; segfault/ruby-hl7 itself states nothing about having moved.</p>

</details>

<h3>Scanpy — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -195,7 +195,7 @@
   * [Ruby HL7](https://github.com/segfault/ruby-hl7) - Ruby HL7 library.
   * [Rust FHIR](https://github.com/itsbalamurali/rust-fhir) - Rust SDK for HL7 FHIR
   * [sct](https://github.com/pacharanero/sct) - File-based SNOMED-CT toolset built in Rust.
-  * [Scanpy](https://scanpy.readthedocs.io/) - Single-cell RNA-seq analysis library in Python.
+  * [Scanpy](https://scanpy.scverse.org/) - Single-cell RNA-seq analysis library in Python.
   * [SMART on FHIR JavaScript client](https://github.com/smart-on-fhir/client-js) - JavaScript client for SMART on FHIR apps.
   * [TorchXRayVision](https://github.com/mlmed/torchxrayvision) - A library for chest X-ray datasets and models. Including pre-trained models.
 
```

<details>
<summary>Evidence and limitations</summary>

<p>https://scanpy.readthedocs.io/ returns a 302 redirect to https://scanpy.scverse.org/en/stable/. The project&#x27;s own README calls https://scanpy.scverse.org/ its documentation home, so the canonical host has moved to scverse.org. The description still fits: Scanpy is a toolkit for analyzing single-cell gene expression data in Python.</p>

<p>https://scanpy.readthedocs.io/ — HTTP 302, Location: https://scanpy.scverse.org/en/stable/.</p>

<p>https://scanpy.scverse.org/en/stable/ — Page title &#x27;Scanpy – Single-Cell Analysis in Python&#x27;; &#x27;Scanpy is a scalable toolkit for analyzing single-cell gene expression data built jointly with anndata.&#x27;</p>

<p>https://raw.githubusercontent.com/scverse/scanpy/HEAD/README.md — Links documentation to https://scanpy.scverse.org/. Covers preprocessing, visualization, clustering, trajectory inference and differential expression. Part of scverse, NumFOCUS-sponsored.</p>

<p>Caveats: The rules discourage documentation links. The maintainer may prefer the source repo https://github.com/scverse/scanpy over the docs site; either is canonical for the project.; The proposed URL is the root of the redirect target; /en/stable/ is reached from there.</p>

</details>

<h3>SMART Pediatric Growth Chart — remove</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -206,7 +206,6 @@
   * [MedTimer](https://github.com/Futsch1/medTimer) - Medication reminder and tracking app for Android.
   * [OpenSRP FHIR Core](https://github.com/opensrp/fhircore) - Offline-capable Android app for community health workers, built on the Android FHIR SDK.
   * [RCPCH Digital Growth Charts](https://growth.rcpch.ac.uk) - Open source Digital Growth Charts platform with API, CLI, Python package, React chart components.
-  * [SMART Pediatric Growth Chart](https://github.com/smart-on-fhir/growth-chart-app) - Pediatric growth charts.
   * [Simple](https://github.com/simpledotorg/) - For clinicians to track patients with high blood pressure.
   * [SORMAS](https://github.com/SORMAS-Foundation/SORMAS-Project) - Surveillance, outbreak response management and analysis system.
 
```

<details>
<summary>Evidence and limitations</summary>

<p>The repository is archived, and its README now opens with &#x27;⚠️ This project is deprecated and is not actively maintained!&#x27;. That is affirmative official evidence of discontinuation, and the pinned rules require that code not be abandoned or discontinued. No successor is named in the README. Per the rules, removal should be proposed by opening an issue, not by a direct edit.</p>

<p>https://raw.githubusercontent.com/smart-on-fhir/growth-chart-app/HEAD/README.md — &#x27;## ⚠️ This project is deprecated and is not actively maintained!&#x27; No successor or replacement is mentioned.</p>

<p>https://github.com/smart-on-fhir/growth-chart-app — Resolves (200). The packet snapshot reports archived=true.</p>

<p>https://github.com/smart-on-fhir/growth-chart-app/commits.atom — Latest commit 2024-02-08.</p>

<p>Caveats: The code remains viewable as a historical reference.; RCPCH Digital Growth Charts (entry 208) is a separate project, not a documented successor.</p>

</details>

<h3>Zato — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -240,7 +240,7 @@
   * [Open Integration Engine](https://github.com/OpenIntegrationEngine/engine) - Community open source fork of Mirth Connect.
   * [OpenHIM](http://openhim.org/) - Health information mediator.
   * [OpenWearables](https://github.com/the-momentum/open-wearables) - Self-hosted platform to unify wearable health data through one AI-ready API.
-  * [Zato](https://zato.io/en/industry/healthcare/index.html) - A Python-based ESB and integration platform for healthcare interoperability, automation and orchestration.
+  * [Zato](https://zato.io/industry/healthcare/index.html) - A Python-based ESB and integration platform for healthcare interoperability, automation and orchestration.
 
 ### Hardware
   * [Gluco](https://github.com/nebulabio/gluco) - Glucometer.
```

<details>
<summary>Evidence and limitations</summary>

<p>The listed URL https://zato.io/en/industry/healthcare/index.html redirects to https://zato.io/industry/healthcare/index.html. The /en/ path is no longer canonical. The description still holds. The page calls Zato an open-source healthcare integration platform in Python with HL7, FHIR and EDI, and markets &#x27;ESB, API, AI and Cloud Integrations in Python&#x27;. The official GitHub repo zatosource/zato is active, so the only change needed is the URL.</p>

<p>https://zato.io/industry/healthcare/index.html — The listed /en/ URL resolves here with HTTP 200. The page title is &#x27;Health Care Interoperability Platform in Python | Zato&#x27;. It says &#x27;Connect clinical, administrative and financial systems through one open-source integration platform&#x27; and &#x27;ESB, API, AI and Cloud Integrations in Python&#x27;.</p>

<p>https://github.com/zatosource/zato — Not archived. The description is &#x27;ESB, SOA, REST, APIs and Cloud Integrations in Python&#x27;, and the main branch had commits on 2026-11-10.</p>

<p>Caveats: The old /en/ URL still works through the redirect, so this is a canonicalization fix, not a broken link.; I did not check whether the maintainer would rather link to the GitHub repo than the marketing page.</p>

</details>

<h3>Bcbio — remove</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -249,7 +249,6 @@
 
 ### Bioinformatics
   * [ADAM](https://github.com/bigdatagenomics/adam) - Genomics analysis platform.
-  * [Bcbio](https://github.com/bcbio/bcbio-nextgen) - Validated, scalable, community developed variant calling, RNA-seq and small RNA analysis.
   * [cBioPortal](https://github.com/cBioPortal/cbioportal) - Platform for exploring and visualizing cancer genomics data.
   * [FlashDeconv](https://github.com/cafferychen777/flashdeconv) - High-performance spatial transcriptomics deconvolution for cell type mapping in tissue samples.
   * [Galaxy](https://galaxyproject.org/) - Open web-based platform for data intensive biomedical research.
```

<details>
<summary>Evidence and limitations</summary>

<p>The project has officially announced its discontinuation. The bcbio-nextgen README links a &#x27;notice of discontinuation of this project&#x27; (08-16-2024). Issue #3749, opened by the core team, says maintenance is no longer sustainable. They planned to handle minor issues until the end of 2024 and then archive the repo, and they point users to Nextflow/nf-core pipelines. This conflicts with the rule that &#x27;Code must not be abandoned/discontinued&#x27;. nf-core is described as a community the team is joining, not a single successor to bcbio. It is a broad framework, and nf-core/sarek is already listed separately. So I recommend removal, not a replacement. Per the rules, this should go to a removal issue.</p>

<p>https://raw.githubusercontent.com/bcbio/bcbio-nextgen/master/README.md — The README says: &#x27;NOTE!!!! Please read the notice of discontinuation of this project - 08-16-2024&#x27;.</p>

<p>https://github.com/bcbio/bcbio-nextgen/issues/3749 — Issue &#x27;Discontinuation of bcbio-nextgen project&#x27; (Aug 16, 2024): &#x27;changes in personnel... have made it increasingly challenging to support and continue the development and maintenance of bcbio... after which, we will archive the bcbio-nextgen project on GitHub.&#x27; It recommends transitioning users to nf-core.</p>

<p>https://github.com/bcbio/bcbio-nextgen — Still not archived as of now. The last commit on master is from 2024-08-24, and the last release is v1.2.9 (Dec 2021).</p>

<p>Caveats: The repo has not been archived yet, despite the stated plan.; It may still have some historical or reproducibility value. The maintainer can weigh that in the removal discussion.</p>

</details>

<h3>cTAKES — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -265,7 +265,7 @@
 ### Data
   * [Atlas BI Library](https://github.com/atlas-bi/Library) The unified report library.
   * [Cedar](https://github.com/mitre/cedar) - Open source tool for testing the strength of Electronic Clinical Quality Measure.
-  * [cTAKES](https://ctakes.apache.org/) - Natural Language Processing System for extraction of information from Electronic Medical Record clinical free-text.
+  * [cTAKES](https://github.com/apache/ctakes) - Natural Language Processing System for extraction of information from Electronic Medical Record clinical free-text.
   * [DHIS2](https://github.com/dhis2/dhis2-core) - Health information management platform used by national health systems.
   * [EDS_NLP](https://github.com/aphp/edsnlp) - provides a set of spaCy components to extract information from clinical notes written in French
   * [eds-scikit](https://github.com/aphp/eds-scikit) - a tool to assist data scientists working on the AP-HP's Clinical Data Warehouse. It is specifically targeted for OMOP-standardized data. 
```

<details>
<summary>Evidence and limitations</summary>

<p>The official Apache cTAKES homepage (ctakes.apache.org) is now a landing page that says the project has moved to its GitHub repository and links to it. The apache/ctakes README confirms the description: clinical text analysis and knowledge extraction using NLP. The project is active (last commit 2026-11-04). Pointing the entry at the official ASF GitHub repository follows the project&#x27;s own move notice. The description stays as is.</p>

<p>https://ctakes.apache.org/ — Page text: &#x27;The Apache cTAKES project has moved to a GitHub repository. Please follow the link below to access documentation and other resources&#x27;, linking to https://github.com/apache/ctakes.</p>

<p>https://raw.githubusercontent.com/apache/ctakes/main/README.md — README: &#x27;clinical Text Analysis and Knowledge Extraction System (cTAKES) focuses on extracting knowledge from clinical text through Natural Language Processing (NLP) techniques&#x27;; supports HL7, CDA, FHIR, SNOMED-CT and RxNorm. Requires Java 17 for 6.x.</p>

<p>https://github.com/apache/ctakes/commits/main.atom — Most recent commit on main dated 2026-11-04.</p>

<p>Caveats: The ctakes.apache.org homepage still resolves (HTTP 200) and is ASF-owned, so the current link isn&#x27;t broken. The update only moves the entry to where the project says it now lives.; Did not run the software.</p>

</details>

<h3>OpenMRS FHIR Analytics — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -271,7 +271,7 @@
   * [eds-scikit](https://github.com/aphp/eds-scikit) - a tool to assist data scientists working on the AP-HP's Clinical Data Warehouse. It is specifically targeted for OMOP-standardized data. 
   * [IHRIS](https://www.ihris.org/toolkit-new/) - Health Information System for management of human resources for health.
   * [medspaCy](https://github.com/medspacy/medspacy) - Library for clinical NLP with spaCy.
-  * [OpenMRS FHIR Analytics](https://github.com/google/fhir-data-pipes) - Pipeline tools for transforming OpenMRS data to FHIR-based analytics using Apache Beam.
+  * [OpenMRS FHIR Analytics](https://github.com/ohs-foundation/fhir-data-pipes) - Pipelines for transforming data from FHIR servers (such as HAPI or OpenMRS) into FHIR-based analytics data warehouses using Apache Beam.
   * [OpenSAFELY](https://www.opensafely.org) - Secure analytics platform for Electronic Health Records in the NHS.
   * [Pathling](https://github.com/aehrc/pathling) - FHIR and clinical terminology analytics on Apache Spark.
   * [Snow Owl](https://github.com/b2ihealthcare/snow-owl) - Highly scalable, open source terminology server with revision-control capabilities and collaborative authoring platform features. 
```

<details>
<summary>Evidence and limitations</summary>

<p>github.com/google/fhir-data-pipes redirects to github.com/ohs-foundation/fhir-data-pipes, a repository transfer to the OHS Software Foundation. The README says the pipelines transform data from a FHIR server (like HAPI, GCP FHIR store, or even OpenMRS) into a Parquet-based data warehouse or another FHIR server. OpenMRS was only the original collaboration. The pipelines README confirms they are built with Apache Beam. So the OpenMRS-specific wording is outdated, and the URL should be the canonical one.</p>

<p>https://github.com/google/fhir-data-pipes — HTTP redirect resolves to https://github.com/ohs-foundation/fhir-data-pipes.</p>

<p>https://raw.githubusercontent.com/ohs-foundation/fhir-data-pipes/master/README.md — &#x27;pipelines to transform data from a FHIR server (like HAPI, GCP FHIR store, or even OpenMRS)... into a data warehouse based on Apache Parquet files, or another FHIR server&#x27;; &#x27;intended to be generic&#x27;; &#x27;originally started as a collaboration between Google and the OpenMRS community&#x27;.</p>

<p>https://raw.githubusercontent.com/ohs-foundation/fhir-data-pipes/master/pipelines/README.md — States &#x27;Pipelines is built using Apache Beam&#x27;; also a Spark Thrift server for querying Parquet output.</p>

<p>https://ohs-foundation.github.io/fhir-data-pipes/ — Docs site live, titled &#x27;OHS Analytics Documentation&#x27;; the old google.github.io/fhir-data-pipes returns 404.</p>

<p>https://github.com/ohs-foundation/fhir-data-pipes/commits/master.atom — Most recent commit 2026-11-03.</p>

<p>Caveats: The entry name &#x27;OpenMRS FHIR Analytics&#x27; is a legacy label. The repo is &#x27;fhir-data-pipes&#x27; and the docs say &#x27;OHS Analytics&#x27;, so the official display name is ambiguous and no rename is proposed.; Did not run the pipelines.</p>

</details>

<h3>Snow Owl — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -274,7 +274,7 @@
   * [OpenMRS FHIR Analytics](https://github.com/google/fhir-data-pipes) - Pipeline tools for transforming OpenMRS data to FHIR-based analytics using Apache Beam.
   * [OpenSAFELY](https://www.opensafely.org) - Secure analytics platform for Electronic Health Records in the NHS.
   * [Pathling](https://github.com/aehrc/pathling) - FHIR and clinical terminology analytics on Apache Spark.
-  * [Snow Owl](https://github.com/b2ihealthcare/snow-owl) - Highly scalable, open source terminology server with revision-control capabilities and collaborative authoring platform features. 
+  * [Snow Owl](https://github.com/iqvia-hds-oss/snow-owl) - Highly scalable, open source terminology server with revision-control capabilities and collaborative authoring platform features. 
   * [Snowstorm](https://github.com/IHTSDO/snowstorm) - SNOMED International's SNOMED CT terminology server.
   * [Synthea Patient Generator](https://github.com/synthetichealth/synthea) - Synthetic patient generator that models the medical history of synthetic patients.
   * [Tuva](https://github.com/tuva-health/tuva-core) - Open source data model, data marts and data quality tests for claims and clinical data.
```

<details>
<summary>Evidence and limitations</summary>

<p>The listed repo b2ihealthcare/snow-owl is archived. Its README says &#x27;B2i Healthcare is now part of IQVIA, and our open-source projects have a new home&#x27; at github.com/iqvia-hds-oss/snow-owl, and that the old repo is kept for historical reference. The new repo is the same project: same default branch 10.x, same README text, newer releases (v10.4.0 badge) and commits through 2026-10-30. This is a canonical URL move by the owner, not a replacement. The description matches the README word for word.</p>

<p>https://raw.githubusercontent.com/b2ihealthcare/snow-owl/10.x/README.md — &#x27;We&#x27;ve Moved... B2i Healthcare is now part of IQVIA... Please visit: https://github.com/iqvia-hds-oss/snow-owl. This repository is no longer actively maintained here and is being kept available for historical reference.&#x27;</p>

<p>https://github.com/iqvia-hds-oss/snow-owl — HTTP 200; title &#x27;Snow Owl Terminology Server - a production-ready, fast, scalable, FHIR Terminology Service compliant server...&#x27;; default branch 10.x.</p>

<p>https://raw.githubusercontent.com/iqvia-hds-oss/snow-owl/10.x/README.md — &#x27;Snow Owl is a highly scalable, open source terminology server with revision-control capabilities and collaborative authoring platform features.&#x27; Badges reference iqvia-hds-oss/snow-owl release v10.4.0; RF2 support as of 2026-09-01.</p>

<p>https://github.com/iqvia-hds-oss/snow-owl/commits/10.x.atom — Most recent commit 2026-10-30.</p>

<p>Caveats: Some terminologies (LOINC, ICD-10) are available only when licensed, per the README; the core server is open source.; Legacy b2ihealthcare repository remains as an archived historical reference.</p>

</details>

<h3>IHRIS — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -269,7 +269,7 @@
   * [DHIS2](https://github.com/dhis2/dhis2-core) - Health information management platform used by national health systems.
   * [EDS_NLP](https://github.com/aphp/edsnlp) - provides a set of spaCy components to extract information from clinical notes written in French
   * [eds-scikit](https://github.com/aphp/eds-scikit) - a tool to assist data scientists working on the AP-HP's Clinical Data Warehouse. It is specifically targeted for OMOP-standardized data. 
-  * [IHRIS](https://www.ihris.org/toolkit-new/) - Health Information System for management of human resources for health.
+  * [IHRIS](https://github.com/iHRIS/iHRIS) - Health Information System for management of human resources for health.
   * [medspaCy](https://github.com/medspacy/medspacy) - Library for clinical NLP with spaCy.
   * [OpenMRS FHIR Analytics](https://github.com/google/fhir-data-pipes) - Pipeline tools for transforming OpenMRS data to FHIR-based analytics using Apache Beam.
   * [OpenSAFELY](https://www.opensafely.org) - Secure analytics platform for Electronic Health Records in the NHS.
```

<details>
<summary>Evidence and limitations</summary>

<p>The listed URL https://www.ihris.org/toolkit-new/ fails TLS verification (certificate only covers Pantheon hostnames). When fetched without verification it returns HTTP 404 with the Pantheon page &#x27;404 - Unknown site&#x27;, so it no longer serves iHRIS content. iHRIS itself is clearly active: Global Communities (an IntraHealth partner) links the &#x27;iHRIS Source Code&#x27; at github.com/iHRIS/iHRIS, the developer docs at ihris.github.io, and the implementation toolkit at toolkit.ihris.org. The iHRIS/iHRIS repo is live with commits through 2026-11-01. Its docs (copyright IntraHealth International) cover iHRIS V5 management of people and positions. The description still fits. Because the rules say not to link documentation, the source repository is the suggested target.</p>

<p>https://www.ihris.org/toolkit-new/ — TLS error: &#x27;Host: www.ihris.org is not in the cert&#x27;s altnames&#x27; (Pantheon cert). Fetched insecurely: HTTP 404, title &#x27;404 - Unknown site&#x27;.</p>

<p>https://globalcommunities.org/ihris/ — Links https://github.com/iHRIS/iHRIS, https://ihris.github.io/ihris-documentation/ and https://toolkit.ihris.org/ as iHRIS resources (developed by partner IntraHealth International).</p>

<p>https://toolkit.ihris.org/ — HTTP 200; title &#x27;iHRIS Implementation Toolkit | Free and open health workforce information software.&#x27;</p>

<p>https://github.com/iHRIS/iHRIS — HTTP 200; repo &#x27;iHRIS V&#x27;; README links install docs (ansible, docker, manual); most recent commit 2026-11-01.</p>

<p>https://ihris.github.io/ihris-documentation/ — Docs for iHRIS V5 (legacy 4.3 also referenced), managing People and Positions; copyright 2024 IntraHealth International.</p>

<p>Caveats: The www.ihris.org failure could be a temporary hosting misconfiguration; per instructions, access failure alone isn&#x27;t grounds for removal, only for pointing to a working official source.; The maintainer may prefer https://toolkit.ihris.org/ (the direct successor of the listed toolkit page) over the GitHub repo.; Did not run the software.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

## Uncertain findings

<h3>Akello — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The new broader healthcare-OS description is supported, but absence of mental-health wording does not establish that the existing mental-health claim is false. Production readiness is unresolved. Hold this confident update for curator review.</p>

<p>https://raw.githubusercontent.com/akello-io/akello/main/README.md — README: &#x27;Akello is an open-source healthcare operating system built for interoperability and AI-driven data processing. It supports healthcare standards like FHIR, SNOMED, LOINC, and DICOM&#x27;. The microservices are auth, care_navigator_orchestrator, ml_model_service, patient_manager, provider_manager, sensor_data_service and user_account_manager. A grep for &#x27;mental&#x27; or &#x27;behavior&#x27; found no matches.</p>

<p>https://github.com/akello-io/akello — Repo metadata: not archived, last pushed 2026-08-16, Apache-2.0. Description: &#x27;Healthcare OS for interoperability and AI-driven data processing&#x27;.</p>

<p>Blocking questions: The new broader healthcare-OS description is supported, but absence of mental-health wording does not establish that the existing mental-health claim is false. Production readiness is unresolved. Hold this confident update for curator review.</p>

<p>Caveats: Did not run the software. Whether the re-architected platform runs in production (a list rule) was not established.; Whether a general healthcare-OS platform still fits the EHR section better than an interoperability section is a maintainer judgement.</p>

<p>Independent source check: The new broader healthcare-OS description is supported, but absence of mental-health wording does not establish that the existing mental-health claim is false. Production readiness is unresolved. Hold this confident update for curator review.</p>

<p>https://github.com/akello-io/akello/blob/main/README.md — Describes an interoperability/AI healthcare operating system with FHIR, SNOMED, LOINC and DICOM. It does not explicitly announce discontinuation of mental-health use.</p>

</details>

<h3>Beda EMR — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The FHIR-native EMR description is supported, but README Project Status says development. Production-readiness eligibility is unresolved under the list’s rules. MIT frontend licensing should not be confused with the default Aidbox backend’s separate licensing.</p>

<p>https://raw.githubusercontent.com/beda-software/fhir-emr/main/README.md — &#x27;Beda EMR... Leverages HL7 FHIR standard as a data model and SDC IG for form management.&#x27; Under &#x27;Fully FHIR compatible&#x27;: &#x27;all app data are stored as FHIR resources; any app data are available via FHIR API&#x27;. It also says &#x27;Project Status: development&#x27;.</p>

<p>https://github.com/beda-software/fhir-emr — Not archived, last pushed 2026-11-04, MIT license. Description: &#x27;EMR based on FHIR&#x27;.</p>

<p>Blocking questions: The FHIR-native EMR description is supported, but README Project Status says development. Production-readiness eligibility is unresolved under the list’s rules. MIT frontend licensing should not be confused with the default Aidbox backend’s separate licensing.</p>

<p>Caveats: The README labels the project status &#x27;development&#x27;. The maintainer may want to weigh this against the list&#x27;s GA-quality rule.</p>

<p>Independent source check: The FHIR-native EMR description is supported, but README Project Status says development. Production-readiness eligibility is unresolved under the list’s rules. MIT frontend licensing should not be confused with the default Aidbox backend’s separate licensing.</p>

<p>https://github.com/beda-software/fhir-emr/blob/main/README.md — Describes a FHIR-native EMR, development status, MIT code and default Aidbox backend; alternative FHIR servers are possible.</p>

<p>https://github.com/kakoni/awesome-healthcare/blob/master/CONTRIBUTING.md — Contribution rules require production-ready software.</p>

</details>

<h3>Cottage Med — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The download page is reachable and still offers Cottage Med, a FileMaker-based EMR from a physician practice (Trailside Health). The description is plausible. Current maintenance is unresolved: the SourceForge project&#x27;s last update is 2015-08-07, and I found no newer release. The list rule says code must not be abandoned, but age alone is not proof of abandonment.</p>

<p>https://cottagemed.org/p/26/Download-Cottage-Med — HTTP 200. Page belongs to Trailside Health family doctors. Says program files are on SourceForge. Cottage_Med needs FileMaker v.7 or later. Free demo versions are available for PC and Mac.</p>

<p>https://sourceforge.net/projects/cottagemed/ — &#x27;CottageMed EHR&#x27;. Last Update: 2015-08-07. License: GPLv2. Text says &#x27;Since 2001 CottageMed...&#x27;.</p>

<p>Blocking questions: No current release or maintenance activity could be confirmed or ruled out, so it is unresolved whether the project meets the &#x27;not abandoned&#x27; rule.</p>

<p>Caveats: Running it requires FileMaker, which is proprietary. The list may want to note this, but it is not a factual error in the entry.</p>

</details>

<h3>EHRServer — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The repo is live and not archived, and the identity matches. The last commit is 2023-03-13. CaboLabs&#x27; own product page now says EHRServer &#x27;remains available for teams that want to study the implementation or run a low-cost CDR for non-production work&#x27;. It names Atomik as the production-focused redesign. Search results also attribute an openEHR forum post to the maintainer saying EHRServer has been unmaintained, but I did not read that post directly. Atomik is a commercial product, not a documented open source successor, so replacement does not fit the list&#x27;s rules.</p>

<p>https://github.com/ppazos/cabolabs-ehrserver — Not archived. Apache-2.0. Commits feed last updated 2023-03-13.</p>

<p>https://cabolabs.com/our_software/ehrserver — &#x27;Atomik is a refactoring of EHRServer... redesigned several internals for production SaaS use... EHRServer remains available for teams that want to study the implementation or run a low-cost CDR for non-production work.&#x27;</p>

<p>https://raw.githubusercontent.com/ppazos/cabolabs-ehrserver/master/README.md — README describes an open source openEHR Clinical Data Management and Sharing Platform.</p>

<p>Blocking questions: The vendor positions EHRServer for non-production use and points production users to commercial Atomik. Whether this counts as &#x27;abandoned/discontinued&#x27; under the list rules is for a removal issue to decide. I did not read the maintainer&#x27;s &#x27;unmaintained&#x27; forum statement directly.</p>

<p>Caveats: The description &#x27;CaboLabs EHRServer.&#x27; only repeats the name. A clearer one would be something like &#x27;openEHR clinical data repository&#x27;. This is optional.</p>

</details>

<h3>ERPNext — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The healthcare module moved out of core ERPNext, but Marley still integrates with and requires ERPNext. This supports a catalog discussion, not an unqualified claim that ERPNext has become irrelevant. Marley is already listed. Removal also requires an issue under this catalog’s rules.</p>

<p>https://raw.githubusercontent.com/wiki/frappe/erpnext/Migration-Guide-to-ERPNext-version-14.md — &#x27;we broke the monolith architecture of ERPNext in version 14 and separated out the following modules into new apps. - Healthcare (https://github.com/frappe/health)&#x27;</p>

<p>https://raw.githubusercontent.com/frappe/erpnext/develop/erpnext/modules.txt — The module list (Accounts, CRM, Buying, Projects, Selling, Setup, Manufacturing, Stock, Support, Utilities, Assets, ...) has no Healthcare module.</p>

<p>https://github.com/frappe/erpnext/tree/develop/erpnext/healthcare — HTTP 404 on develop. The same path on the version-13 branch returns 200.</p>

<p>https://github.com/frappe/health — 301 redirect to https://github.com/earthians/marley, which is listed as id 53.</p>

<p>Blocking questions: The healthcare module moved out of core ERPNext, but Marley still integrates with and requires ERPNext. This supports a catalog discussion, not an unqualified claim that ERPNext has become irrelevant. Marley is already listed. Removal also requires an issue under this catalog’s rules.</p>

<p>Caveats: The legacy version-13 branch still contains the old healthcare module. Its maintenance status was not investigated.; ERPNext is active and could still be used alongside Marley, which requires ERPNext.</p>

<p>Independent source check: The healthcare module moved out of core ERPNext, but Marley still integrates with and requires ERPNext. This supports a catalog discussion, not an unqualified claim that ERPNext has become irrelevant. Marley is already listed. Removal also requires an issue under this catalog’s rules.</p>

<p>https://github.com/frappe/erpnext/wiki/Migration-Guide-to-ERPNext-version-14 — Official v14 migration guide separates Healthcare into another app and explicitly says this need not cause loss of user functionality.</p>

<p>https://github.com/frappe/erpnext/blob/develop/erpnext/modules.txt — Current core module list omits Healthcare.</p>

<p>https://github.com/earthians/marley/blob/develop/README.md — Marley supplies healthcare functions in ERPNext and documents ERPNext as an installation dependency.</p>

</details>

<h3>FerroEHR — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The description is accurate. The README and repo metadata confirm a pure-Rust openEHR CDR with ITS-REST 1.1.0, AQL 1.1 and PostgreSQL storage, and the repo is very active. However, the license is Business Source License 1.1. That is source-available, not an FSF-listed free license. Production use beyond non-commercial needs a commercial licence from Cadasto B.V., and each version converts to Apache 2.0 after four years. The list rules require FOSS or an explicit &#x27;(Commercial Software)&#x27; note.</p>

<p>https://raw.githubusercontent.com/FerroHEALTH/FerroEHR/main/README.md — Features: &#x27;openEHR REST API (ITS-REST 1.1.0)&#x27;, &#x27;AQL queries&#x27;. Operations run on PostgreSQL. Licence section: &#x27;Business Source License 1.1: free outside production and for non-commercial production use, a commercial licence from Cadasto B.V. for other production use, and Apache License 2.0 four years after each version.&#x27;</p>

<p>https://github.com/FerroHEALTH/FerroEHR — Not archived, pushed 2026-11-10. License shown as NOASSERTION. Description: &#x27;A pure-Rust openEHR Clinical Data Repository: ITS-REST 1.1.0, AQL 1.1, PostgreSQL 18-native storage.&#x27;</p>

<p>Blocking questions: Unresolved: under the list&#x27;s licensing rule, does a BUSL-1.1 project need a &#x27;(Commercial Software)&#x27; note, or does it not qualify? This is a maintainer policy decision.</p>

<p>Caveats: Did not run the software.</p>

</details>

<h3>FreeMedForms EMR — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The site is reachable and still presents FreeMedForms EMR as an open source electronic medical record, so the description is accurate. Current maintenance is unclear. The site advertises EMR 1.0.0 with &#x27;1.1.0 on the way / for testers&#x27;. The official GitHub repo the project documents (FreeMedForms/freemedforms) returns 404. Search results put the most recent SourceForge folder (1.1.0) at 2019.</p>

<p>https://freemedforms.com/fr/start — HTTP 200, French page. &#x27;La version 1.1.0 disponible pour MacOs aux testeurs&#x27;, &#x27;FreeMedForms EMR version 1.0.0&#x27;. Lists &#x27;FreeMedForms EMR — Gestionnaire de dossier médical (EMR, EHR)&#x27;.</p>

<p>https://freemedforms.com/en/start — An English page exists: &#x27;Open source electronic medical/health record... Version 1.1.0 on the way&#x27;.</p>

<p>https://github.com/FreeMedForms/freemedforms — HTTP 404.</p>

<p>Blocking questions: No current source repository or recent release could be confirmed, so whether the project meets the &#x27;not abandoned&#x27; rule is unresolved.</p>

<p>Caveats: The listed URL is the French-language page, while the rules say &#x27;English only&#x27;. An English page exists at /en/start. This is an optional URL tweak, not verified as a required correction.; I did not directly open the SourceForge files listing. The 2019 date comes from search results.</p>

</details>

<h3>GitEHR — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>Most description claims are supported. The docs describe a patient-owned record stored as a folder of plain-text files in Git, with offline operation and no database. Documents are &#x27;immutable and write-once&#x27;. The README notes that append-only enforcement is still planned: &#x27;A planned policy checker will enforce GitEHR-specific append-only... rules&#x27;. The project&#x27;s own docs label it a &#x27;Developer preview&#x27;, which conflicts with the list&#x27;s GA-quality and production-use rules.</p>

<p>https://raw.githubusercontent.com/gitehr/gitehr/main/docs/index.md — &#x27;A patient&#x27;s record is a folder of plain-text files... Auditable, portable, patient-owned by design.&#x27; A callout is labelled &#x27;Developer preview&#x27;.</p>

<p>https://raw.githubusercontent.com/gitehr/gitehr/main/README.md — &#x27;/journal - Immutable chronological entries&#x27;. &#x27;A planned policy checker will enforce GitEHR-specific append-only and authorship rules&#x27;. Encryption at rest and digital signatures are listed as planned, not implemented.</p>

<p>https://raw.githubusercontent.com/gitehr/gitehr/main/folder-structure/documents/README.md — &#x27;Documents are immutable and write-once; integrity can be checked with gitehr document verify.&#x27;</p>

<p>https://raw.githubusercontent.com/gitehr/gitehr/main/docs/design/files-not-databases.md — &#x27;A patient&#x27;s record in GitEHR is a folder of plain-text files... the offline operation...&#x27; This supports the offline-first and no-database claims.</p>

<p>Blocking questions: The project describes itself as a &#x27;Developer preview&#x27;. Whether it meets the list&#x27;s &#x27;reasonably GA quality&#x27; and production-use rules is unresolved.; &#x27;Append-only journal&#x27; is only partly implemented: the README says rule enforcement is planned.</p>

<p>Caveats: The repo is active (pushed 2026-11-10, AGPL-3.0). The description has two sentences and uses capitalised fragments, which loosely fits the list&#x27;s style rules.</p>

</details>

<h3>HOSxP — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The URL resolves to the official BMS-HOSxP site (Bangkok Medical Software), which still offers HOSxP, HOSxP XE and HOSxP PCU XE as Thai hospital information system products. Identity and the Thai-HIS description are supported. Licensing is unclear. Older third-party listings (Wikipedia, MedFLOSS) call it GPL, but the current site presents a commercial product line, and third-party sources say XE editions need yearly subscriptions. The entry has no &#x27;(Commercial Software)&#x27; note.</p>

<p>https://hosxp.net/wordpress/ — HTTP 200. Title &#x27;BMS-HOSxP&#x27;. Product menu: BMS-HOSxP, BMS-HOSxP XE, BMS-HOSxP PCU XE, plus back-office, PACS and lab products, training and migration services.</p>

<p>https://en.wikipedia.org/wiki/HOSxP — Search snippet (third-party): developer is Bangkok Medical Software, license GNU GPL. HOSxP-PCU is free, but HOSxP and HOSxP XE need a yearly subscription.</p>

<p>Blocking questions: Unresolved: is the currently distributed HOSxP open source, or does the entry need a &#x27;(Commercial Software)&#x27; note under the list rules?</p>

<p>Caveats: Most of the site is in Thai. No official license statement was found on the current site.</p>

</details>

<h3>ICTHospital — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The description is accurate. The README describes hospital management software with SMS, voice and video communications built in (via ICTCore and Jitsi), rebuilt on Laravel. The repo is active and GPL-3.0. However, the README states the rebuilt system is &#x27;Not yet proven in production&#x27;, which conflicts with the list&#x27;s rule that code must have been active in a production environment.</p>

<p>https://raw.githubusercontent.com/ictinnovations/ICTHospital/main/README.md — &#x27;Hospital management software with unified communications built in... adds SMS, voice and video consultation&#x27;. &#x27;the application was rebuilt on Laravel 12&#x27;. &#x27;Not yet proven in production. The screens are new and have automated coverage rather than years of use behind them.&#x27;</p>

<p>https://github.com/ictinnovations/ICTHospital — Not archived, pushed 2026-11-01, GPL-3.0. GitHub description says &#x27;Laravel 11&#x27;; the README says Laravel 12. The entry only says &#x27;Laravel&#x27;, so it is still accurate.</p>

<p>Blocking questions: The project says it is not yet proven in production. Whether it meets the list&#x27;s production/GA rule is unresolved.</p>

<p>Caveats: The enterprise edition adds separately licensed communication products. The community edition integrates the open source ICTCore.</p>

</details>

<h3>LibreHealth EHR — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The LibreHealth project page is live and describes LibreHealth EHR as a &#x27;clinically-focused electronic health record (EHR) system&#x27;, which matches the entry. The official code repository it links (LibreHealthIO/lh-ehr) is not archived, but its last commit is 2022-11-15. Whether the project is still maintained is unresolved, and age alone does not establish abandonment.</p>

<p>https://librehealth.io/projects/lh-ehr/ — &#x27;The LibreHealth EHR application is a clinically-focused electronic health record (EHR) system...&#x27; Maintainer: Tony McCormick. Official code repository: github.com/LibreHealthIO/lh-ehr.</p>

<p>https://github.com/LibreHealthIO/lh-ehr — Not archived. Commits feed last updated 2022-11-15.</p>

<p>Blocking questions: No maintenance activity since 2022 could be confirmed, and there is no official discontinuation statement. Status under the &#x27;not abandoned&#x27; rule is unresolved.</p>

<p>Caveats: I did not check the forums or other branches for more recent activity.</p>

</details>

<h3>Odoo Medical — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The repo is reachable and not archived, but none of the current branches (14.0 to 20.0, including the default 19.0) contain any addon modules. Their READMEs show only the template placeholder for the addons table, and their trees hold only .github and setup. Installable medical addons appear only on the 10.0 branch, whose last commit was in 2021. The phrase &quot;Universal Health and Hospital Information System&quot; is not supported by the repo&#x27;s own description (&quot;Open Source Healthcare System for Odoo&quot;). No official discontinuation notice was found, so this does not meet the removal bar. A maintainer could raise the empty supported branches in a removal issue.</p>

<p>https://raw.githubusercontent.com/OCA/vertical-medical/19.0/README.md — Default-branch README holds only the placeholder &#x27;This part will be replaced when running the oca-gen-addons-table script&#x27;. No addons are listed.</p>

<p>https://github.com/OCA/vertical-medical/tree/19.0 — Tree has only .github directories and no module directories. Branches 14.0, 16.0 and 20.0 likewise show only .github and setup.</p>

<p>https://raw.githubusercontent.com/OCA/vertical-medical/10.0/README.md — The 10.0 branch lists addons such as medical, medical_practitioner, medical_insurance and medical_pathology (10.0.1.x), plus many 8.0 modules marked unported. Last commit on 10.0 seen: 2021-10-16.</p>

<p>https://github.com/OCA/vertical-medical/pulls?q=is%3Apr+sort%3Aupdated-desc — Some PRs show 2025–2026 activity (for example 17.0 pos_* and partner_weight additions, and &#x27;Medical Plan Definition&#x27;), but nothing confirmed as merged into a current branch.</p>

<p>Blocking questions: Unresolved: whether OCA still maintains this as a working product. Current branches contain no modules, but there is no official deprecation statement.; If kept, the description should probably not claim a &#x27;Universal Health and Hospital Information System&#x27;. That would be a wording change, and its value depends on the relevance decision first.</p>

<p>Caveats: The branch list came from the HTML branches page and may be incomplete (no 8.0, 9.0, 12.0 or 13.0 trees were seen).; The repo&#x27;s open PRs were not individually reviewed.</p>

</details>

<h3>OpenClinic — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>Identity and description check out. jact/openclinic is a PHP medical records system under GPL-2.0, so &quot;Medical Records System&quot; is accurate. The last master commit is 2019-10-01, and the README still requires PHP5 (&gt;=5.3.1) and MySQL 5.1. Under the rules (&#x27;Code must not be abandoned/discontinued&#x27;), maintenance status is the open question. No official discontinuation notice was found, so removal is not supported by affirmative evidence.</p>

<p>https://raw.githubusercontent.com/jact/openclinic/master/README — &#x27;OpenClinic is an easy to use, open source, medical records system written in PHP.&#x27; Requires PHP5 &gt;= 5.3.1 and MySQL 5.1. GPL v2.</p>

<p>https://github.com/jact/openclinic/commits/master — Most recent commits are dated 2019-10-01 and 2019-09-28.</p>

<p>Blocking questions: No official statement that the project is discontinued. Seven years without commits suggests abandonment under the contribution rules, but that is a judgement for a removal issue.</p>

<p>Caveats: GitHub API was rate-limited, so archive status relies on the packet (archived=false).; Not checked whether the code runs on current PHP versions.</p>

</details>

<h3>openMAXIMS — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The packet snapshot failed, but the repo was reachable. IMS-MAXIMS/openMAXIMS returns 200 and its README matches the entry: &#x27;A full Patient Administration System designed for the NHS&#x27;, plus an EPR. The last commit on master is 2017-04-28. No official end-of-life notice was found. IMS MAXIMS is still a going concern selling its MAXIMS EPR commercially, and in 2019 its CEO publicly said the open-source project was &#x27;not abandoned&#x27;. Whether it is maintained as open source is unresolved.</p>

<p>https://raw.githubusercontent.com/IMS-MAXIMS/openMAXIMS/master/README.md — &#x27;A full Patient Administration System designed for the NHS&#x27;, with EPR features. &#x27;openMAXIMS release 10.5... live at Taunton and Somerset NHS Trust&#x27;.</p>

<p>https://github.com/IMS-MAXIMS/openMAXIMS/commits/master — Latest commits dated 2017-04-28.</p>

<p>https://highland-marketing.com/wp-content/uploads/2019/09/IMS-Shane-Tickell-Open-Source-NEWS-WIRE.pdf — Surfaced via web search: the 2019 interview with the IMS MAXIMS CEO addresses &#x27;open washing&#x27; accusations and says the project is not abandoned. Not opened directly; this is search-summary evidence only.</p>

<p>Blocking questions: No official discontinuation evidence. The roughly nine-year commit gap and the shift to commercial products suggest abandonment under the rules, but this needs a maintainer decision via a removal issue.</p>

<p>Caveats: GitHub API was rate-limited, so archive status was not confirmed by API; the HTML page loads normally.; Company status (acquired by Total Specific Solutions) comes from a third-party search summary and was not verified.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>open-eObs — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The website still describes the ward observation platform, so the description matches the site. However, the core open-eObs code repositories have been archived by their owner, with no commits since 2018–2019. The pinned rules say code &#x27;must not be abandoned/discontinued&#x27;, which makes continued inclusion doubtful. I found no official statement that the project was discontinued and no documented successor. Removal has to go through an issue under the contribution rules, so this needs a maintainer decision.</p>

<p>https://openeobs.github.io/ — Returns HTTP 200. Describes open-eObs as a NEWS app &#x27;By the NHS. For the NHS.&#x27; with real-time visual feedback on ward patient risk and ward-level views. Footer reads &#x27;© Open Health Hub CIC&#x27;.</p>

<p>https://github.com/openeobs/openeobs — Shows GitHub&#x27;s archived-repository banner. The README describes an electronic observations, ward management and task management app built as Odoo modules. The last master commit is dated 2019-01-12.</p>

<p>https://github.com/openeobs/nhclinical — The NHClinical dependency repository is archived; its last commit is dated 2018-03-16.</p>

<p>https://github.com/openeobs/openeobs.github.io/commits/master.atom — The website source was last committed on 2019-11-10.</p>

<p>Blocking questions: No official discontinuation notice or successor was found. The only evidence of abandonment is that the owner archived the repositories and activity stopped, so whether this meets the &#x27;abandoned/discontinued&#x27; bar is up to the maintainer.</p>

<p>Caveats: https://openeobs.org/ could not be reached from this environment (proxy 502). That is an access failure, not evidence that the project is dead.; I did not check whether any NHS trust still runs open-eObs in production.</p>

</details>

<h3>LibreHealth Radiology — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The description repeats the official project page exactly, and the GitLab code repository had commits in 2026. However, the official page states &#x27;The module has not yet been officially released&#x27;, and the repository has no tags or releases. That conflicts with the pinned rule that code be in production and &#x27;reasonably GA quality&#x27;. Whether the project currently meets that rule is unresolved.</p>

<p>https://librehealth.io/projects/lh-radiology/ — &#x27;Our Radiology suite is a customized version of LibreHealth Toolkit with additional tools for radiology and imaging professionals.&#x27; Under Limitations: &#x27;The module has not yet been officially released. We are working very hard on first release.&#x27;</p>

<p>https://gitlab.com/librehealth/radiology/lh-radiology — The GitLab API reports last_activity_at 2026-10-20. Latest commits are dated 2026-06-02 and 2026-05-25 (an OHIF viewer fix). The tags and releases endpoints return no entries.</p>

<p>Blocking questions: Unresolved whether LibreHealth Radiology has reached a release or production use; the official page says it has not been released.</p>

<p>Caveats: The project page may be stale relative to the code. I did not check for downstream production deployments.</p>

</details>

<h3>Kheops — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>kheops.online is live and still describes KHEOPS as a platform for storing, sharing and viewing medical images, so the description and the Imaging category both fit. Two facts are unresolved. First, the main source repo (OsiriX-Foundation/kheops) has no license file or license metadata at its root, so the &#x27;open source&#x27; claim could not be confirmed. Second, it was last committed on 2025-01-02, and several component repos, including KheopsAuthorization, which the site links to, are archived. That is weak evidence of maintenance, not proof the project is discontinued.</p>

<p>https://kheops.online/ — Returns HTTP 200. The page says &#x27;KHEOPS offers a simple solution for storing, sharing and viewing medical images&#x27;. The footer reads &#x27;© KHEOPS, inc 2019 - 2022&#x27;. The /news/ page returns &#x27;No Results Found&#x27;.</p>

<p>https://github.com/OsiriX-Foundation/kheops — Monorepo containing Authorization, DICOMwebProxy, UI, PEP, ReverseProxy and Zipper directories. It has no root README or LICENSE, and the GitHub license field is null. The last commit is 2025-01-02 (Gradle/JDK 17 update).</p>

<p>https://github.com/OsiriX-Foundation/KheopsAuthorization — Archived. This is the repo whose wiki kheops.online links to. KheopsUI, KheopsNginx and KheopsDICOMwebProxy are also archived. KheopsOrchestration (MIT) was last pushed 2024-09-26.</p>

<p>Blocking questions: The license of the main kheops source repo is unconfirmed, so the &#x27;open source&#x27; claim cannot be verified.; No official statement on whether Kheops is still maintained or has been discontinued was found.</p>

<p>Caveats: Did not deploy or run Kheops.; Some component repos (e.g. KheopsNginx, KheopsOrchestration) carry an MIT license, but the license of the main monorepo is unknown.</p>

</details>

<h3>CyclOps — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The description is still accurate: the README calls cyclops &#x27;a toolkit for facilitating research and deployment of ML models for healthcare&#x27; (data, models, evaluate, monitor, report). However, GitHub shows the owner archived the repo on Oct 20, 2026. Neither the README nor the repo page gives a reason or names a successor. Archiving alone doesn&#x27;t prove discontinuation under the pinned rules, but the repo is now read-only. A maintainer should decide whether to open a removal issue.</p>

<p>https://github.com/VectorInstitute/cyclops — Page shows &#x27;This repository was archived by the owner on Oct 20, 2026. It is now read-only.&#x27; GitHub description: &#x27;A toolkit for evaluating and monitoring AI models in clinical settings&#x27;.</p>

<p>https://raw.githubusercontent.com/VectorInstitute/cyclops/main/README.md — Describes a toolkit with data/models/tasks/evaluate/monitor/report APIs for clinical ML. No deprecation notice and no successor named.</p>

<p>https://pypi.org/pypi/pycyclops/json — Latest PyPI version of pycyclops is 0.2.12.</p>

<p>Blocking questions: Unresolved: why the repo was archived and whether Vector Institute names a maintained successor. That determines whether removal is warranted under the &#x27;not abandoned&#x27; rule.</p>

<p>Caveats: Didn&#x27;t search Vector Institute blogs or announcements for an explanation of the archive.</p>

</details>

<h3>LinuxForHealth FHIR Server — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The README confirms identity and a modular Java FHIR server (formerly IBM FHIR Server) that supports R4 and R4B. R4B is FHIR version 4.3, so &#x27;version 4&#x27; is still accurate. However, the last release (5.1.1) was in December 2022 and the last commit on main was in May 2023. No archive banner or official end-of-maintenance notice was found. Whether it is abandoned under the pinned rules can&#x27;t be determined without official confirmation.</p>

<p>https://raw.githubusercontent.com/LinuxForHealth/FHIR/main/README.md — &#x27;The LinuxForHealth FHIR® Server (formerly the IBM® FHIR® Server) is a modular Java implementation of the HL7 FHIR specification that supports versions R4 and R4B&#x27;.</p>

<p>https://github.com/LinuxForHealth/FHIR/releases.atom — Most recent release is &#x27;LinuxForHealth FHIR Server 5.1.1&#x27; (Dec 2022).</p>

<p>https://github.com/LinuxForHealth/FHIR/commits/main.atom — Latest commit on main is dated 2023-05-17. The repo page shows no archive banner.</p>

<p>Blocking questions: Unresolved: whether LinuxForHealth or IBM has officially stopped maintaining the server. More than three years without a commit suggests it, but no affirmative notice was found.</p>

<p>Caveats: Didn&#x27;t search issues or discussions for a maintainer statement about project status.</p>

</details>

<h3>fhir.js — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>Identity and description are accurate: the README says &#x27;JavaScript client for FHIR&#x27;. However, the owner archived the repository on Oct 8, 2024, and the last commit feed entry is from 2023-06-06. The pinned rules require code not to be abandoned or discontinued. The README gives no deprecation notice and names no successor, so it is unresolved whether the project is officially discontinued or just frozen. A maintainer may want to open a removal-discussion issue.</p>

<p>https://github.com/FHIR/fhir.js — HTTP 200, no redirect. Page banner: &#x27;archived by the owner on Oct 8, 2024. It is now read-only.&#x27;</p>

<p>https://raw.githubusercontent.com/FHIR/fhir.js/master/README.md — &#x27;JavaScript client for FHIR&#x27;. Goals are CRUD, a query syntax, framework adapters and auth. No deprecation, successor or no-longer-maintained statement.</p>

<p>https://github.com/FHIR/fhir.js/commits.atom — Most recent commit entry is dated 2023-06-06.</p>

<p>Blocking questions: No official discontinuation statement or documented successor was found. Whether the archive counts as &#x27;abandoned&#x27; under the contribution rules is a maintainer judgment.</p>

<p>Caveats: Did not check whether the npm package still works with current FHIR servers.; Archive status alone does not prove the library is unusable.</p>

</details>

<h3>Graphir — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The URL resolves to microsoft/Graphir (case differs only), and the description matches the repo description. However, the owner archived the repo on Jun 15, 2026. The README calls it &#x27;an example lightweight proxy&#x27; that uses Azure FHIR as its backend, and the last commit is from 2023-01-17. That raises questions about the &#x27;maintained&#x27; and &#x27;GA quality&#x27; rules, but no official discontinuation statement was found. Suggest the maintainer consider a removal-discussion issue.</p>

<p>https://github.com/microsoft/graphir — HTTP 200. Canonical name is microsoft/Graphir. Banner: &#x27;archived by the owner on Jun 15, 2026. It is now read-only.&#x27;</p>

<p>https://raw.githubusercontent.com/microsoft/Graphir/main/README.md — &#x27;Graphir is an example lightweight proxy that reshapes GraphQL queries and mutations into standard FHIR REST requests. This example uses the Azure implementation of FHIR as its backend.&#x27;</p>

<p>https://github.com/microsoft/Graphir/commits.atom — Latest commit entry is dated 2023-01-17.</p>

<p>Blocking questions: No official statement explains the archive or names a successor. Whether an archived &#x27;example&#x27; project still meets the contribution rules is for the maintainer to decide.</p>

<p>Caveats: Did not run the proxy.; GitHub URLs are case-insensitive, so the lowercase URL still works.</p>

</details>

<h3>Hearth — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The description matches the repo&#x27;s own text verbatim. However, the README says the project &#x27;is still in the early stages of development&#x27; and is updated only &#x27;when we have projects with funding&#x27;. package.json is at 1.0.0-beta.3, and the last commit is from 2019-11-22. This conflicts with the pinned rules on reasonable GA quality and not being abandoned. It is not archived and there is no official discontinuation notice.</p>

<p>https://raw.githubusercontent.com/jembi/hearth/master/README.md — &#x27;A fast FHIR-compliant server focused on longitudinal data stores... It is still in the early stages of development... We do our best to update this project when we have projects with funding that are using it.&#x27;</p>

<p>https://raw.githubusercontent.com/jembi/hearth/master/package.json — version &#x27;1.0.0-beta.3&#x27;.</p>

<p>https://github.com/jembi/hearth/commits.atom — Latest commit entry is dated 2019-11-22. Repo is not archived.</p>

<p>Blocking questions: Unresolved whether Hearth is still maintained or used in production. No official discontinuation evidence was found.</p>

<p>Caveats: Inactivity alone does not prove discontinuation.; Did not check for production deployments.</p>

</details>

<h3>Health data standards — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The listed repo was archived on Jun 24, 2021, and its README says it is &#x27;read-only, and kept for historical purposes&#x27;, naming MeasureAuthoringTool/health-data-standards as the active home. That successor was itself archived on Sep 3, 2021, with its last commit in 2020-06. So &#x27;replace&#x27; is not viable, because no maintained official successor is documented. Also, the 3.6.0 changelog notes &#x27;Removed GC32 &amp; CCR code&#x27;, which needs checking against the C32 claim. This is strong evidence for a removal-discussion issue, but there is no explicit statement that the functionality was withdrawn.</p>

<p>https://raw.githubusercontent.com/projectcypress/health-data-standards/master/README.md — &#x27;NOTE: This repository is read-only, and kept for historical purposes. Development is currently active on https://github.com/MeasureAuthoringTool/health-data-standards&#x27;. It is described as a project to generate and consume HITSP C32, QRDA Cat I and Cat III. The changelog shows 3.6.0 &#x27;Removed GC32 &amp; CCR code&#x27;.</p>

<p>https://github.com/projectcypress/health-data-standards — Banner: &#x27;archived by the owner on Jun 24, 2021&#x27;.</p>

<p>https://github.com/MeasureAuthoringTool/health-data-standards — The named successor is also &#x27;archived by the owner on Sep 3, 2021&#x27;. Latest commit entry is 2020-06-15.</p>

<p>Blocking questions: No maintained official successor exists, and there is no explicit statement that the functionality was withdrawn. Removal should go through an issue per the contribution rules.</p>

<p>Caveats: Did not check whether the Ruby gem still installs or runs.; Did not research other Cypress-era gems, which would not be documented successors of this repo.</p>

</details>

<h3>Rust FHIR — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The repository still says &#x27;Rust SDK for HL7 FHIR&#x27;, matching the entry, but the code is auto-generated FHIR data models (Cargo description &#x27;HL7 FHIR data models&#x27;, version 0.0.6). Activity stopped years ago: the last commit was 2023-01-20 and the last release (0.0.6) was 2022-08-03. The crates.io &#x27;fhir&#x27; crate that its README badge advertises now publishes a different project: fhir-rust/fhir-rust by another publisher, versions 0.1.0 to 4.2.4 from 2026. Neither side documents that project as a successor. Unresolved: whether this repository is still maintained or used, as the rules&#x27; maintained/GA conditions require. A successor cannot be inferred.</p>

<p>https://raw.githubusercontent.com/itsbalamurali/rust-fhir/HEAD/README.md — Title &#x27;Rust SDK for HL7 FHIR&#x27;; &#x27;auto generated from googles fhir protobufs&#x27;. Badge points at crates.io/crates/fhir.</p>

<p>https://raw.githubusercontent.com/itsbalamurali/rust-fhir/HEAD/Cargo.toml — name=&#x27;fhir&#x27;, description=&#x27;HL7 FHIR data models&#x27;, version 0.0.6, prost 0.11.</p>

<p>https://github.com/itsbalamurali/rust-fhir/commits.atom — Latest commit 2023-01-20. The repo is not archived.</p>

<p>https://crates.io/api/v1/crates/fhir/versions — Versions 0.0.1–0.0.6 (2022) were published by itsbalamurali from itsbalamurali/rust-fhir. Versions 0.1.0+ (2026-07 onward) were published by joelparkerhenderson, with repository github.com/fhir-rust/fhir-rust.</p>

<p>https://raw.githubusercontent.com/fhir-rust/fhir-rust/HEAD/README.md — No mention of itsbalamurali or rust-fhir was found, so it is not documented as a successor.</p>

<p>Blocking questions: No official statement confirms abandonment of itsbalamurali/rust-fhir, or that fhir-rust/fhir-rust is its endorsed successor.</p>

<p>Caveats: No official discontinuation notice exists, and age alone does not justify removal.</p>

</details>

<h3>Intervention Engine — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The description matches the README word for word: &#x27;provides a web-application for data-driven team huddles&#x27;. However, the last commit was 2017-04-22. The README still calls it &#x27;a work in progress&#x27; with &#x27;prototype&#x27; risk services, and it uses Travis CI and vendored Go dependencies. The repo is not archived, and no official discontinuation notice was found. Unresolved: whether the project is abandoned and production-grade under the rules. Age alone does not settle this.</p>

<p>https://raw.githubusercontent.com/intervention-engine/ie/HEAD/README.md — &#x27;The Intervention Engine project provides a web-application for data-driven team huddles.&#x27; Also: &#x27;Intervention Engine is a work in progress&#x27;, listing prototype risk services and &#x27;Still to come&#x27; items.</p>

<p>https://github.com/intervention-engine/ie/commits.atom — Latest commit 2017-04-22.</p>

<p>https://github.com/intervention-engine — The organization still hosts related repos (fhir, frontend-react, ie-docker, etc.). No deprecation banner was seen in the fetched HTML.</p>

<p>Blocking questions: No affirmative official evidence of discontinuation, and no confirmation of continued maintenance or production use.</p>

<p>Caveats: Archive status and maintainer intent could not be confirmed through the API (rate-limited). Only the HTML repo page and commit feed were read.</p>

</details>

<h3>HealthLocker — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>Identity and description check out. The repo resolves, is not archived, and mix.exs plus the README confirm an Elixir/Phoenix app (Healthlocker, version 1.0.3, from South London and Maudsley NHS Foundation Trust) for supported self-management. The open question is maintenance: the latest commit on master is dated 2018-06-22, and the README still uses Travis CI and phantomjs. The contribution rules say code &#x27;must not be abandoned&#x27;, but no official deprecation or discontinuation notice was found. Age alone does not justify removal. A maintainer could raise it in an issue.</p>

<p>https://github.com/healthlocker/healthlocker — HTTP 200, not archived; description &#x27;Inspire and motivate people to stay well.&#x27;</p>

<p>https://raw.githubusercontent.com/healthlocker/healthlocker/HEAD/mix.exs — Elixir Mix project :healthlocker version 1.0.3 using Phoenix, Ecto and Postgrex. This confirms the &#x27;Elixir-based&#x27; claim.</p>

<p>https://raw.githubusercontent.com/healthlocker/healthlocker/HEAD/README.md — Describes a secure platform from South London and Maudsley NHS Foundation Trust for self-management and communication between service users, carers and clinicians. Uses Travis CI badge and Vagrant setup.</p>

<p>https://github.com/healthlocker/healthlocker/commits — Most recent committedDate shown is 2018-06-22.</p>

<p>Blocking questions: Unresolved: is the project still maintained or deployed? No official discontinuation statement was found; only inactivity since 2018.</p>

<p>Caveats: Whether it is still deployed in production at SLaM is unknown.</p>

</details>

<h3>LabKey Server — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The listed URL redirects to https://www.labkey.com/sdms-software/, a commercial &#x27;LabKey SDMS&#x27; page with pricing tiers. That page does not mention translational research or open source. The open-source edition is now branded &#x27;LabKey Server SDMS – Community Edition&#x27; (Apache 2.0), but its download requires a form. The source code is public at github.com/LabKey/platform (&#x27;core functionality for LabKey Server&#x27;). The &#x27;Platform for Translational Research&#x27; description is no longer supported by the destination page. The right canonical target is unresolved: marketing page, community-edition page, or GitHub repo. The commercial/open-source framing also needs a maintainer decision.</p>

<p>https://www.labkey.com/products-services/labkey-server/ — Redirects (HTTP 200) to https://www.labkey.com/sdms-software/, titled &#x27;SDMS Software: Scientific Data Management with LabKey SDMS&#x27;.</p>

<p>https://www.labkey.com/sdms-software/ — Focuses on commercial SDMS tiers. A footer links &#x27;Download Community Edition&#x27;. No mention of translational research, open source or GitHub.</p>

<p>https://www.labkey.com/download-community-edition/ — Product named &#x27;LabKey Server SDMS – Community Edition&#x27;, licensed under Apache 2.0. The download requires completing a form, and LabKey provides no support for it.</p>

<p>https://github.com/LabKey/platform — HTTP 200; &#x27;A set of modules that provide core functionality for LabKey Server&#x27;.</p>

<p>Blocking questions: Unresolved canonical destination: redirected commercial SDMS page vs github.com/LabKey/platform vs the community-edition page (which requires registration, which the rules disallow for non-newsletter resources).; Unresolved replacement wording: current official positioning (scientific data management) differs from &#x27;Platform for Translational Research&#x27;.</p>

<p>Caveats: LabKey documentation was not reviewed to see whether translational research is still a documented use case.</p>

</details>

<h3>NextGen Connect Integration Engine — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The repo resolves, is not archived, and its description still matches the entry. However, NextGen officially announced on 2025-03-19 that Mirth Connect moved to a single commercial, proprietary license starting with 4.6. 4.5.2 is the final open-source release, and the repo&#x27;s latest release is still 4.5.2. NextGen says the GitHub source stays available, but new versions are closed. The open-source code at this URL is frozen at the vendor level, which may conflict with the rule that code &#x27;must not be abandoned/discontinued&#x27;. The product itself continues commercially. A removal, a &#x27;(Commercial Software)&#x27; note, or a separate addition of a community fork (e.g. Open Integration Engine, which NextGen does not name as a successor) all need maintainer discussion via an issue.</p>

<p>https://www.nextgen.com/blog/industry-news/a-new-era-for-mirth-connect-by-nextgen-healthcare — Official: &#x27;transitioning from a dual license (open-source and commercial) to a single commercial and proprietary Mirth Connect licensing model with Mirth Connect 4.6&#x27;. Open-source users may stay on their version or upgrade to 4.5.2, &#x27;the final open-source release&#x27;. &#x27;All GitHub source code ... will continue to be available&#x27;.</p>

<p>https://github.com/nextgenhealthcare/connect/releases.atom — Latest release listed is &#x27;Mirth Connect 4.5.2&#x27;.</p>

<p>https://raw.githubusercontent.com/nextgenhealthcare/connect/HEAD/README.md — README is titled &#x27;Mirth® Connect by NextGen Healthcare&#x27; and describes filtering, transformation, extraction and routing of healthcare messages.</p>

<p>https://github.com/nextgenhealthcare/connect — HTTP 200; not archived; description &#x27;The swiss army knife of healthcare integration.&#x27; Latest commit on development is dated 2026-09-17 (content not inspected).</p>

<p>Blocking questions: Unresolved: does a vendor-frozen open-source line (MPL 2.0 code still public, no new OSS releases since 4.5.2) count as &#x27;discontinued&#x27; under this list&#x27;s rules? That is a maintainer policy call.; No officially documented open-source successor. Open Integration Engine and BridgeLink are community forks, not vendor-designated successors, so replacement is not supported.</p>

<p>Caveats: The 2026-09-17 commit to the public repo was not inspected; it may be housekeeping.; The entry&#x27;s tagline is the vendor&#x27;s slogan. The rules discourage superlatives, but it is not a factual error.</p>

</details>

<h3>Gluco — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The identity and the &#x27;Glucometer&#x27; description are correct. The repo nebulabio/gluco (&#x27;An open source glucometer&#x27;) is live and not archived. However, the README says &#x27;For research purposes only. Currently a work in progress&#x27;, and the last commit is from Mar 2016. The contribution rules ask for maintained, GA-quality code that has been used in production. Nothing official says the project was discontinued, so removal is not supported. Whether it still meets the maintained/GA criteria is unresolved and needs the maintainer&#x27;s judgment.</p>

<p>https://github.com/nebulabio/gluco — Returns 200 with no redirect and no archived banner. Description: &#x27;An open source glucometer&#x27;.</p>

<p>https://raw.githubusercontent.com/nebulabio/gluco/master/README.org — Title &#x27;Gluco - an open source glucometer&#x27;. The README says &#x27;For research purposes only. Currently a work in progress.&#x27; and describes an Arduino Uno plus e-Health shield build.</p>

<p>https://github.com/nebulabio/gluco/commits/master.atom — The most recent commit on master is from 2016-03-15.</p>

<p>Blocking questions: No official statement says whether the project is discontinued or production-ready. The README&#x27;s &#x27;work in progress / research only&#x27; wording conflicts with the GA-quality rule, and only the maintainer can decide that.</p>

<p>Caveats: I did not build or test the hardware.; Age and inactivity alone do not prove the project is abandoned.</p>

</details>

<h3>Cedar — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The identity and description are accurate. mitre/cedar is a tool &#x27;for testing the strength of Electronic Clinical Quality Measure (eCQM) collection systems that receive QRDA files&#x27;, and the repo is live and not archived. However, the last commit was in Jul 2017 and the last release in Oct 2016, and the README still documents Rails, Mongo and Homebrew setup from that era. The rules require code that is not abandoned. I found no official discontinuation notice, so removal is not supported, but its maintenance and current relevance to eCQM/QRDA reporting are unresolved.</p>

<p>https://github.com/mitre/cedar — Returns 200, not archived. Description: &#x27;Cedar is a tool for testing the strength of Electronic Clinical Quality Measure (eCQM) collection systems that receive Quality Reporting Document Architecture (QRDA) files.&#x27;</p>

<p>https://raw.githubusercontent.com/mitre/cedar/master/README.md — The README repeats the purpose and says it is &#x27;open source and freely available for use or adoption by state health agencies&#x27;. It is a Ruby on Rails app with a MongoDB backend.</p>

<p>https://github.com/mitre/cedar/commits/master.atom — Latest commit 2017-07-10. Latest release &#x27;October 2016 Release&#x27;.</p>

<p>Blocking questions: No official statement says whether Cedar is maintained or deprecated, or whether it supports current QRDA/eCQM versions. That is needed to judge it against the &#x27;not abandoned&#x27; rule.</p>

<p>Caveats: Inactivity alone is not evidence that the project was discontinued.</p>

</details>

<h3>MEDIC Client Registry RI — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The repo is reachable and not archived. Its README describes a prototype Client Registry/EMPI reference implementation built under an NSERC grant, intended for development, test, demo and staging use. The last commit was 2018-10-21, which conflicts with the pinned &#x27;not abandoned&#x27; and &#x27;production/GA&#x27; conditions, but no official discontinuation notice was found in the repo. Third-party sources (search results summarizing SanteSuite and Digital Square pages) describe SanteMPI as the next-generation MEDIC CR from the original team. The santedb/client-registry fork published 1.x &#x27;MEDIC CR / SanteMPI&#x27; releases, but it was last committed in 2019 and its README is unchanged. The Mohawk repo itself doesn&#x27;t document a successor, so replace and remove are both unsupported. This should go to a maintainer removal-or-replace issue.</p>

<p>https://raw.githubusercontent.com/MohawkMEDIC/client-registry/master/README.md — Describes &#x27;the prototype Client Registry (Enterprise Master Patient Index - EMPI)&#x27;; supports HL7v3, IHE PIX/PDQ v3 and v2, PDQm; &#x27;intended to assist developers... as a test interface, in demonstration XDS infrastructures, or in staging environments&#x27;.</p>

<p>https://github.com/MohawkMEDIC/client-registry/commits/master.atom — Most recent commit 2018-10-21.</p>

<p>https://github.com/santedb/client-registry — Fork of MohawkMEDIC/client-registry; README identical; most recent commit 2019-04-12; releases page reportedly lists 1.4.0 as combined MEDIC CR / SanteMPI.</p>

<p>https://applications.digitalsquare.io/content/sant%C3%A9mpi-client-registry — Per search-result summary (page not directly read): SantéMPI described as a commercially supported open source derivative of the MEDIC Client Registry.</p>

<p>Blocking questions: The MohawkMEDIC repository doesn&#x27;t document an official successor; SanteMPI is described as a derivative by a separate commercial entity, so &#x27;replace&#x27; isn&#x27;t supported.; No official discontinuation or deprecation notice for the listed implementation, so &#x27;remove&#x27; needs a maintainer discussion issue under the contribution rules.; SanteMPI&#x27;s current canonical source repository was not verified (santedb/santedb-mpi returned 404).</p>

<p>Caveats: Did not directly read the SanteSuite or Digital Square pages; successor claims come from search-result summaries.; The GitHub API was rate-limited; activity was taken from commit Atom feeds.</p>

</details>

<h3>Tapirx — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>Identity and description check out: virtalabs/tapirx returns 200, is not archived, and its README says it &#x27;passively discovers and identifies networked medical devices&#x27;. What is unresolved is whether Tapirx is still maintained, which the list&#x27;s &#x27;must not be abandoned&#x27; rule depends on. The default branch (develop) was last committed in Aug 2019, though a feature branch has 2026 commits. The vendor site now promotes TapirXL for passive device identification, and a new virtalabs/tapirxl repo is described as &#x27;based on tapirx&#x27;. Neither Tapirx nor TapirXL documents TapirXL as Tapirx&#x27;s official successor, and TapirXL&#x27;s license shows as NOASSERTION, so a replace recommendation is not supported.</p>

<p>https://raw.githubusercontent.com/virtalabs/tapirx/develop/README.md — &#x27;Tapirx (&quot;taper ecks&quot;) passively discovers and identifies networked medical devices.&#x27; Go tool that sniffs HL7/DICOM traffic from SPAN ports or pcaps. No deprecation or archive notice.</p>

<p>https://github.com/virtalabs/tapirx/commits/develop — Most recent commits on the default branch dated 2019-08-28 and 2019-06-24.</p>

<p>https://github.com/virtalabs/tapirx/branches/all — Non-default branch feature/configurable-http-verb has commits dated 2026-04-07 to 2026-04-13. Other branches were last touched between 2019 and 2022. Whether these branches will be merged or released is unknown.</p>

<p>https://virtalabs.com/ — Vendor site says &#x27;TapirXL passively identifies medical devices from observed network traffic, and BlueFlow provides the open asset-management core&#x27;. Tapirx is not named.</p>

<p>https://github.com/virtalabs/tapirxl — Repo description: &#x27;Free and open-source medical device discovery and identification tool based on tapirx&#x27;. It is a Python 3.14 rewrite. GitHub license detection shows NOASSERTION/Other.</p>

<p>Blocking questions: No official statement that Tapirx is discontinued or superseded by TapirXL.; TapirXL&#x27;s license is unconfirmed (GitHub shows NOASSERTION), so a replacement could not be checked against the open-source requirement.; Whether Tapirx is still maintained or used in production is unknown.</p>

<p>Caveats: The GitHub REST API was rate-limited, so I used HTML pages and raw files for commit dates and branches.; Branch existence and recent feature-branch commits do not establish maintenance status either way.</p>

</details>

## Unresolved keeps

These entries were not added to the baseline.

<h3>OpenEMR — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>www.open-emr.org resolves (200) to the official OpenEMR site, which announces version 8.5 and describes OpenEMR as &quot;the most popular open source electronic health records and medical practice management solution&quot;. This matches the entry&#x27;s &quot;Electronic Health Records and Medical Practice Management application.&quot;</p>

<p>https://www.open-emr.org/ — &#x27;OpenEMR is the most popular open source electronic health records and medical practice management solution.&#x27; &#x27;New: Announcing OpenEMR Version 8.5&#x27;. ONC Certified; free download for Windows, macOS and Linux.</p>

<p>Caveats: The GitHub repository (openemr/openemr) was not inspected because the API was rate-limited. The listed site was sufficient.</p>

</details>

<h3>OpenMRS — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>openmrs.org resolves (200). The site calls OpenMRS the open-source medical records system built by a global community: 8000+ facilities in 70+ countries, with REST and FHIR APIs, adaptable to local needs. This supports &quot;Enterprise Electronic Medical Record System platform.&quot;</p>

<p>https://openmrs.org/ — &#x27;Electronic Medical Records built by a Global Community&#x27;. &#x27;Our community builds and maintains the world&#x27;s leading open-source medical records system&#x27;. Lists REST/FHIR APIs, 8000+ facilities and 70+ countries.</p>

<p>Caveats: &#x27;Enterprise&#x27; is not wording the site uses, but it is not contradicted.</p>

</details>

<h3>OSCAR EMR — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>bitbucket.org/oscaremr/oscar is public and active. The Bitbucket API shows full_name oscaremr/oscar, description &#x27;OSCAR EMR&#x27;, main branch &#x27;stable&#x27; with a last commit on 2026-06-13, and feature branches through 2026-02 (for example a Java 11 migration). It remains a relevant EHR. The description &quot;OSCAR McMaster Project&quot; is a historical label rather than a functional description, but it is not shown to be false.</p>

<p>https://api.bitbucket.org/2.0/repositories/oscaremr/oscar — Public repo &#x27;OSCAR EMR&#x27;; mainbranch &#x27;stable&#x27;; updated_on 2026-06-13.</p>

<p>https://api.bitbucket.org/2.0/repositories/oscaremr/oscar/commits?pagelen=3 — Latest commits 2026-06-13 and 2026-06-03 (JSP fixes). Recent branches include OSCAREMR-7265-java-11 and OSCAREMR-7268-ability-to-use-headless-ch.</p>

<p>Caveats: The rendered Bitbucket page needs JavaScript; evidence comes from the public Bitbucket API.; The current McMaster University affiliation was not verified. A more functional description (for example &#x27;Electronic medical record system&#x27;) would be an optional clarification, not a confirmed correction.</p>

</details>

<h3>OHDSI OMOP Common Data Model — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The OHDSI Data Standardization page resolves (200) and describes the OMOP CDM as an open community data standard with standardized vocabularies, linking to the OMOP CDM GitHub. The CommonDataModel README confirms SQL DDLs for multiple supported dialects (generated via R or downloadable). That supports &quot;scripts for many major relational databases&quot;.</p>

<p>https://www.ohdsi.org/data-standardization/ — &#x27;The Observational Medical Outcomes Partnership (OMOP) Common Data Model (CDM) is an open community data standard, designed to standardize the structure and content of observational data&#x27;. Links to the OMOP CDM GitHub.</p>

<p>https://raw.githubusercontent.com/OHDSI/CommonDataModel/main/README.md — SQL DDLs available under inst/ddl/5.5 and in releases. listSupportedDialects() and executeDdl support multiple DBMS dialects.</p>

<p>Caveats: &#x27;awesome Github presence&#x27; is subjective wording; the rules discourage superlatives, but this is not a factual error.</p>

</details>

<h3>OpenEHR — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>www.openehr.org redirects to https://openehr.org/ (same organisation). The site describes openEHR as a non-profit that publishes open standards and clinical models, with specifications, platforms and tools for building health software. This supports &quot;Open specification upon which software can be built.&quot;</p>

<p>https://openehr.org/ — &#x27;openEHR is a non-profit that publishes open standards and clinical models for a lifelong, patient-centred health record.&#x27; &#x27;Build on openEHR: Specifications, shared clinical models, platforms and tools for building health software&#x27;.</p>

<p>Caveats: The www to apex redirect is harmless. Updating the URL to https://openehr.org is optional.</p>

</details>

<h3>sct — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The repository is canonical and very active. It is a Rust, local-first SNOMED CT toolchain that turns RF2 release files into NDJSON, SQLite, Parquet and other files. &#x27;File-based SNOMED-CT toolset built in Rust&#x27; is still accurate. The added MCP, GUI and FHIR server features are expansions, not contradictions.</p>

<p>https://raw.githubusercontent.com/pacharanero/sct/HEAD/README.md — &#x27;A local-first SNOMED CT toolchain. One binary - from raw RF2 release to NDJSON, then SQL, Parquet, Markdown, TUI, GUI, graphs and MCP/LLM tool use.&#x27; The README also says it is &#x27;very much a work in progress, but it&#x27;s ready to use&#x27;.</p>

<p>https://raw.githubusercontent.com/pacharanero/sct/HEAD/Cargo.toml — Rust package &#x27;sct-rs&#x27;, binary &#x27;sct&#x27;, license AGPL-3.0-or-later. Description: &#x27;Local-first SNOMED CT toolchain: RF2 → NDJSON, SQLite, Parquet, Markdown, Arrow embeddings, and MCP server&#x27;.</p>

<p>https://github.com/pacharanero/sct/commits.atom — Latest commit 2026-11-09.</p>

<p>Caveats: The author calls it a &#x27;work in progress&#x27;. The maintainer may want to weigh that against the rules&#x27; GA-quality condition, but it is not a description error.</p>

</details>

<h3>Simple — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The org URL resolves. The packet snapshot failure was a fetch error, not a dead link. The org hosts an Android app for recording hypertension and blood-pressure data plus its backend, and both were committed to in the last two weeks. Simple.org describes &#x27;Fast, free software for clinicians to manage patients with hypertension &amp; diabetes&#x27;, which supports the entry.</p>

<p>https://github.com/simpledotorg — 200. Repos include simple-android (&#x27;An Android app for recording hypertension-related data&#x27;), simple-server (&#x27;The web app behind Simple.org&#x27;) and a hypertension dashboard template.</p>

<p>https://raw.githubusercontent.com/simpledotorg/simple-android/HEAD/README.md — &#x27;# Simple — An Android app for recording blood pressure measurements.&#x27;</p>

<p>https://raw.githubusercontent.com/simpledotorg/simple-server/HEAD/README.md — &#x27;This is the backend for the Simple app to help track hypertensive patients across a population.&#x27; Verified DPG badge.</p>

<p>https://simple.org — &#x27;Fast, free software for clinicians to manage patients with hypertension &amp; diabetes.&#x27; Used in India, Bangladesh, Ethiopia, Sri Lanka and Myanmar.</p>

<p>https://github.com/simpledotorg/simple-android/commits.atom — simple-android: latest commit 2026-10-29. simple-server: latest commit 2026-11-04.</p>

<p>Caveats: Simple now also covers diabetes. That is an optional expansion; the entry&#x27;s hypertension claim remains true.; The entry links to a GitHub organization rather than a single repository. This is pre-existing and not a factual error.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Tidepool — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The packet snapshot failed, but the URL was reachable live. github.com/tidepool-org returns HTTP 200 for the Tidepool Project org, which describes itself as &#x27;an open source, nonprofit effort building an open data platform to make diabetes data more accessible, actionable, and meaningful&#x27;. It hosts platform (Go API), blip (web viewer) and uploader repos. &#x27;Data platform&#x27; and the PHR fit are supported.</p>

<p>https://github.com/tidepool-org — HTTP 200; og:title &#x27;Tidepool Project&#x27;. The org description says it builds an open data platform for diabetes data. Verified domain tidepool.org. Repos include platform, blip, uploader, TidepoolApi and Loop.</p>

<p>Caveats: The org text now refers to diabetes generally rather than Type 1 specifically. The entry&#x27;s &#x27;Type 1 Diabetes&#x27; mission phrasing was not re-verified against tidepool.org, but it is not contradicted.; Individual repos were not checked for archive status.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Murgen — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The Hackaday.io page is live and titled &#x27;Murgen: open source ultrasound imaging&#x27;. It describes &#x27;An open-source ultrasound imaging dev kit&#x27;, which matches the entry. The project is tagged &#x27;completed&#x27;. Its linked murgen-dev-kit repo was last updated in 2021, and the author&#x27;s related echomods repo is still active (Oct 2026). Completion is not an official statement that the project lost its purpose. Whether a completed hardware kit satisfies &#x27;maintained&#x27; is for the maintainer to judge.</p>

<p>https://hackaday.io/project/9281-murgen-open-source-ultrasound-imaging — Returns 200. The page says &#x27;An open-source ultrasound imaging dev kit&#x27; and carries the tags &#x27;completed project&#x27;, &#x27;medical imaging&#x27; and &#x27;ultrasound&#x27;. It links to the documentation and the GitHub repos.</p>

<p>https://github.com/kelu124/murgen-dev-kit — Not archived. Description: &#x27;Imaging ultrasound dev/hacking kit&#x27;. Last commit 2021-11-11.</p>

<p>https://github.com/kelu124/echomods — The same author&#x27;s &#x27;Open source ultrasound processing modules and building blocks&#x27; repo is active (commit 2026-10-08). I found no official statement that it is Murgen&#x27;s successor.</p>

<p>Caveats: The project is marked completed, and the dev-kit repo has been inactive since 2021. I did not verify whether the hardware is still available on Tindie.; I am not proposing echomods as a replacement because no officially documented successor relationship was found.</p>

</details>

<h3>OpenSAFELY — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The official site is live. Its About page calls OpenSAFELY &#x27;an open source trusted research environment (TRE), specifically tailored for electronic health record (EHR) analysis&#x27;, deployed within the secure data centres of the two largest NHS EHR providers (TPP and Optum). It is built by the Bennett Institute, University of Oxford, with NHS England. The description is accurate and the software is open source on GitHub.</p>

<p>https://www.opensafely.org/ — &#x27;A platform for analysing large, sensitive datasets – safely and securely&#x27;; &#x27;built, managed and maintained by a team at the Bennett Institute, University of Oxford, with NHS England, TPP, Optum&#x27;.</p>

<p>https://www.opensafely.org/about/ — &#x27;OpenSAFELY is an open source trusted research environment (TRE), specifically tailored for electronic health record (EHR) analysis&#x27;; deployed in TPP and Optum data centres; code freely available at github.com/opensafely.</p>

<p>Caveats: Access to run analyses requires approval; the listed link is the public project website.</p>

</details>

The complete research records remain local. This inventory contains all recommendations and unresolved entries from the saved initial review.

[One-entry integration example](https://github.com/bromanko/awesome-healthcare/blob/codex/catalog-inventory-preview/.um/catalog-inventory/checked-example.md). Saved research with real discussion-history and patch checks.
