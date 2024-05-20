CSA CCM Control Domain	Control Name	Control ID	Control Description		Physio Controls	Physio Maturity Rating	Maturity Rating Justification		AI Gauss Controls	Maturity Rating	Maturity Rating Justification		Blueprint Controls	Maturity Rating	Maturity Rating Justification		Prophecy Controls	Maturity Rating	Maturity Rating Justification		Vocera Controls	Maturity Rating	Maturity Rating Justification		General Recommendations (All accounts) 		"Stryker Shared Services Controls 
(3rd Party Risk, AppSec, CCOE, DPO, Audit, CIRT, etc.)"	Maturity Rating	Maturity Rating Justification		Ideal State Controls		Average Score of Control Maturity across AWS accounts	Average Score of Control Maturity across AWS accounts, Ignoring Os			
Audit & Assurance	Audit and Assurance Policy and Procedures	A&A-01	Establish, document, approve, communicate, apply, evaluate and maintain audit and assurance policies and procedures and standards. Review and update the policies and procedures at least annually.		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"At a minimum, audit and assurance policies and procedures should include:

a. Audit and assurance functions indicating purposes, responsibilities, authorities, and 
accountabilities to ensure organizational independence, professional care, audit objectivity, 
and proficiency,
b. Audit and assurance plans,
c. Audit development policies and procedures to determine criteria and assertions against which 
the subject matter will be assessed, quality assurance and supervision, sufficient and appropriate 
evidence, in accordance with commonly accepted frameworks and audit best practices,
d. Audit reporting to communicate audit results and findings,
e. Follow-up activities to monitor audit findings implementation progress"		"Several teams referred to ISO 27001 HIPAA or SOC 2 compliance but no documentation (policies, procedures, additional guidance) were produced to validate. Audit Team:- Playbooks and other documentation stored on a per team basis- Meeting standard docs must be in QMS- Internal use can be in different places (playbooks, knowledge base articles, docs)Audit Team Controls/ Policies in place:-SOP for document control (ISSOP_QMS_001) with system to have audit-SMLS for training documents management-3 year review if no revisions made beforehand-Process owner or document owner responsible for creation and modification-Review process: process owner, quality assurance, and other relevant teams, then Audit&Assurance pushes to OnePLM (Windchill)-OnePLM pushes to SMLS via API"	2	The company has some audit and assurance policies and procedures in place, such as an SOP for document control (ISSOP_QMS_001), a system for managing training documents (SMLS), and a defined review process involving process owners, quality assurance, and relevant teams. Documents are stored in various locations including a Quality Management System (QMS), playbooks, and knowledge base articles. A 3-year review cycle is in place for documents if no revisions are made beforehand. However, the maturity rating is a 2 because while some controls exist, there is a lack of consistency in documentation across teams, with several teams referring to compliance standards without providing validating documentation. Centralized storage and stricter enforcement of documentation standards would be needed to achieve a higher maturity level.		"Both the cloud service provider (CSP) and cloud service customer (CSC) should develop a ""customized integrated framework"" of audit and assurance policies and procedures. This framework should incorporate/demonstrate compliance to leading industry standards and self-imposed business requirements while providing appropriate coverage of controls to assess the respective cloud environment and corresponding services.
At a minimum, audit and assurance policies and procedures should include:

a. Audit and assurance functions indicating purposes, responsibilities, authorities, and 
accountabilities to ensure organizational independence, professional care, audit objectivity, 
and proficiency,
b. Audit and assurance plans,
c. Audit development policies and procedures to determine criteria and assertions against which 
the subject matter will be assessed, quality assurance and supervision, sufficient and appropriate 
evidence, in accordance with commonly accepted frameworks and audit best practices,
d. Audit reporting to communicate audit results and findings,
e. Follow-up activities to monitor audit findings implementation progress"		0	0			
Audit & Assurance	Independent Assessments	A&A-02	"Conduct independent audit and assurance assessments according to relevant standards at least annually.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		ISO 27001 annual review	3	Standard 3rd party ISO 27001 execution for which this team is only marginally involved relative to inputs		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		Establish a centralized documentation repository using tools like Confluence or SharePoint for audit findings and remediation actions. Ensure that individual teams provide validating documentation for controls and compliance. Implement a process to track remediation actions with clear timelines and responsibilities using Jira for issue tracking and Confluence for documentation. Conduct quarterly internal audits to verify the effectiveness of controls and their alignment with ISO 27001 standards.		"Individual teams provided minimal, verbal convenance to controls. No documentation conveyed or provided to validate. Audit team Controls/ Policies in place:-ISO 27001, 20000, 9002 -Partial GDPR data-Annual external audit from SGS, in alignment to ISO standards-Just completed last surveillance audit, next audit underway"	1	The company undergoes annual external audits from SGS aligned to ISO standards such as ISO 27001, ISO 20000, and ISO 9002. They also have partial GDPR data. However, the maturity rating is only a 1 because individual teams provided minimal verbal assurance of controls without validating documentation. The lack of evidence of a comprehensive, independent audit and assurance program indicates an ad-hoc approach. Detailed audit reports, remediation tracking, and consistent assurance processes would be expected for a higher maturity rating.		"Independent audit and assurance should be free from conflict of interest and undue influence in all matters related to audit and assurance engagements.

The frequency of audit and assurance evaluations should comply with applicable standards, regulations, legal/contractual obligations, and statutory requirements.

The audit and assurance process should assess all applicable CCM domains.
"		0.6	3			
Audit & Assurance	Risk Based Planning Assessment	A&A-03	"Perform independent audit and assurance assessments according to risk-based plans and policies.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		PSRT ecosystem	2	"Some risk based plans and policies leveraged - generally undefined. Policy and procedure updates for ISO 27001 are done in collaboration with an India-based Striker team. The first year updates are targeted for completion by August.
"		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		Develop a risk-based audit plan in collaboration with the India-based Striker team. Use risk assessment frameworks like COSO or ISO 31000. Implement a risk management tool like RSA Archer or LogicManager to document and track risk-based audit plans. Ensure that the audit plan is reviewed and updated annually based on risk assessments.		No relevant controls found.	0	No relevant controls found.		"Independent audit and assurance assessments should be based on risk-based plans that define audit objectives, scope, resources, timeline and deliverables, documentation and reporting requirements, use of relevant technology and data analysis techniques, costs, communication, and escalation protocols.

Both CSPs and CSCs may take guidance from industry standards like the Committee of Sponsoring Organizations (COSO) or the International Organization for Standardization (ISO) 31000 for risk management and risk-based planning.
"		0.4	2			
Audit & Assurance	Requirements Compliance	A&A-04	"Verify compliance with all relevant standards, regulations, legal/contractual,
and statutory requirements applicable to the audit.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No controls identified	0	Group not responsible/ involved and reliant on alternate Stryker team		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"Implement a formal risk assessment process using tools like RiskWatch or Resolver. Engage with legal and compliance teams to ensure data-related standards comply with GDPR and other regulations. Assign a Data Protection Officer (DPO) to oversee compliance. Use a GRC (Governance, Risk, and Compliance) platform like RSA Archer to track compliance with all relevant standards, regulations, and legal requirements.

Verify compliance with all relevant standards applicable to the audit, such as:

a. Country regulations
b. Standards and certifications
c. Industry sector regulations
d. International applicable regulations such as those regarding privacy and cybersecurity"		"Individual teams provided minimal, verbal convenance to controls. No documentation conveyed or provided to validate. Audit team Controls/Policies in place:-No formal risk assessment, but general security and risky standards go through leadership review-Data related standards must use legal and compliance, and EU compliance for GDPR assessments-DPO assigned Sarah Knight (Global Privacy Officer)-Contractors held to same training requirements-Need to meet with supplier team (Heather Maurer)"	1	The company has some controls related to compliance verification, such as leadership review of security standards, involvement of legal and compliance teams for data-related standards, and assignment of a Data Protection Officer (DPO) for GDPR. Contractors are held to the same training requirements as employees. However, the maturity rating is only a 1 because there is no formal risk assessment process, and individual teams provided minimal assurance of controls without supporting documentation. The need to meet with the supplier team for further information indicates gaps in the compliance verification process. A structured, documented approach to ensuring compliance with all relevant standards and regulations would be expected for a higher rating.		"Verify compliance with all relevant standards applicable to the audit, such as:

a. Country regulations
b. Standards and certifications
c. Industry sector regulations
d. International applicable regulations such as those regarding privacy and cybersecurity
"		0	0			
Audit & Assurance	Audit Management Process	A&A-05	"Define and implement an Audit Management process to support audit planning, risk analysis, security control assessment, conclusion, remediation 
schedules, report generation, and review of past reports and supporting evidence.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		ISO 27001 annual review	2	"Policy and procedure updates for ISO 27001 are done in collaboration with an India-based Striker team. The first year updates are targeted for completion by August.
"		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"Audit management process security should include:

a. Secure role-based access and authorization and secure communication and storage.
b. Controls to protect audit data confidentiality, integrity, and availability.
c. Periodic reporting, including issues and remediation plans per organizational requirements."		"Individual teams (with exception of 3rd Party Risk) provided minimal, verbal convenance to controls. No documentation conveyed or provided to validate. Audit team Controls/ Polices in place:-Annual surveillance audit (sampling), every 3 years is full recertification-Results sent to leadership-No noncompliance noted in recent past-3 month remediation for major-1 year for minor, OFI disposition log-CI portal for tracking for decisions3rd Party Risk team maintains:- Risk Assessment Process- Inherent Risk Questionnaire- Vendor questionnaire- BitSight scoring system for high risk vendors"	2	The company has an audit management process that includes annual surveillance audits with sampling, full recertification every 3 years, and reporting of results to leadership. Noncompliance issues are remediated within defined timeframes (3 months for major, 1 year for minor) and tracked in an OFI disposition log and CI portal. The 3rd Party Risk team maintains a risk assessment process, inherent risk questionnaire, vendor questionnaire, and BitSight scoring for high-risk vendors. However, the maturity rating is a 2 because while some audit management controls exist, most teams provided minimal verbal assurance without validating documentation. The lack of a comprehensive, consistently followed audit management process across all teams prevents a higher rating. Detailed evidence of risk analysis, security control assessment, remediation tracking, and regular review of past reports would be needed to demonstrate a more mature audit management program.		"Audit management process security should include:

a. Secure role-based access and authorization and secure communication and storage.
b. Controls to protect audit data confidentiality, integrity, and availability.
c. Periodic reporting, including issues and remediation plans per organizational requirements.
"		0.4	2			
Audit & Assurance	Remediation	A&A-06	"Establish, document, approve, communicate, apply, evaluate and maintain a risk-based corrective action plan to remediate audit findings, review and report remediation status to relevant stakeholders.
"		Manual process for tickets being created based on risk findings from LifeNet/Stryker, but no long term, risk-driven, or published findings.	2	Reactive, based on external alerts with no proactive or strategic reviews. Complete coverage, based on tickets from LifeNet of known issues. Uncertainty on how to document unknown or unattributed issues.		No controls identified	0	No controls identified		quarterly review + ORCA bi month review + alerts on critical CVE + review at each release + code review + sonar cloud on each development	3	3rd party pen tests executed against stage servers for Blueprint OMS 3.4.0,  Blueprint 4.2.0		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"The organization should document a well-defined remediation plan that includes:

a. Remediation tasks and their risk levels.
b. Proactive, continuous monitoring (where applicable) to identify anomalies using a risk-based approach.
c. Specific task owners.
d. Milestones with due dates.
e. Deliverables and current status.

The organization should document, communicate, and enforce change management best practices to address audit findings based on a risk-based approach.
"		Individual teams provided minimal, verbal convenance to controls. No documentation conveyed or provided to validate.	1	Individual teams provided minimal verbal assurance of controls related to a risk-based corrective action plan, but no validating documentation was conveyed or provided. The lack of evidence of a documented, consistently applied process for remediating audit findings and communicating remediation status to stakeholders indicates an ad-hoc approach at best. A well-defined, centrally managed corrective action program with clear ownership, timelines, and reporting would be expected for a higher maturity rating.		"The organization should document a well-defined remediation plan that includes:

a. Remediation tasks and their risk levels.
b. Proactive, continuous monitoring (where applicable) to identify anomalies using a risk-based approach.
c. Specific task owners.
d. Milestones with due dates.
e. Deliverables and current status.

The organization should document, communicate, and enforce change management best practices to address audit findings based on a risk-based approach.
"		1	2.5			
Application & Interface Security	Application and Interface Security Policy and Procedures	AIS-01	"Establish, document, approve, communicate, apply, evaluate and maintain
policies and procedures for application security to provide guidance to the
appropriate planning, delivery and support of the organization's application
security capabilities. Review and update the policies and procedures at least
annually.
"		Manual process for migration of selected services to Azure with Stryker teams.	1	Ongoing migrations to Azure, but no overall review or guidance of security in AWS for long term support.		Sporadic controls for risk assessment, cloud migration, and updating	1	Ad-hoc and inconsistent application of assessment and planning of cloud usage.		No controls identified	0	No controls identified		Some application security policies and procedures are mentioned, like penetration testing and automated security testing in the QA environment, but there are no details on them being documented, approved, and reviewed annually.	2	1. Regular penetration testing is conducted on the 3D Planner and LMS components, showing some application security practices. 2. Automated security testing like DAST is performed in the QA environment, but the details and frequency are unclear. 3. There is a lack of evidence of documented application security policies and procedures that are reviewed and updated annually.		No relevant controls found.	0	No relevant controls found.		"Develop a comprehensive application security policy using industry standards like OWASP ASVS. Implement tools like SonarQube for static code analysis, Synopsys Black Duck for software composition analysis, and OWASP ZAP for dynamic application security testing. Integrate these tools into the CI/CD pipeline using Jenkins or GitLab CI. Conduct regular security training sessions for development teams on secure coding practices.
Ensure reviews are conducted by management periodically or after significant changes."		"AppSec Team: - App Sec Playbook in Stryker SharePoint- SAST: team in place for Sonarcloud, shift left in new dev, threat modelling Sdelements, no current DAST tooling, Stryker employs a secure software development life cycle (SDLC) for their in-house developed applications. Their SDLC includes the following key phases and practices:- Threat modeling using SD Elements to identify and mitigate potential security risks early in the development process.- Static application security testing (SAST) using SonarCloud to scan source code for vulnerabilities. Developers are required to remediate all critical vulnerabilities identified by SonarCloud before proceeding to the next phase of the SDLC. Lower severity vulnerabilities can be addressed over time based on risk and priority.- Dynamic application security testing (DAST) is performed, although the specific DAST tool being used is not mentioned.- Software composition analysis (SCA) using Synopsys Blackduck to identify and manage vulnerabilities in third-party libraries and components.- Manual code reviews and approval gates at each phase of the SDLC.- Automated enforcement of security policies and standards through the CI/CD pipeline, including gating deployments on passing SAST scans.- Penetration testing conducted by internal security teams. -M&A Cloud coverage: only Orca coverage, no threat modelling, SonarCloud, BlackDuck"	3	The company has established application security policies and procedures, documented in an App Sec Playbook stored in Stryker Sharepoint. They employ a secure software development lifecycle (SDLC) that includes threat modeling using SD Elements, static application security testing (SAST) with SonarCloud, dynamic application security testing (DAST), software composition analysis (SCA) using Synopsys Blackduck, manual code reviews, and automated enforcement of security policies in the CI/CD pipeline. Penetration testing is conducted by internal security teams. For M&A cloud coverage, they use Orca for scanning but lack threat modeling. The maturity rating is a 3 because while they have documented policies and a range of security tools and practices integrated into the SDLC, some gaps exist, such as the lack of a specific DAST tool and threat modeling for cloud M&A. More comprehensive coverage and evidence of regular review and updating of the policies would be needed for a higher rating.		"The policy should:

a. Include defined roles and responsibilities supported by regular workforce training.
b. Align with organizational purpose and strategy.
c. Provide a framework for setting application security baselines (e.g., NIST, ISO, OWASP, and CIS benchmarks).
d. Guide the development of application security controls.
e. Include a commitment to satisfy applicable requirements and continual improvement.
f. Cover all relevant applications regardless of whether they are developed in-house or via one’s supply chain.
g. Promote the use of an established software development lifecycle (SDLC) in software development, including code review, secure coding training, testing (functional, regression, security, etc.), vulnerability testing, and change management.
h. Ensure vulnerability processes are followed with regular patching, scanning, and remediation before production deployment.
i. Be reviewed by management periodically or after significant changes.
"		0.8	1.333333333			
Application & Interface Security	Application Security Baseline Requirements	AIS-02	"Establish, document and maintain baseline requirements for securing
different applications.
"		No process, mostly manual for updating software versions on EC2 instances	1	Ongoing migrations to Azure, but no overall review or guidance of security in AWS for long term support.		Some controls (Cloudtrail, Clearscale, Qualys, Nessus) in place.	1	Controls are not widely deployed and limited proactive alerting, reactive focus.		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		Establish baseline security requirements for applications using CIS benchmarks. Implement tools like Qualys or Nessus for continuous vulnerability scanning. Use Terraform or Ansible for automated configuration management and enforcement of security baselines. Ensure that all applications are reviewed against these baselines quarterly.		"AppSec Team: Black Duck SCA Tool Functionality: Open-source vulnerability Management Detects Inventory all open source in apps & containers. Protect by finding and fixing known open-source vulnerabilities in development and production. Black Duck - Requirements to initiate Tool: Will the application under assessment require the following: Security Risk details License risks Operational risk -Pentesting or 3rd Party scanning: BlackDuck -API sec testing: Genesis Zamora, in progress"	2	The company uses Black Duck for software composition analysis (SCA) to manage open-source vulnerabilities in applications and containers. Black Duck detects and inventories open-source components, identifies known vulnerabilities, and helps remediate them in development and production. Initiating a Black Duck scan requires providing security risk details, license risks, and operational risks for the application. Third-party penetration testing is also performed using Black Duck. API security testing is in progress under Genesis Zamora. The maturity rating is a 2 because while they have some tools and processes for securing applications, such as SCA and penetration testing, the baseline requirements are not comprehensively documented. The lack of information on the scope and consistency of application security practices across the organization limits the rating. More detailed standards, guidelines, and evidence of their systematic enforcement would be needed to demonstrate a higher level of maturity.		"At a minimum, baseline requirements should include:

a. An alignment with established application security policies and industry standards.
b. Risk assessment (business, technical risks) to evaluate application security alignment with the baseline and the performance of regular auditing (scanning/monitoring) to ensure such alignment is achieved.
c. A consideration for unique requirements and characteristics of each application.
d. Consideration and integration of lessons learned from issues/incidents back into the security policy.
e. Incorporation of guidelines on how to meet and/or stay aligned with the established baseline.
f. Periodic management review.
"		0.4	1			
Application & Interface Security	Application Security Metrics	AIS-03	"Define and implement technical and operational metrics in alignment
with business objectives, security requirements, and compliance obligations.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"Actionable metrics should be defined with consideration to business goals, the criticality of service, security requirements, and compliance obligations.

Example technical metrics include:
• Count or percentage of vulnerabilities by weakness.
• Count or percentage of vulnerabilities by severity.
• Count or percentage of vulnerabilities by detection source (design review, code review, SAST, DAST, penetration test, VDP, or bug bounty).
• Count or percentage of vulnerabilities by environment detected (pre-production vs. production).
• Average time to resolution.
• Count exceeding remediation service level objectives (SLOs).

Example operational metrics include:
• Count or percentage of applications using automated security testing by test type (SAST, DAST, SCA).
• Count or percentage of applications have completed penetration testing in the last “n” months.
• Count or percentage of development teams or individuals who have completed application security training in the last “n” months.
• Count of proactive engagements by development and business teams.
• Results from surveys delivered to application security customers, such as business and development teams.

Reporting:
Reporting should be designed with various users in mind. For example, security professionals, engineering teams, business stakeholders, and executives will often have different interests requiring specialized views, filtering, and delivery mechanisms.

a. The collection, visualization, and distribution of reporting data should be automated.
b. Data may be further analyzed using application criticality, business units, platforms, languages, and other factors relevant to the viewer.
c. Compare actual metrics to standards to evaluate performance.
d. Enable comparisons over time to identify trends.
e. Enable correlations, such as relating a reduction in vulnerabilities of a specific type after new tools or training.
"		No relevant controls found.	0	No relevant controls found.		"Actionable metrics should be defined with consideration to business goals, the criticality of service, security requirements, and compliance obligations.

Example technical metrics include:
• Count or percentage of vulnerabilities by weakness.
• Count or percentage of vulnerabilities by severity.
• Count or percentage of vulnerabilities by detection source (design review, code review, SAST, DAST, penetration test, VDP, or bug bounty).
• Count or percentage of vulnerabilities by environment detected (pre-production vs. production).
• Average time to resolution.
• Count exceeding remediation service level objectives (SLOs).

Example operational metrics include:
• Count or percentage of applications using automated security testing by test type (SAST, DAST, SCA).
• Count or percentage of applications have completed penetration testing in the last “n” months.
• Count or percentage of development teams or individuals who have completed application security training in the last “n” months.
• Count of proactive engagements by development and business teams.
• Results from surveys delivered to application security customers, such as business and development teams.

Reporting:
Reporting should be designed with various users in mind. For example, security professionals, engineering teams, business stakeholders, and executives will often have different interests requiring specialized views, filtering, and delivery mechanisms.

a. The collection, visualization, and distribution of reporting data should be automated.
b. Data may be further analyzed using application criticality, business units, platforms, languages, and other factors relevant to the viewer.
c. Compare actual metrics to standards to evaluate performance.
d. Enable comparisons over time to identify trends.
e. Enable correlations, such as relating a reduction in vulnerabilities of a specific type after new tools or training.
"		0	0			
Application & Interface Security	Secure Application Design and Development	AIS-04	"Define and implement a SDLC process for application design, development,
deployment, and operation in accordance with security requirements defined by
the organization.
"		"Inside of the AWS subscription, no defined process for deployment since the environment is static aside from updates. 

The CI/CD tools inside the cloud tenant do enabled SDLC processes for the Physio team though."	2	Limited scope due to nonproduction usage.		Controls for new solution identified and in place in accordance with standards, but does not apply to entire environment.	2	Manual and reactive, but limited new deployments.		"No defined process. For application and infrastructure monitoring, they use several tools:
- Imperva web application firewall to check for bot attacks, illegal access, etc.
- Orca CSPM to scan and evaluate their security posture 
- Aqua scan to check for vulnerabilities in VM images
- They also scan VMs with BlackDuck and Tenable twice
- AWS CloudTrail integrated with CloudWatch to monitor all actions in the AWS account"	3	No defined process. For application and infrastructure monitoring, scanning and reporting of vulnerabilities and monitoring of firewalls exist		A Software Development Lifecycle (SDLC) process is referenced in terms of the deployment process progressing through different environments (Edge, Test, QA, Production), but there are no specifics on it being defined and implemented in accordance with security requirements.	2	1. The deployment process involves moving changes through different environments, indicating some form of an SDLC process. 2. However, there are no clear details on the SDLC process being formally defined and implemented in alignment with specific security requirements. 3. While an SDLC process seems to be in place based on the deployment workflow, there is a lack of evidence of it comprehensively incorporating security requirements as required by this control.		Code scans are performed at the build process for Kubernetes workloads and VM-based deployments. Static code analysis and unit test cases are conducted on the security side.	2	The company performs code scanning and static code analysis as part of their CI/CD pipeline for Kubernetes and VM-based deployments. Unit testing is also conducted from a security perspective. However, there is no mention of a fully defined SDLC process that incorporates security requirements throughout the application lifecycle. The maturity rating is a 2 due to the existence of some security testing practices, but lack of evidence of a comprehensive, documented SDLC process.		"Defining security requirements should be the first step in the secure software development lifecycle (SSDLC) process to ensure that security is integrated into the product from its creation. All security requirement aspects should be considered from functional, physical, and business requirements perspectives. In addition, security requirements should derive from security objectives and/or organizational goals and regulatory requirements. Industry standards should be applied at project inception and every stage of the SSDLC process—including requirements analysis, design, coding, testing, deployment, and end-of-life (EoL) processes.

To successfully enable SSDLC security, roles and expectations should be clearly defined and published, and an inventory of applications and their metadata should exist in an easily accessible format.

Appropriate security practice examples for the common stages of an SSDLC are provided below to include the following categories: training, requirements, design, development, testing, and release and response.

A. Training:
a. Role-based secure development training should be required at multiple stages of employment (or other contractual relationships), including on-boarding and role changes.
b. Refresher training should be delivered throughout one's career, regardless of position or movement in their organization.
c. Targeted, specialty training should be created and made available as the organization adopts new technologies.
d. Progressively advanced training should be made available to relevant employees (and contractors whenever applicable) as they transition through technical roles and/or champion program participants.

B. Requirements:
a. Generic and specialized security requirements should be defined, published, organized, and easily accessible to all organizational roles.
b. Every application, during each iteration, should review existing requirements and research if additional requirements are necessary. It is beneficial for the engineering teams to consult with a security professional at this time.

C. Design:
a. Security-focused design reviews are conducted.
b. Threat models are developed or modified.
c. The design of new or enhanced security controls, required by the application design, is developed.

D. Development:
a. Develop, as per design specifications.
b. Abuse cases are used to develop a security-focused unit and integration tests during development.
c. Secure coding practices are implemented and enforced through automation and manual peer code reviews.

E. Security Testing:
a. Manual and automated test plans are developed and executed with abuse cases in mind.
b. Automation may include one or more of SCA, SAST, DAST, IAST, fuzzing, credential scans, etc.
c. Penetration testing may be executed during this stage, based on need.
d. Crowdsourced testing or private bug bounty programs may be implemented.

F. Release:
a. Change control is instituted, including gating and documenting releases to ensure requirements and compliance objectives are met.

G. Response:
a. Monitoring and alerting are in place to identify security issues and enable response activities.
b. A response plan exists and can be easily executed when a security issue is discovered.
c. A process is established for monitoring external sources for vulnerability disclosures and responding when applicable.
"		"AppSec Team: (Docs provided):Vulnerability Scan Requirements Ticket requester must share Project Name: Ticket requester must estimate lines of code: Ticket requester must perform sign up with Sonar Cloud at this link: Login - SonarCloudTicket requester must have access to the specific Application Code to have the vulnerability scan completed.Controls:Sonarcloud, dev team joins Joel Hatland call to ask vuln scan requirements questionsDev team signs up to SonarCloud with MFA, then team user can plugin CI/CD pipeline in to SonarCloudPolicy for SonarCloud detections? Need to followupProcess: env escalation from non-prod, need to see how often code is scanned during deployment model Metrics for success: alerts or remediations, not stopped for issues except criticals, approval process for non-critical exceptions. Black Duck is used for software composition analysis (SCA) to identify vulnerabilities in third-party components. Stryker's Drupal-based content management system (CMS), used for internal research and analysis of surgical data, is hosted on hardened Amazon EC2 instances behind a VPN gateway. Access requires authentication through SecurID MFA. Azure WAF and Azure Front Door are used to protect the EC2-hosted web applications. Amazon Aurora encrypted using AES-256. All data in transit is encrypted using TLS 1.2. Developers connect to AWS environments using SSH with RSA keys. Stryker's new serverless AWS environment, built using AWS Lambda, API Gateway, S3, and Aurora, leverages similar data security controls:- All data in transit is encrypted using HTTPS/TLS. - Amazon S3 buckets are encrypted using AES-256 and access is restricted through IAM policies and bucket policies. - Aurora databases are encrypted at rest using AES-256.- Secure key management and rotation is handled using AWS KMS.- Secrets are stored using AWS Secrets Manager and encrypted using KMS."	3	The company has a defined SDLC process that incorporates security practices. Vulnerability scanning requirements are documented, mandating the use of SonarCloud for static code analysis. Developers must sign up for SonarCloud with MFA and integrate it into their CI/CD pipeline. The process involves escalating code through environments, with critical vulnerabilities blocking deployment. Metrics track alerts and remediations, with an approval process for non-critical exceptions. Black Duck is used for SCA. The Drupal CMS is hosted on hardened EC2 instances behind a VPN gateway, with MFA access. Azure WAF and Front Door protect web apps. Encryption is used for data at rest (AES-256 for Aurora and S3) and in transit (TLS 1.2). The serverless AWS environment follows similar practices. The maturity rating is a 3 because while they have a documented SDLC process with multiple security tools and controls, some gaps exist, such as the lack of a defined policy for SonarCloud detections and uncertainty around the frequency of scans during deployment. More comprehensive documentation and evidence of consistent application would be needed for a higher rating.		"Defining security requirements should be the first step in the secure software development lifecycle (SSDLC) process to ensure that security is integrated into the product from its creation. All security requirement aspects should be considered from functional, physical, and business requirements perspectives. In addition, security requirements should derive from security objectives and/or organizational goals and regulatory requirements. Industry standards should be applied at project inception and every stage of the SSDLC process—including requirements analysis, design, coding, testing, deployment, and end-of-life (EoL) processes.

To successfully enable SSDLC security, roles and expectations should be clearly defined and published, and an inventory of applications and their metadata should exist in an easily accessible format.

Appropriate security practice examples for the common stages of an SSDLC are provided below to include the following categories: training, requirements, design, development, testing, and release and response.

A. Training:
a. Role-based secure development training should be required at multiple stages of employment (or other contractual relationships), including on-boarding and role changes.
b. Refresher training should be delivered throughout one's career, regardless of position or movement in their organization.
c. Targeted, specialty training should be created and made available as the organization adopts new technologies.
d. Progressively advanced training should be made available to relevant employees (and contractors whenever applicable) as they transition through technical roles and/or champion program participants.

B. Requirements:
a. Generic and specialized security requirements should be defined, published, organized, and easily accessible to all organizational roles.
b. Every application, during each iteration, should review existing requirements and research if additional requirements are necessary. It is beneficial for the engineering teams to consult with a security professional at this time.

C. Design:
a. Security-focused design reviews are conducted.
b. Threat models are developed or modified.
c. The design of new or enhanced security controls, required by the application design, is developed.

D. Development:
a. Develop, as per design specifications.
b. Abuse cases are used to develop a security-focused unit and integration tests during development.
c. Secure coding practices are implemented and enforced through automation and manual peer code reviews.

E. Security Testing:
a. Manual and automated test plans are developed and executed with abuse cases in mind.
b. Automation may include one or more of SCA, SAST, DAST, IAST, fuzzing, credential scans, etc.
c. Penetration testing may be executed during this stage, based on need.
d. Crowdsourced testing or private bug bounty programs may be implemented.

F. Release:
a. Change control is instituted, including gating and documenting releases to ensure requirements and compliance objectives are met.

G. Response:
a. Monitoring and alerting are in place to identify security issues and enable response activities.
b. A response plan exists and can be easily executed when a security issue is discovered.
c. A process is established for monitoring external sources for vulnerability disclosures and responding when applicable.
"		2.2	2.2			
Application & Interface Security	Automated Application Security Testing	AIS-05	"Implement a testing strategy, including criteria for acceptance of
new information systems, upgrades and new versions, which provides application
security assurance and maintains compliance while enabling organizational speed
of delivery goals. Automate when applicable and possible.
"		Manual update processes in place	2	Ad-hoc process for updating 		No controls identified	1	Ad-hoc process for updating 		Selenium test automation written by V&V 	2	No defined test strategy. More reactive test automation 		- Blue-green deployment approach for updating production environment. - Deployment process involves progressively moving changes through Edge (dev), Test, QA, and Production environments. - Regular penetration testing on 3D Planner and LMS components. - Automated security testing (DAST) performed on QA environment.	4	1. Well-defined deployment process with multiple environments enables thorough testing before production. 2. Regular penetration testing provides assurance of application security. 3. Automated security testing in QA environment helps maintain compliance and identify vulnerabilities early.		No relevant controls found.	0	No relevant controls found.		"Implement a robust automated testing strategy using tools like OWASP ZAP for DAST, SonarQube for SAST, and Synopsys Black Duck for SCA. Integrate these tools into the CI/CD pipeline using Jenkins or GitLab CI. Establish criteria for acceptance of new information systems and updates, and automate security testing at each stage of the development lifecycle. Conduct regular audits to ensure compliance with the testing strategy.

Strategy:
a. Identify the goals and requirements of the automation implementation.

Example goals:
• Security requirements are not relaxed to improve speed.
• All developers can leverage tools to detect security weaknesses while developing software.
• All third-party libraries are scanned for known vulnerabilities.
• All authentication and authorization functions “pass” abuse case unit tests before deployment.
• All website security headers are verified to meet security requirements when deployed.

Example requirements:
• Applicable programming languages should be supported by static analysis tools.
• Python and C# should be supported by select static analysis tools.
• Automation should not require infrastructure support.
• All automation tools should offer an application programming interface (API).
• All website security headers are verified to meet security requirements when deployed.

Strategy can also include, but is not limited to:
b. Security testing for unintentional side effects and behaviors that are not specified in the test plan or design.
c. Security testing for incident response procedures, such as simulating breaches.
d. Determining which portfolio applications warrant investment in automation. Prioritize the adoption order based on criticality.

Considerations:
e. Security requirements
f. Risk, business, and compliance requirements
g. Development methodology
h. Lifecycle
i. Metrics establishment

Example:
• Count or percentage of (test type) adoption among applications requiring (test type) SAST, DAST, SCA, etc.
• Count or percentage of false positives produced by test automation.
• Count or percentage of execution-time SLA breaches by test automation.
• Soft measures, including satisfaction levels with usability.
• Change in the number of security weaknesses discovered after release.
• Percentage coverage of automated test cases for exposed APIs and SDK functions by service (i.e., the total number of automated test cases for APIs/SDK functions; the total number of APIs/SDK by service).
• Evaluate test types to determine which is best suited for different categories of applications based on the attributes of those in the prioritized inventory.

Considerations:
• Development and security team sizes
• Platform and operating systems
• Maturity of build automation
• Language support

Execution:
a. Avoid approaches that cause unreasonable delays to builds and deployments or require significant process modification or resource commitment from development teams.
b. Seek to adopt automation at multiple SDLC integration points

Example integration points:
            1. A plugin in the developer's integrated development environment (IDE).
            2. Abuse case unit and integration tests—created and maintained by developers—and executed during development and build cycles.
            3. Static application security testing or SCA scans executed during automated builds.
            4. Dynamic application security testing scans executed during automated deployment.

c. Automate patching when possible.
d. Use metrics to drive feedback loops and continuous improvement.

            1. Maintain an accurate count of license utilization.
            2. Tune automation to reduce false positives and false negatives.
            3. Analyze gaps in support and trends for response and planning.

e. Continue to leverage manual testing for scenarios not easily tested with automation.
"		"AppSec Team:-Human reviews needed-Code signing or tagging: need review-Orca for scanning across env-Scanning for legacy/non-updated apps: Orca looking at SBOM, taskforce asking for more connections/actions, CCOE to look at old/unused envs"	2	The company's testing strategy includes human code reviews, Orca for scanning across environments, and checking software bills of materials (SBOMs) for legacy or non-updated applications. A task force is working on increasing connections and actions based on Orca findings, and the Cloud Center of Excellence (CCOE) is examining old/unused environments. However, the need for reviewing code signing/tagging processes is acknowledged. The maturity rating is a 2 because while some testing practices are in place, such as Orca scanning and human reviews, there are gaps in the strategy, such as the lack of a defined code signing/tagging process. The need for more connections and actions based on Orca findings suggests that the testing is not yet fully effective in driving remediation. A more comprehensive, consistently applied testing strategy with clear acceptance criteria and automated enforcement would be needed for a higher maturity rating.		"Note: The implementation guidelines of AIS-05 should be interpreted as further guidance in addition to what is specified in AIS-03 and AIS-04.

Automation of security testing should be implemented to reduce risks and errors and enable the scaling of security practices to meet organizational demands. Multiple test types and integration points will likely be needed to provide the appropriate level of assurance throughout the SDLC. Criteria should be developed for use when assessing the automation required by an application, as not all systems will benefit equally.

Strategy:
a. Identify the goals and requirements of the automation implementation.

Example goals:
• Security requirements are not relaxed to improve speed.
• All developers can leverage tools to detect security weaknesses while developing software.
• All third-party libraries are scanned for known vulnerabilities.
• All authentication and authorization functions “pass” abuse case unit tests before deployment.
• All website security headers are verified to meet security requirements when deployed.

Example requirements:
• Applicable programming languages should be supported by static analysis tools.
• Python and C# should be supported by select static analysis tools.
• Automation should not require infrastructure support.
• All automation tools should offer an application programming interface (API).
• All website security headers are verified to meet security requirements when deployed.

Strategy can also include, but is not limited to:
b. Security testing for unintentional side effects and behaviors that are not specified in the test plan or design.
c. Security testing for incident response procedures, such as simulating breaches.
d. Determining which portfolio applications warrant investment in automation. Prioritize the adoption order based on criticality.

Considerations:
e. Security requirements
f. Risk, business, and compliance requirements
g. Development methodology
h. Lifecycle
i. Metrics establishment

Example:
• Count or percentage of (test type) adoption among applications requiring (test type) SAST, DAST, SCA, etc.
• Count or percentage of false positives produced by test automation.
• Count or percentage of execution-time SLA breaches by test automation.
• Soft measures, including satisfaction levels with usability.
• Change in the number of security weaknesses discovered after release.
• Percentage coverage of automated test cases for exposed APIs and SDK functions by service (i.e., the total number of automated test cases for APIs/SDK functions; the total number of APIs/SDK by service).
• Evaluate test types to determine which is best suited for different categories of applications based on the attributes of those in the prioritized inventory.

Considerations:
• Development and security team sizes
• Platform and operating systems
• Maturity of build automation
• Language support

Execution:
a. Avoid approaches that cause unreasonable delays to builds and deployments or require significant process modification or resource commitment from development teams.
b. Seek to adopt automation at multiple SDLC integration points

Example integration points:
            1. A plugin in the developer's integrated development environment (IDE).
            2. Abuse case unit and integration tests—created and maintained by developers—and executed during development and build cycles.
            3. Static application security testing or SCA scans executed during automated builds.
            4. Dynamic application security testing scans executed during automated deployment.

c. Automate patching when possible.
d. Use metrics to drive feedback loops and continuous improvement.

            1. Maintain an accurate count of license utilization.
            2. Tune automation to reduce false positives and false negatives.
            3. Analyze gaps in support and trends for response and planning.

e. Continue to leverage manual testing for scenarios not easily tested with automation.
"		1.8	2.25			
Application & Interface Security	Automated Secure Application Deployment	AIS-06	"Establish and implement strategies and capabilities for secure, standardized,
and compliant application deployment. Automate where possible.
"		Manual update processes in place	2	Ad-hoc process for updating 		Controls in place for new solution, but not for existing solutions.	1	Not complete coverage		ORCA score + Black report	1	No defined test strategy. More reactive test automation 		- Blue-green deployment approach for updating production environment. - Deployment process involves progressively moving changes through Edge (dev), Test, QA, and Production environments.	3	1. Standardized deployment process with multiple environments promotes compliance. 2. Blue-green deployment enables seamless updates while maintaining availability. 3. Automation of deployment process is not explicitly mentioned, leaving room for improvement.		No relevant controls found.	0	No relevant controls found.		"The strategies should include:
a. Defined security and automation requirements based on an organization's application deployment needs and standards.
b. Defined roles and responsibilities between security, application teams, and other stakeholder groups.
c. Identification and integration with existing application deployment processes.
d. Customization of secure application deployment for deployment types such as operating systems, network connections, configuration, etc.
e. Logging and monitoring of secure application deployment so that data issues can be promptly addressed by the appropriate people (incident or forensics).
f. Metrics to effectively measure deployment success.

The capabilities should be based on the organization's SSDLC and should include, for instance:
g. Defined and approved list of deployment and automation technologies.
h. Enablement for team members (e.g., developers, administrators, etc.) to dynamically address security issues when needed.

The strategies and capabilities should be reviewed periodically by senior management."		"AppSec Team: Orca rolls up data across BU or env.Stryker has a defined secure development lifecycle including threat modeling (using SD Elements), static code analysis (SonarCloud), and software composition analysis (Black Duck). Dynamic testing and API security testing are future initiatives."	2	The company uses Orca to roll up data across business units and environments for a consolidated view. They have a defined secure development lifecycle that includes threat modeling with SD Elements, static code analysis with SonarCloud, and software composition analysis with Black Duck. However, dynamic testing and API security testing are noted as future initiatives, not yet implemented. The maturity rating is a 2 because while they have some strategies and tools for secure application deployment, such as Orca and elements of a secure SDLC, the lack of dynamic and API testing indicates that the approach is not yet comprehensive. The fact that these are future initiatives suggests they have not yet standardized and automated the process across the organization. More mature application deployment capabilities would include a fully implemented secure SDLC, automated enforcement of security policies, and integration of security testing throughout the pipeline.		"The strategies should include:
a. Defined security and automation requirements based on an organization's application deployment needs and standards.
b. Defined roles and responsibilities between security, application teams, and other stakeholder groups.
c. Identification and integration with existing application deployment processes.
d. Customization of secure application deployment for deployment types such as operating systems, network connections, configuration, etc.
e. Logging and monitoring of secure application deployment so that data issues can be promptly addressed by the appropriate people (incident or forensics).
f. Metrics to effectively measure deployment success.

The capabilities should be based on the organization's SSDLC and should include, for instance:
g. Defined and approved list of deployment and automation technologies.
h. Enablement for team members (e.g., developers, administrators, etc.) to dynamically address security issues when needed.

The strategies and capabilities should be reviewed periodically by senior management.
"		1.4	1.75			
Application & Interface Security	Application Vulnerability Remediation	AIS-07	"Define and implement a process to remediate application security
vulnerabilities, automating remediation when possible.
"		Manual process based on Physio team determination of external tickets for issues	2	Ad-hoc process for updating 		No controls identified	0	No controls identified		Patch or code removal or configuration change handled by OMS team	2	"No defined or implemented process to remediate application security,
vulnerabilities. There is an internal OMS team that handles vulnerability management. When notified of a vulnerability, they assess the ease of patching. Easy patches are done quickly in production, harder ones are scheduled for the next release. Patches are integrated into sprints."		No relevant controls found.	0	No relevant controls found.		Patches are recommended by the DevOps team in collaboration with the development team. Changes go through a control process from development to production.	2	The company has a process where the DevOps team collaborates with the development team to identify and recommend patches for vulnerabilities. These changes then go through a control process as they move from development to production environments. However, there is no clear evidence that this process is fully documented or that remediation is automated where possible. The maturity rating is a 2 based on having a collaborative process in place, but lacking details on documentation and automation.		"Application security remediation should adhere to the following guidelines:
a. Follow defined remediation processes, designed, tested, and implemented by security and application teams.
b. Remediate risks as early in the SDLC as possible, such as during the design or development stages.
c. Have defined roles and responsibilities, including escalation paths for application security incident response and remediation.
d. Follow a risk-based approach to address high-risk incidents that significantly impact application availability, integrity, or confidentiality.
e. Leverage automation when possible to increase remediation efficiency and accuracy.

Processes, roles, responsibilities, and documentation established for application security remediation should be reviewed periodically by management.

Example:
• GitOps-based remediation of application vulnerabilities.
• Automated remediation efficacy metric: total number of remediations of active critical/high vulnerabilities performed through Git for the given period.
• Total number of active critical/ high vulnerabilities identified for the given period."		"AppSec Team: For in prod Orca detections process for remediation: task force to reach out to owner for alerting and tracking"	2	The company has a process for remediating application security vulnerabilities identified by Orca in production. When Orca detects an issue, a task force reaches out to the asset owner for alerting and tracking of the remediation. However, the maturity rating is a 2 because the process seems to be largely manual and reactive, lacking automation. The task force has to manually alert owners and track remediation, suggesting that the vulnerability management process is not yet fully streamlined and efficient. A more mature approach would include automated workflows for ticketing, prioritization, and tracking of vulnerabilities, with SLAs for remediation based on severity. Integration of the vulnerability scanner with a centralized ticketing system and reporting dashboard would enable more proactive management and metrics-driven improvement.		"Application security remediation should adhere to the following guidelines:
a. Follow defined remediation processes, designed, tested, and implemented by security and application teams.
b. Remediate risks as early in the SDLC as possible, such as during the design or development stages.
c. Have defined roles and responsibilities, including escalation paths for application security incident response and remediation.
d. Follow a risk-based approach to address high-risk incidents that significantly impact application availability, integrity, or confidentiality.
e. Leverage automation when possible to increase remediation efficiency and accuracy.

Processes, roles, responsibilities, and documentation established for application security remediation should be reviewed periodically by management.

Example:
• GitOps-based remediation of application vulnerabilities.
• Automated remediation efficacy metric: total number of remediations of active critical/high vulnerabilities performed through Git for the given period.
• Total number of active critical/ high vulnerabilities identified for the given period.
"		1.2	2			
Business Continuity Management and Operational Resilience	Business Continuity Management Policy and Procedures	BCR-01	"Establish, document, approve, communicate, apply, evaluate and maintain
business continuity management and operational resilience policies and procedures.
Review and update the policies and procedures at least annually.
"		No documented BC processes	0	No controls identified		No controls identified	0	No controls identified		"""Depending of what a user has to do. (Least priviledge)
We do continual improvement.
We have written procedure for backup and restoration"""	1	Reactive approach to documentation of BC. Minimal policies or procedures and no evidence of annual updating		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"The policies should include defined roles and responsibilities supported by regular workforce training.

The policies should:
a. Be appropriate to the organization’s purpose.
b. Provide a framework for setting business continuity objectives.
c. Include a commitment to satisfy applicable requirements and continual improvement.
d. Include organizational risk appetite and tolerance to facilitate appropriate planning, delivery, and support of capabilities in the event of a business disruption.
e. Take guidance from industry standards, such as ISO 22300.
"		No relevant controls found.	0	No relevant controls found.		"The policies should include defined roles and responsibilities supported by regular workforce training.

The policies should:
a. Be appropriate to the organization’s purpose.
b. Provide a framework for setting business continuity objectives.
c. Include a commitment to satisfy applicable requirements and continual improvement.
d. Include organizational risk appetite and tolerance to facilitate appropriate planning, delivery, and support of capabilities in the event of a business disruption.
e. Take guidance from industry standards, such as ISO 22300.
"		0.2	1			
Business Continuity Management and Operational Resilience	Risk Assessment and Impact Analysis	BCR-02	"Determine the impact of business disruptions and risks to establish
criteria for developing business continuity and operational resilience strategies
and capabilities.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		yes, we assess the impact based on short and long term impact of all risk that can be exploited.	1	Reactive based with no defined process other than 3rd party scan analysis		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"The business impact analysis (BIA) should incorporate the following components:
a. Identification of critical products and services with their inherent risks.
b. The likelihood and impact of each risk.
c. The organization's risk appetite and tolerance.
d. The identification of risk dependencies.
e. The identification of appropriate and relevant countermeasures to prevent, detect, and react to the identified risks.

The impact analysis should incorporate the following elements:
f. The immediate and ongoing impacts resulting from disruptions.
g. A recovery time objective (RTO) and recovery point objective (RPO).
h. The estimated internal and external resources required for recovery and resumption.
"		No relevant controls found.	0	No relevant controls found.		"The business impact analysis (BIA) should incorporate the following components:
a. Identification of critical products and services with their inherent risks.
b. The likelihood and impact of each risk.
c. The organization's risk appetite and tolerance.
d. The identification of risk dependencies.
e. The identification of appropriate and relevant countermeasures to prevent, detect, and react to the identified risks.

The impact analysis should incorporate the following elements:
f. The immediate and ongoing impacts resulting from disruptions.
g. A recovery time objective (RTO) and recovery point objective (RPO).
h. The estimated internal and external resources required for recovery and resumption.
"		0.2	1			
Business Continuity Management and Operational Resilience	Business Continuity Strategy	BCR-03	"Establish strategies to reduce the impact of, withstand, and recover
from business disruptions within risk appetite.
"		EC2 snapshots with retention	1	Ad-hoc and not complete BC processes.		Low risk due to no retention of PHI/PII or sensitive data, but still required for customer facing applications to work.	1	Ad-hoc and not complete assessment of BC processes.		backup and fallback procedure	1	Minimal documentation available to assess business preparedness or disruption policy/procedures. Business continuity and disaster recovery procedures are not fully documented yet. Their provider Clarinet is responsible for data backups and infrastructure rebuilding in a disaster scenario. The company manager most knowledgeable about BC/DR is currently on an extended leave.		No relevant controls found.	0	No relevant controls found.		Multi-AZ deployment is used within the same region for high availability. Clustered environments are set up across different subnets in the same region. Load distribution ensures continuity if one availability zone goes down.	2	The company utilizes multi-AZ deployments within the same AWS region to provide high availability. Clustered environments are spread across different subnets in the region, and load balancing is used to maintain continuity in the event of an availability zone outage. These strategies help reduce the impact of disruptions. However, there is no mention of a formal process to determine business disruption impacts and establish comprehensive continuity strategies. The maturity rating is a 2 based on the use of multi-AZ deployments and load balancing, but lack of evidence of a holistic, risk-based approach to continuity planning.		"Develop a detailed business continuity plan that includes multi-AZ deployments, load balancing, and failover strategies. Use AWS Elastic Load Balancing and AWS Auto Scaling to ensure high availability and failover. Regularly test these strategies through simulation exercises using AWS Fault Injection Simulator. Document all processes and ensure they are reviewed annually. Engage with vendors like Claranet to ensure they have robust disaster recovery procedures in place.

Business continuity and operational resilience strategies should:
a. Be developed by both cloud service providers and cloud service consumers with consideration of acceptable limits regarding risk appetite and tolerance.
b. Cover all aspects of business continuity and resilience planning—taking inputs from assessed impact and risks—to consider activities for before, during, and after a disruption.
c. Account for the unavailability of all relevant components required to operate the business “as usual” or in a disrupted mode (in parts or total) during a disruption.
d. Cover all actions required to continue and recover prioritized activities within identified timeframes and aligned with organizational risk appetite and tolerance (including the invocation of continuity plans and crisis management capabilities).
e. Cover all activities within the defined scope to protect prioritized activities, reduce disruption likelihood, and limit cloud capability disruption through adequate resourcing.
f. Include detailed solutions and measures for each strategy."		No relevant controls found.	0	No relevant controls found.		"Business continuity and operational resilience strategies should:
a. Be developed by both cloud service providers and cloud service consumers with consideration of acceptable limits regarding risk appetite and tolerance.
b. Cover all aspects of business continuity and resilience planning—taking inputs from assessed impact and risks—to consider activities for before, during, and after a disruption.
c. Account for the unavailability of all relevant components required to operate the business “as usual” or in a disrupted mode (in parts or total) during a disruption.
d. Cover all actions required to continue and recover prioritized activities within identified timeframes and aligned with organizational risk appetite and tolerance (including the invocation of continuity plans and crisis management capabilities).
e. Cover all activities within the defined scope to protect prioritized activities, reduce disruption likelihood, and limit cloud capability disruption through adequate resourcing.
f. Include detailed solutions and measures for each strategy.
"		1	1.25			
Business Continuity Management and Operational Resilience	Business Continuity Planning	BCR-04	"Establish, document, approve, communicate, apply, evaluate and maintain
a business continuity plan based on the results of the operational resilience
strategies and capabilities.
"		No controls identified	0	No controls identified		Source code held and device snapshots created, but restoration process not tested.	1	Ad-hoc and not complete assessment of BC processes.		3rd party Claranet to provides this capability	1	Business continuity and disaster recovery procedures are not fully documented yet. Their provider Clarinet is responsible for data backups and infrastructure rebuilding in a disaster scenario. The company manager most knowledgeable about BC/DR is currently on an extended leave.		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"Develop a comprehensive business continuity plan that includes detailed recovery procedures, roles, and responsibilities. Use tools like Everbridge or Fusion Framework System for managing business continuity plans. Conduct regular drills and tests to ensure plan effectiveness. Ensure that the business continuity plan is reviewed and updated annually or upon significant organizational changes.

Business continuity plans should be accessible and available to those with the need-to-know and include the following elements:
a. Defined purpose and scope, aligned with relevant dependencies.
b. Assigned roles and responsibilities (i.e., review, update, and approval).
c. Defined lines of communication, roles, and responsibilities.
d. Detailed recovery procedures, manual workaround, and reference information.
e. Method for plan invocation.

The plans should be tested and reviewed at planned intervals (e.g., annually or upon significant organizational or environmental changes)."		No relevant controls found.	0	No relevant controls found.		"All relevant business continuity plans should be developed consistently to address priorities for operational resilience, testing, maintenance, and information security requirements.

Business continuity plans should be accessible and available to those with the need-to-know and include the following elements:
a. Defined purpose and scope, aligned with relevant dependencies.
b. Assigned roles and responsibilities (i.e., review, update, and approval).
c. Defined lines of communication, roles, and responsibilities.
d. Detailed recovery procedures, manual workaround, and reference information.
e. Method for plan invocation.

The plans should be tested and reviewed at planned intervals (e.g., annually or upon significant organizational or environmental changes).
"		0.4	1			
Business Continuity Management and Operational Resilience	Documentation	BCR-05	"Develop, identify, and acquire documentation that is relevant to
support the business continuity and operational resilience programs. Make the
documentation available to authorized stakeholders and review periodically.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		"Claranet have plan to restore everything in case of disaster"	1	Clarinet is responsible for data backups and infrastructure rebuilding in a disaster scenario. The company manager most knowledgeable about BC/DR is currently on an extended leave. Business continuity and disaster recovery procedures are not fully documented yet.		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"The documentation should include but is not limited to:
a. Administrator and user guides
b. Database backup and replication guidelines
c. Architecture diagrams
d. Incident playbooks

Documentation availability is intended to support successful continuity of the following activities:
e. Configuring, installing, deploying changes, and operating the system and/or infrastructure.
f. Effectively using the system’s security and business continuity features.
g. Using system automation and structured playbooks where available for fast incident recovery.

The documentation should be interconnected and comparable."		No relevant controls found.	0	No relevant controls found.		"The documentation should include but is not limited to:
a. Administrator and user guides
b. Database backup and replication guidelines
c. Architecture diagrams
d. Incident playbooks

Documentation availability is intended to support successful continuity of the following activities:
e. Configuring, installing, deploying changes, and operating the system and/or infrastructure.
f. Effectively using the system’s security and business continuity features.
g. Using system automation and structured playbooks where available for fast incident recovery.

The documentation should be interconnected and comparable.
"		0.2	1			
Business Continuity Management and Operational Resilience	Business Continuity Exercises	BCR-06	"Exercise and test business continuity and operational resilience
plans at least annually or upon significant changes.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		"We test the DB backup procedure but not something as heavy as a total infrastructure disaster"	1	Team relies on Calaranet however, plans and annual exercises don't appear available or aligned with a schedule		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"Exercise and test business continuity and operational resilience plans at least annually or upon significant changes.

Exercises and tests should include but are not limited to:
a. Processes established in the business continuity plan.
b Alignment with business continuity policies.
c. Critical systems and equipment relevant to the business continuity plan.
d. Roles and responsibilities of the various parties involved in the exercises.
e. The use of CSP support mechanisms in CSC exercises.
f. A review and update of communication templates.
g. Lessons learned from previous events and exercises.
h. Tabletop exercises.

Depending on the level of CSP maturity, the CSP’s practices may include automated chaos testing.
"		No relevant controls found.	0	No relevant controls found.		"Exercise and test business continuity and operational resilience plans at least annually or upon significant changes.

Exercises and tests should include but are not limited to:
a. Processes established in the business continuity plan.
b Alignment with business continuity policies.
c. Critical systems and equipment relevant to the business continuity plan.
d. Roles and responsibilities of the various parties involved in the exercises.
e. The use of CSP support mechanisms in CSC exercises.
f. A review and update of communication templates.
g. Lessons learned from previous events and exercises.
h. Tabletop exercises.

Depending on the level of CSP maturity, the CSP’s practices may include automated chaos testing.
"		0.2	1			
Business Continuity Management and Operational Resilience	Communication	BCR-07	"Establish communication with stakeholders and participants in the
course of business continuity and resilience procedures.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"A business continuity and resilience program should:

a. Communicate the importance of effective business continuity and the consequences of disruptions to all relevant stakeholders.
b. Communicate the business continuity and resilience policy, objectives, and plans to all relevant stakeholders.
c. Communicate the roles, responsibilities, authorities, and expected competencies to all relevant stakeholders.
d. Establish the criteria, thresholds, and indicators to demonstrate when and how business continuity-related communications should be sent, who should send them, and to whom they should be sent.
e. Establish templates for common communications during a disruption regarding the activation, operation, coordination, and communication of a business continuity response.
f. Establish the people, technology, and processes required for business continuity communications.
g. Establish a response structure that will enable timely warnings and communication to relevant stakeholders.

Clear and effective communication channels should remain available to disseminate information to participants and stakeholders, assess and relay damage, and coordinate a recovery strategy. Failed communication often results in failed business continuity efforts. Thorough planning, testing, and exercising communication procedures within the following four phases are essential to support effective business continuity and the viability of critical business operations.
"		No relevant controls found.	0	No relevant controls found.		"A business continuity and resilience program should:
a. Communicate the importance of effective business continuity and the consequences of disruptions to all relevant stakeholders.
b. Communicate the business continuity and resilience policy, objectives, and plans to all relevant stakeholders.
c. Communicate the roles, responsibilities, authorities, and expected competencies to all relevant stakeholders.
d. Establish the criteria, thresholds, and indicators to demonstrate when and how business continuity-related communications should be sent, who should send them, and to whom they should be sent.
e. Establish templates for common communications during a disruption regarding the activation, operation, coordination, and communication of a business continuity response.
f. Establish the people, technology, and processes required for business continuity communications.
g. Establish a response structure that will enable timely warnings and communication to relevant stakeholders.

Clear and effective communication channels should remain available to disseminate information to participants and stakeholders, assess and relay damage, and coordinate a recovery strategy. Failed communication often results in failed business continuity efforts. Thorough planning, testing, and exercising communication procedures within the following four phases are essential to support effective business continuity and the viability of critical business operations.
"		0	0			
Business Continuity Management and Operational Resilience	Backup	BCR-08	"Periodically backup data stored in the cloud. Ensure the confidentiality,
integrity and availability of the backup, and verify data restoration from backup
for resiliency.
"		EC2 snapshots with retention, but no restoration or recovery tested	1	Ad-hoc and not complete BC processes.		EFS disk snapshots for VM hosts. PaaS databases have snapshots enabled.	2	Snapshots and source code retained, but manual processes for creation, deletion, and testing.		3rd party Claranet to provides this capability	1	Team relies on Calaranet however, no policies or procedures have been identified		- Amazon RDS (SQL engine) and SQL Server on Azure for storing case data. - Databases are part of the backend services.	2	1. Usage of managed database services like Amazon RDS and SQL Server on Azure ensures data availability and resilience. 2. Backup and restoration processes for data stored in these databases are not explicitly mentioned. 3. Confidentiality and integrity controls for database backups are not specified in the provided text.		RDS instances are used for backend databases with multi-AZ deployment for reader and writer instances. Daily backups are taken by default, with more frequent backups based on customer requirements. Backup restoration is regularly tested during migration processes.	3	The company uses Amazon RDS for their backend databases and leverages multi-AZ deployment for redundancy with reader and writer instances. Database backups are performed daily by default, with the ability to do more frequent backups based on specific customer needs. The restore process for these backups is regularly tested when performing migrations. The maturity rating is a 3 because they have documented processes for regular backups and testing of restores. However, to achieve a higher rating, additional details would be needed on the controls in place to ensure the confidentiality, integrity, and availability of the backups.		" Implement a robust backup strategy for all critical systems and data using AWS Backup or Azure Backup. Configure regular, automated backups with appropriate retention policies. Regularly test backup restoration processes to ensure data integrity and availability. Document backup procedures and review them annually. Use AWS Backup Audit Manager to ensure compliance with backup policies and procedures.

a. The scope, frequency, and duration of cloud data retention should comply with:

Applicable laws
Contractual agreements with the cloud customers
The cloud provider’s business requirements

b. The backup approach, including the physical location of backup files, should comply with the privacy and data protection laws and regulations applicable to the data collected.
c. The data backup process should be monitored by employing technical and organizational safeguards. At a minimum, malfunctions should be examined and eliminated promptly by qualified employees to support compliance with the retention’s scope, frequency, and duration.
d. Backup and restoration procedures should be periodically tested and the results documented to ensure data can be successfully restored. Tests should be designed so that the reliability of the backup media and the restoration time (RPO, RTO) can be established with sufficient certainty. Any errors and identified improvements (corrective and preventive actions) should be addressed promptly.
e. Restorations should be carried out only after they have been approved by authorized persons (according to contractual agreements with cloud customers or the internal policies of the cloud provider).
f. The cloud service provider, when appropriate, should be able to disclose the exercise results to the cloud services customer as part of the assurance of business continuity and resilience.

Additional guidance is also available in the NIST Special Publication 800-53 (Rev. 4) CP-9 INFORMATION SYSTEM BACKUP (latest revision)."		No relevant controls found.	0	No relevant controls found.		"Implementation of backups and/or other means of data preservation (e.g., replication) should follow the following guidelines.
a. The scope, frequency, and duration of cloud data retention should comply with:
Applicable laws
Contractual agreements with the cloud customers
The cloud provider’s business requirements

b. The backup approach, including the physical location of backup files, should comply with the privacy and data protection laws and regulations applicable to the data collected.
c. The data backup process should be monitored by employing technical and organizational safeguards. At a minimum, malfunctions should be examined and eliminated promptly by qualified employees to support compliance with the retention’s scope, frequency, and duration.
d. Backup and restoration procedures should be periodically tested and the results documented to ensure data can be successfully restored. Tests should be designed so that the reliability of the backup media and the restoration time (RPO, RTO) can be established with sufficient certainty. Any errors and identified improvements (corrective and preventive actions) should be addressed promptly.
e. Restorations should be carried out only after they have been approved by authorized persons (according to contractual agreements with cloud customers or the internal policies of the cloud provider).
f. The cloud service provider, when appropriate, should be able to disclose the exercise results to the cloud services customer as part of the assurance of business continuity and resilience.

Additional guidance is also available in the NIST Special Publication 800-53 (Rev. 4) CP-9 INFORMATION SYSTEM BACKUP (latest revision).
"		1.8	1.8			
Business Continuity Management and Operational Resilience	Disaster Response Plan	BCR-09	"Establish, document, approve, communicate, apply, evaluate and maintain
a disaster response plan to recover from natural and man-made disasters. Update
the plan at least annually or upon significant changes.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"The response plan should include the ability to protect systems—including the physical environment when possible—from inadvertent unauthorized access during an emergency.

The response plan should include the following when describing environmental threats/natural disasters: fires, medical emergencies, tornadoes, hurricanes, flooding, earthquakes, and other natural disasters.

Civil disturbances can include disgruntled employees/contractors/customers, terrorist attacks, biological attacks, and airborne agents.

Emergency authorities can include first responders and other law enforcement entities."		No relevant controls found.	0	No relevant controls found.		"The response plan should include the ability to protect systems—including the physical environment when possible—from inadvertent unauthorized access during an emergency.

The response plan should include the following when describing environmental threats/natural disasters: fires, medical emergencies, tornadoes, hurricanes, flooding, earthquakes, and other natural disasters.

Civil disturbances can include disgruntled employees/contractors/customers, terrorist attacks, biological attacks, and airborne agents.

Emergency authorities can include first responders and other law enforcement entities.
"		0	0			
Business Continuity Management and Operational Resilience	Response Plan Exercise	BCR-10	"Exercise the disaster response plan annually or upon significant
changes, including if possible local emergency authorities.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"The plan should be executed at regular intervals based on the organization’s BIA. It should be performed as a tabletop exercise and incorporate an annual live event with local authorities (e.g., fire departments, health officials, police departments, anti-terrorist organizations, and anti-cybercrime groups).

Depending on regulatory requirements, the business, and the industry, a disaster recovery (DR) exercise might be required. For example, financial institutions may consider running live on DR for extended periods or simulate component or partial failures to test overall organizational resiliency and recovery abilities."		No relevant controls found.	0	No relevant controls found.		"The plan should be executed at regular intervals based on the organization’s BIA. It should be performed as a tabletop exercise and incorporate an annual live event with local authorities (e.g., fire departments, health officials, police departments, anti-terrorist organizations, and anti-cybercrime groups).

Depending on regulatory requirements, the business, and the industry, a disaster recovery (DR) exercise might be required. For example, financial institutions may consider running live on DR for extended periods or simulate component or partial failures to test overall organizational resiliency and recovery abilities.
"		0	0			
Business Continuity Management and Operational Resilience	Equipment Redundancy	BCR-11	"Supplement business-critical equipment with redundant equipment independently
located at a reasonable minimum distance in accordance with applicable industry
standards.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		k8's redundancy architecture	2	Reliant on K8s architecture and equipment. No documentation (policies or procedures) available at this point in time.		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		The minimum distance between mirrored or redundant physical systems should support compliance with the organization's defined continuity and availability within contractual agreements or service-level agreements (SLAs).		No relevant controls found.	0	No relevant controls found.		"The minimum distance between mirrored or redundant physical systems should support compliance with the organization's defined continuity and availability within contractual agreements or service-level agreements (SLAs).
"		0.4	2			
Change Control and Configuration Management	Change Management Policy and Procedures	CCC-01	"Establish, document, approve, communicate, apply, evaluate and maintain
policies and procedures for managing the risks associated with applying changes
to organization assets, including application, systems, infrastructure, configuration,
etc., regardless of whether the assets are managed internally or externally
(i.e., outsourced). Review and update the policies and procedures at least annually.
"		No controls identified	0	No controls identified		Limited change in legacy application environment, new environment has not been deployed. No identified change management controls.	0	No controls identified		No controls identified	0	No controls identified		- Blue-green deployment approach for updating production environment. - Deployment process involves progressively moving changes through Edge (dev), Test, QA, and Production environments.	3	1. Following a defined deployment process with established testing and release standards demonstrates a level of change control. 2. Progressive deployment through multiple environments (Edge, Test, QA, Production) shows evaluation of changes before applying to production. 3. Insufficient evidence of documented policies and procedures for managing risks associated with changes or reviewing them annually.		No relevant controls found.	0	No relevant controls found.		"Establish a formal change management process using ITIL best practices. Implement a change management tool like ServiceNow or Jira Service Management to track all changes. Ensure that changes are documented, reviewed, and approved before implementation. Conduct regular audits to ensure compliance with the change management process. Review and update the change management policy annually.

a. Ensure that changes are tested, documented, risk assessed, and authorized in a consistent and timely manner. All changes (e.g., major, minor, and emergency and the qualifying criteria) in organization assets, applications, system software, and informational technology (IT) infrastructure (e.g., hardware, operating systems, communications equipment, and software) and associated configurations should be under the scope of the change management policy.
b. Be communicated and made accessible to all employees and interested parties involved within the change management process (e.g., service/application owners, project leaders, IT, operating systems staff, contractors, etc.).
c. Include the management of emergency changes."		"Audit Team: -SOP for document control (ISSOP_QMS_001) with system to have audit -SMLS for training documents management -3 year review if no revisions made beforehand -Process owner or document owner responsible for creation and modification -Review process: process owner, quality assurance, and other relevant teams, then Audit&Assurance pushes to OnePLM (Windchill) -OnePLM pushes to SMLS via API"	3	The company has a documented Standard Operating Procedure (SOP) for document control, which includes a system for auditing documents. Training documents are managed through SMLS, and documents are reviewed every 3 years if no revisions are made beforehand. The process owner or document owner is responsible for creation and modification of documents. The review process involves the process owner, quality assurance, and other relevant teams, before the document is pushed to OnePLM (Windchill) by the Audit & Assurance team. OnePLM then pushes the document to SMLS via API. This indicates the existence of documented controls and processes that are followed with moderate consistency, justifying a maturity rating of 3. However, there is no explicit mention of these controls being applied to managing risks associated with changes to organization assets.		"A documented and approved change management policy (and associated process documentation) should:
a. Ensure that changes are tested, documented, risk assessed, and authorized in a consistent and timely manner. All changes (e.g., major, minor, and emergency and the qualifying criteria) in organization assets, applications, system software, and informational technology (IT) infrastructure (e.g., hardware, operating systems, communications equipment, and software) and associated configurations should be under the scope of the change management policy.
b. Be communicated and made accessible to all employees and interested parties involved within the change management process (e.g., service/application owners, project leaders, IT, operating systems staff, contractors, etc.).
c. Include the management of emergency changes.
"		0.6	3			
Change Control and Configuration Management	Quality Testing	CCC-02	"Follow a defined quality change control, approval and testing process
with established baselines, testing, and release standards.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No controls identified	0	No controls identified		- Blue-green deployment approach. - Deployment process involves progressively moving changes through different environments (Edge, Test, QA, Production) with specific purposes and testing requirements.	3	1. Blue-green deployment approach indicates a defined process for releasing changes with established baselines. 2. Progressive deployment through Edge, Test, QA, and Production environments demonstrates a testing process before production release. 3. Each environment having specific purposes and testing requirements shows quality control and testing standards, but more details would be needed for a higher maturity rating.		Changes are tested and approved before deployment to production. Deployment checklists are maintained for each release.	2	The company follows a process where changes are tested and must be approved prior to deployment into production environments. Deployment checklists are documented and maintained for each release. This indicates some level of change control with testing and approvals. However, there is no mention of established baselines or formal release standards that are consistently followed. The maturity rating is a 2 based on having an approval and testing process, but lacking evidence of defined baselines and release standards.		"Implement a defined quality change control, approval, and testing process using tools like SonarQube for static code analysis and OWASP ZAP for dynamic testing. Establish baselines and release standards for all changes. Use Jenkins or GitLab CI for automated testing and deployment. Ensure that all changes are tested and approved before deployment to production. Conduct regular reviews of the testing process to ensure its effectiveness.

Testing record(s) should be documented before implementing all planned changes to organization assets (including applications, systems, infrastructure, configuration, etc.), regardless of whether the assets are managed internally or externally (i.e., outsourced).

The record(s) should comprise a test plan, configuration baseline before the change, the test result, and the new configuration baseline.

The quality testing plan might align with relevant standards or guidelines (i.e., ITIL or ISO 20000, etc.)"		No relevant controls found.	0	No relevant controls found.		"A plan to test and review during the development process should be prepared. This plan should include (but is not limited to) relevant activities and test inputs, and expected outputs regarding various conditions that may impact the outcome. For internal organizational developments, the team that oversees development efforts initially can perform such tests. Independent acceptance testing can then be performed (both for internal and external development sources) to determine whether the system functions as intended. Testing should be proportionate to the system’s relevance based on its nature.

Testing record(s) should be documented before implementing all planned changes to organization assets (including applications, systems, infrastructure, configuration, etc.), regardless of whether the assets are managed internally or externally (i.e., outsourced).

The record(s) should comprise a test plan, configuration baseline before the change, the test result, and the new configuration baseline.

The quality testing plan might align with relevant standards or guidelines (i.e., ITIL or ISO 20000, etc.)
"		1	2.5			
Change Control and Configuration Management	Change Management Technology	CCC-03	"Manage the risks associated with applying changes to organization
assets, including application, systems, infrastructure, configuration, etc.,
regardless of whether the assets are managed internally or externally (i.e.,
outsourced).
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		redmine + git + testrail	1	Only reference to inputs verbally conveyed with no specificity (policies or procedures) 		- Blue-green deployment approach. - Deployment process involves progressively moving changes through different environments (Edge, Test, QA, Production).	3	1. Following a blue-green deployment approach helps manage risks by maintaining separate production and staging environments. 2. Progressively moving changes through Edge, Test, QA, and Production environments allows evaluating risks before applying changes to production. 3. Insufficient detail provided on how risks are assessed and managed during the change process to warrant a higher maturity rating.		No relevant controls found.	0	No relevant controls found.		"The organization should:

Collaborate with relevant internal and external parties involved in the change management process. 
Assess the impact and type of change to determine the risk of the change before it is applied.
Adopt Change Management Technologies to manage the change management workflow. 

These tools should help adequately manage the authorization process, including activity logging. In addition, real-time reporting/monitoring capabilities should be implemented to monitor change progress so that quick decisions can be made to manage the risks of unforeseen issues due to the change implementation.

Understanding how those relevant components impact the security and usability of the supply chain that supports organizational environments should be one aspect of such collaboration."		"AppSec Team: Stryker conducts risk assessments on outsourced development providers within their third-party risk management framework. These developers must adhere to Stryker's secure coding standards and undergo similar security testing and reviews as internal developments."	2	The company conducts risk assessments on outsourced development providers within their third-party risk management framework. These outsourced developers are required to adhere to Stryker's secure coding standards and undergo security testing and reviews similar to internal development teams. This indicates the existence of some controls and processes to manage risks associated with changes made by external parties. However, the lack of detailed documentation and uncertainty around the consistency of application limits the maturity rating to a 2. More evidence is needed regarding the systematic enforcement and regular auditing of these risk management practices for outsourced development.		"The organization should:
Collaborate with relevant internal and external parties involved in the change management process. 
Assess the impact and type of change to determine the risk of the change before it is applied.
Adopt Change Management Technologies to manage the change management workflow. 

These tools should help adequately manage the authorization process, including activity logging. In addition, real-time reporting/monitoring capabilities should be implemented to monitor change progress so that quick decisions can be made to manage the risks of unforeseen issues due to the change implementation.

Understanding how those relevant components impact the security and usability of the supply chain that supports organizational environments should be one aspect of such collaboration.
"		0.8	2			
Change Control and Configuration Management	Unauthorized Change Protection	CCC-04	"Restrict the unauthorized addition, removal, update, and management
of organization assets.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		Access to production are monitored. But nothing prevent change in production yet.	1	No policies / procedures or specificity of how access is monitored obtained as of this juncture		- Security groups used to control access to publicly exposed resources. - IP whitelisting employed to restrict access to resources to authorized users.	3	1. Using security groups to control access to publicly exposed resources helps restrict unauthorized changes. 2. Employing IP whitelisting to limit access to authorized users reduces the risk of unauthorized modifications. 3. More information would be needed on change management processes and how unauthorized changes are prevented across all assets and environments for a higher rating.		Only the DevOps team has access to make changes in production. Developers do not have direct access to the production environment. Changes require approval from the product owner before deployment.	3	The company restricts production changes to only the DevOps team. Developers do not have direct access to make changes in production environments. Furthermore, all changes require explicit approval from the product owner prior to deployment. These controls help prevent unauthorized changes to production systems. The maturity rating is a 3 because they have a documented process restricting production changes to authorized personnel only, with a change approval process in place. However, for a higher rating, additional details would be needed on how they technically enforce these restrictions and approvals.		Implement technical controls to prevent unauthorized changes to systems and configurations using AWS Config or Azure Policy. Regularly audit changes and ensure they are authorized and documented. Use tools like HashiCorp Vault or AWS Secrets Manager to manage and secure access credentials. Ensure that all changes are reviewed and approved by authorized personnel.		"Audit team Controls/Policies in place: -No formal risk assessment, but general security and risky standards go through leadership review -Data related standards must use legal and compliance, and EU compliance for GDPR assessments -DPO assigned Sarah Knight (Global Privacy Officer) -Contractors held to same training requirements -Need to meet with supplier team (Heather Maurer)"	2	The company has some controls and policies in place to restrict unauthorized changes to organization assets. General security standards and high-risk standards go through a leadership review process. Data-related standards require involvement from legal, compliance, and EU compliance teams for GDPR assessments. A Data Protection Officer (DPO) has been assigned. Contractors are held to the same training requirements as employees. However, the lack of a formal risk assessment process and the need to gather more information from the supplier team suggests that these controls may not be comprehensively documented or consistently applied across the organization. Therefore, the maturity rating is assessed as a 2, indicating the existence of some controls but with room for improvement in documentation and consistency.		"The organization should establish procedures and implement technical measures to prevent and/or detect any unwanted/unauthorized changes (e.g., additions, removals, and updates) to organizational assets production, including applications, systems, infrastructure, configuration, etc.
"		1.4	2.333333333			
Change Control and Configuration Management	Change Agreements	CCC-05	"Include provisions limiting changes directly impacting CSCs owned
environments/tenants to explicitly authorized requests within service level
agreements between CSPs and CSCs.
"		Physio account is managed by LifeNet who owns the CSP relationship and contractual components	2	Some external controls, but not well documented nor monitored.		No controls identified	0	No controls identified		Managed by Claranet.	2	No policies / procedures obtained as of this juncture		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"Processes and procedures established by both the CSP and CSC should reflect respective change management responsibilities with respect to the scope of services being provided and/or consumed. There should be acknowledgement of each party's responsibility, where applicable and it should be part of a written change management agreement between CSC and CSP. The acknowledgment should include a reference to limitations related to changes impacting CSC-owned environments/tenants.

NOTE: The CSP may need to apply changes that impact CSC-owned environments/tenants without the explicit authorization of the CSC (in case those changes would be required for the overall security of the CSP system). If those types of changes are applied, the CSC should be consulted promptly."		No relevant controls found.	0	No relevant controls found.		"Processes and procedures established by both the CSP and CSC should reflect respective change management responsibilities with respect to the scope of services being provided and/or consumed. There should be acknowledgement of each party's responsibility, where applicable and it should be part of a written change management agreement between CSC and CSP. The acknowledgment should include a reference to limitations related to changes impacting CSC-owned environments/tenants.

NOTE: The CSP may need to apply changes that impact CSC-owned environments/tenants without the explicit authorization of the CSC (in case those changes would be required for the overall security of the CSP system). If those types of changes are applied, the CSC should be consulted promptly.
"		0.8	2			
Change Control and Configuration Management	Change Management Baseline	CCC-06	"Establish change management baselines for all relevant authorized
changes on organization assets.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No controls identified	0	No controls identified		The Prophecy system follows a blue-green deployment approach for updating the production environment. The deployment process involves progressively moving changes through different environments: Edge (dev), Test, QA, and Production.	4	1. The blue-green deployment approach provides a controlled and measured way to implement changes. 2. The progressive deployment through Edge, Test, QA, and Production environments allows for thorough testing and validation before changes reach production. 3. Having separate blue and green environments enables quick rollback in case of issues.		No relevant controls found.	0	No relevant controls found.		A change management baseline reflects the minimum policies, procedures and technical measures established to achieve organizational objectives, and requirements (i.e., CCC-02 implementation guidelines).		No relevant controls found.	0	No relevant controls found.		"A change management baseline reflects the minimum policies, procedures and technical measures established to achieve organizational objectives, and requirements (i.e., CCC-02 implementation guidelines).
"		0.8	4			
Change Control and Configuration Management	Detection of Baseline Deviation	CCC-07	"Implement detection measures with proactive notification in case
of changes deviating from the established baseline.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		Terraform drift scan done daily	2	No policies / procedures or documentation process evidence obtained as of this juncture		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"The organization should establish a policy and procedures to detect deviations from the established control baseline. When a deviation is detected, the organization should follow the incidence management policies and procedures defined in SEF-01.
"		No relevant controls found.	0	No relevant controls found.		"The organization should establish a policy and procedures to detect deviations from the established control baseline. When a deviation is detected, the organization should follow the incidence management policies and procedures defined in SEF-01.
"		0.4	2			
Change Control and Configuration Management	Exception Management	CCC-08	"'Implement a procedure for the management of exceptions, including
emergencies, in the change and configuration process. Align the procedure with
the requirements of GRC-04: Policy Exception Process.'
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		We use Claranet tools to perform such a change	2	Team reliant on Claranet for managing exceptions procedure. No documented policies or procedures		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"The procedure for exceptions’ management should include, but is not limited to:
a. Change management baselines
b. Unauthorized assets
c. Evidence collection and management
"		Individual teams provided minimal, verbal convenance to controls. No documentation conveyed or provided to validate.	1	While the audit team has some controls and policies in place related to document control, training document management, and a review process, there is no specific mention of a procedure for managing exceptions and emergencies in the change and configuration process. The individual teams provided minimal assurance of controls without supporting documentation. To achieve a higher maturity rating, a documented procedure aligned with policy exception processes and evidence of its application across teams would be needed.		"The procedure for exceptions’ management should include, but is not limited to:
a. Change management baselines
b. Unauthorized assets
c. Evidence collection and management
"		0.4	2			
Change Control and Configuration Management	Change Restoration	CCC-09	"Define and implement a process to proactively roll back changes to
a previous known good state in case of errors or security concerns.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No controls identified	0	No controls identified		The Prophecy system follows a blue-green deployment approach for updating the production environment. Two identical environments (blue and green) are maintained, with one serving as production and the other as a staging environment.	4	1. The blue-green deployment approach allows for quick rollback to a previous known good state in case of errors or security concerns. 2. Maintaining two identical environments ensures a stable rollback point is always available. 3. The staging environment serves as a final validation step before promoting changes to production, reducing the risk of introducing errors.		No relevant controls found.	0	No relevant controls found.		Rollback procedures should be created and tested with each change request.		No relevant controls found.	0	No relevant controls found.		"Rollback procedures should be created and tested with each change request.
"		0.8	4			
Cryptography, Encryption & Key Management	Encryption and Key Management Policy and Procedures	CEK-01	"Establish, document, approve, communicate, apply, evaluate and maintain
policies and procedures for Cryptography, Encryption and Key Management. Review
and update the policies and procedures at least annually.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		We follow AWS standard	2	No policies / procedures or documentation process evidence obtained as of this juncture		No relevant controls found.	0	No relevant controls found.		Ansible Vault is used to encrypt sensitive information. Secrets are stored in AWS Secrets Manager and Azure DevOps for secure access.	2	The company utilizes Ansible Vault for encrypting sensitive data and leverages AWS Secrets Manager and Azure DevOps for secure secret storage. However, there is no mention of comprehensive policies, procedures, or regular reviews related to cryptography, encryption, and key management. The maturity rating is limited to a 2 due to the lack of evidence of a fully established and maintained cryptography and key management program.		"Develop a detailed encryption and key management policy. Implement a key management solution such as HashiCorp Vault, Azure Key Vault, or AWS KMS. Ensure that encryption keys are rotated regularly and stored securely.

Conduct regular audits of the key management process. Use tools like Venafi or Thales CipherTrust for advanced key management and encryption.

Policies and procedures include but are not limited to the following considerations:

A. Policies and procedures relating to organization/management.
a. Roles and responsibilities (See GRM for general considerations)
b. Data protection (DSP domain for general considerations)
   1) Data encryption
   2) Algorithm
c. Change management (See CCC domain for general considerations)
   1) Cost-Benefit analysis
d. Risk management (See BCR/GRC domains for general considerations)
e. Monitoring and reporting (see LOG and monitoring domain for general considerations )
f. Transaction/activity logging (see LOG and monitoring domain for general considerations)
g. Incident handling (see SEF domain for general considerations)
h. Audit (See A&A domain for general considerations)

B. Policies and procedures relating to key management.
a. Key generation 
b. Key distribution 
c. Key rotation 
d. Key revocation 
e. Key destruction
f. Key activation 
g. Key suspension
h. Key deactivation
i. Key archival
j. Key compromise
k. Key recovery
l. Key inventory management
m. Key purposes
n. Key access"		No relevant controls found.	0	No relevant controls found.		"Policies and procedures on the use, protection, and lifetime of cryptographic keys should be developed and implemented through their full  lifecycle.

Policies and procedures include but are not limited to the following considerations:

A. Policies and procedures relating to organization/management.
a. Roles and responsibilities (See GRM for general considerations)
b. Data protection (DSP domain for general considerations)
   1) Data encryption
   2) Algorithm
c. Change management (See CCC domain for general considerations)
   1) Cost-Benefit analysis
d. Risk management (See BCR/GRC domains for general considerations)
e. Monitoring and reporting (see LOG and monitoring domain for general considerations )
f. Transaction/activity logging (see LOG and monitoring domain for general considerations)
g. Incident handling (see SEF domain for general considerations)
h. Audit (See A&A domain for general considerations)

B. Policies and procedures relating to key management.
a. Key generation 
b. Key distribution 
c. Key rotation 
d. Key revocation 
e. Key destruction
f. Key activation 
g. Key suspension
h. Key deactivation
i. Key archival
j. Key compromise
k. Key recovery
l. Key inventory management
m. Key purposes
n. Key access
"		0.8	2			
Cryptography, Encryption & Key Management	CEK Roles and Responsibilities	CEK-02	"Define and implement cryptographic, encryption and key management
roles and responsibilities.
"		SSH keys in use by Physio users to manage EC2 instances	2	Ad-hoc, host based solutions that do not align with best practices or security isolation.		No controls identified	0	No controls identified		We use AWS KMS	2	No policies / procedures or documentation process evidence obtained as of this juncture		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"Below are some examples of possible roles and responsibilities:

a. Keys managers should not be able to access protected data or the cryptographic engine.
b. Separation of duties should include two or more individuals control a single process.
c. Split Knowledge requires no one person knows the complete value of an encryption key.
d. No one person should know the entire passphrase used to create encryption keys.
e. Restrict access rights to the least resources required (least privilege).
f. A policy authority is responsible for all operational cryptographic key management system (CKMS) roles and reports to the executive IT.

Roles and responsibilities should be defined and followed:
a. Generation or acquisition of key information .
b. Secure distribution of private and secret keys,and the metadata.
c. Establishment of cryptoperiods.
d. Key and certificate inventory management.
e. Revocation of compromised keys and the establishment of replacement keys and/or certificates.
f. Management of the storage and recovery of operational and backed-up key information.
g. Storage and recovery of archived key information.
h. Checking the integrity of stored key information before using it.
i. Destruction of private or secret keys that are no longer required."		No relevant controls found.	0	No relevant controls found.		"Below are some examples of possible roles and responsibilities:
a. Keys managers should not be able to access protected data or the cryptographic engine.
b. Separation of duties should include two or more individuals control a single process.
c. Split Knowledge requires no one person knows the complete value of an encryption key.
d. No one person should know the entire passphrase used to create encryption keys.
e. Restrict access rights to the least resources required (least privilege).
f. A policy authority is responsible for all operational cryptographic key management system (CKMS) roles and reports to the executive IT.


Roles and responsibilities should be defined and followed:
a. Generation or acquisition of key information .
b. Secure distribution of private and secret keys,and the metadata.
c. Establishment of cryptoperiods.
d. Key and certificate inventory management.
e. Revocation of compromised keys and the establishment of replacement keys and/or certificates.
f. Management of the storage and recovery of operational and backed-up key information.
g. Storage and recovery of archived key information.
h. Checking the integrity of stored key information before using it.
i. Destruction of private or secret keys that are no longer required.
"		0.8	2			
Cryptography, Encryption & Key Management	Data Encryption	CEK-03	"Provide cryptographic protection to data at-rest and in-transit,
using cryptographic libraries certified to approved standards.
"		No controls identified/ No business data held	0	No controls identified		No controls identified	0	No controls identified		It is done in redmine. One spec for crypto (our microservice handling encryption at rest) and one spec for the TLS 1,3 configuration	2	No policies / procedures or documentation process evidence obtained as of this juncture		All communication between services, including internal communication, utilizes Transport Layer Security (TLS) 1.2 encryption.	4	1. The use of TLS 1.2 encryption provides strong cryptographic protection to data in transit. 2. Encrypting all communication between services, including internal communication, ensures comprehensive data protection. 3. TLS 1.2 is a widely-accepted and approved standard for secure communication.		Customer data stored in databases is encrypted. Older products have been migrated to TLS 1.2 for secure communication.	2	The company encrypts customer data at rest in databases and has migrated older products to use TLS 1.2 for data in transit, providing cryptographic protection. However, there is no specific mention of using certified cryptographic libraries or a comprehensive approach to protecting all data at rest and in transit. The maturity rating is a 2 due to the lack of evidence of a complete and consistent cryptographic protection strategy.		"Data protection/data encryption is the process of changing plaintext into ciphertext using a cryptographic algorithm and key.

a. Stryker should be able to either encrypt all information on storage devices (i.e., full disk encryption) or encrypt specific data structures (e.g., files, records, or fields).
b. Data at rest involves databases, end-user workstations, and file servers.
c. Data in transit involves system interfaces, public networks, and electronic messaging.
d. Cryptography provides data protection: confidentiality, integrity, availability, and source authentication.
e. Cryptographic key management system security policies rules need to protect the confidentiality, integrity, availability, and source authentication of all keys, algorithms, and metadata.
f. Key management technology and processes should be NIST FIPS validated and/or National Security Agency (NSA)-approved by other relevant international standardization bodies.
g. Approved algorithms and key sizes should reside in the CKMS.
h. Quantum-resistant encryption is developing quickly, and it is recommended that this technology is closely monitored so the organization is not exposed."		"AppSec Team: Stryker's Drupal-based content management system (CMS), used for internal research and analysis of surgical data, is hosted on hardened Amazon EC2 instances behind a VPN gateway. Access requires authentication through SecurID MFA. Azure WAF and Azure Front Door are used to protect the EC2-hosted web applications. Amazon Aurora encrypted using AES-256. All data in transit is encrypted using TLS 1.2. Developers connect to AWS environments using SSH with RSA keys. Stryker's new serverless AWS environment, built using AWS Lambda, API Gateway, S3, and Aurora, leverages similar data security controls: - All data in transit is encrypted using HTTPS/TLS. - Amazon S3 buckets are encrypted using AES-256 and access is restricted through IAM policies and bucket policies. - Aurora databases are encrypted at rest using AES-256. - Secure key management and rotation is handled using AWS KMS. - Secrets are stored using AWS Secrets Manager and encrypted using KMS."	4	Stryker provides strong cryptographic protection to data at rest and in transit across their environments. Their Drupal CMS hosted on EC2 instances uses AES-256 encryption for Aurora databases and TLS 1.2 for data in transit. Access requires MFA and goes through a VPN gateway, with additional protection from Azure WAF and Front Door. Their serverless AWS environment similarly encrypts S3 buckets and Aurora databases with AES-256, secures data in transit with HTTPS/TLS, and leverages AWS KMS for key management and Secrets Manager for storing secrets. Developers connect using SSH with RSA keys. These controls are well-documented and consistently applied across the different environments, warranting a maturity rating of 4. To achieve a 5, evidence of regular audits and strict enforcement of these encryption standards would be needed.		"Data protection/data encryption is the process of changing plaintext into ciphertext using a cryptographic algorithm and key.
a. Organizations should be able to either encrypt all information on storage devices (i.e., full disk encryption) or encrypt specific data structures (e.g., files, records, or fields).
b. Data at rest involves databases, end-user workstations, and file servers.
c. Data in transit involves system interfaces, public networks, and electronic messaging.
d. Cryptography provides data protection: confidentiality, integrity, availability, and source authentication.
e. Cryptographic key management system security policies rules need to protect the confidentiality, integrity, availability, and source authentication of all keys, algorithms, and metadata.
f. Key management technology and processes should be NIST FIPS validated and/or National Security Agency (NSA)-approved by other relevant international standardization bodies.
g. Approved algorithms and key sizes should reside in the CKMS.
h. Quantum-resistant encryption is developing quickly, and it is recommended that this technology is closely monitored so the organization is not exposed.
"		1.6	2.666666667			
Cryptography, Encryption & Key Management	Encryption Algorithm	CEK-04	"Use encryption algorithms that are appropriate for data protection,
considering the classification of data, associated risks, and usability of the
encryption technology.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No controls identified	0	No controls identified		All communication between services, including internal communication, utilizes Transport Layer Security (TLS) 1.2 encryption.	3	1. The use of TLS 1.2 encryption is appropriate for protecting data in transit. 2. TLS 1.2 is a widely-accepted and approved standard for secure communication. 3. However, the text does not provide information on the specific encryption algorithms used within TLS 1.2 or their appropriateness based on data classification and associated risks.		No relevant controls found.	0	No relevant controls found.		"A risk-based approach to encryption algorithms adoption should consider, but not be limited to:

a. Cryptographic key management system algorithms should not exceed the anticipated lifetime of the CKMS and the information it protects.
b. Cryptographic key management system security policies should protect the confidentiality, integrity, availability, and source authentication of all keys, algorithms, and metadata.
c. The (CKMS) should include, but is not limited to:
Approved algorithms
Hardware security modules (HSMs)
Key sizes
d. The adoption of the appropriate key size and algorithm types should be done based on cost-benefit analysis and the level of risk to data (please see the reference to quantum-resistant encryption in CEK-03)."		"AppSec Team: Stryker's Drupal-based content management system (CMS), used for internal research and analysis of surgical data, is hosted on hardened Amazon EC2 instances behind a VPN gateway. Access requires authentication through SecurID MFA. Azure WAF and Azure Front Door are used to protect the EC2-hosted web applications. Amazon Aurora encrypted using AES-256. All data in transit is encrypted using TLS 1.2. Developers connect to AWS environments using SSH with RSA keys. Stryker's new serverless AWS environment, built using AWS Lambda, API Gateway, S3, and Aurora, leverages similar data security controls: - All data in transit is encrypted using HTTPS/TLS. - Amazon S3 buckets are encrypted using AES-256 and access is restricted through IAM policies and bucket policies. - Aurora databases are encrypted at rest using AES-256. - Secure key management and rotation is handled using AWS KMS. - Secrets are stored using AWS Secrets Manager and encrypted using KMS."	3	Stryker uses encryption algorithms appropriate for protecting their data, considering the sensitivity of the surgical research data handled by their Drupal CMS. AES-256 is used for encrypting Aurora databases and S3 buckets at rest, while TLS 1.2 and HTTPS secure data in transit. These are industry-standard algorithms suitable for the use case. However, there is no explicit mention of a data classification system or risk assessment process to determine encryption requirements. The consistent use of strong encryption across environments suggests a level of maturity, but more information on the decision process and risk analysis would be needed to warrant a higher rating.		"A risk-based approach to encryption algorithms adoption should consider, but not be limited to:
a. Cryptographic key management system algorithms should not exceed the anticipated lifetime of the CKMS and the information it protects.
b. Cryptographic key management system security policies should protect the confidentiality, integrity, availability, and source authentication of all keys, algorithms, and metadata.
c. The (CKMS) should include, but is not limited to:
Approved algorithms
Hardware security modules (HSMs)
Key sizes
d. The adoption of the appropriate key size and algorithm types should be done based on cost-benefit analysis and the level of risk to data (please see the reference to quantum-resistant encryption in CEK-03).
"		0.6	3			
Cryptography, Encryption & Key Management	Encryption Change Management	CEK-05	"Establish a standard change management procedure, to accommodate
changes from internal and external sources, for review, approval, implementation
and communication of cryptographic, encryption and key management technology
changes.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"Key change management is the process of managing all changes to key management governance, organization, infrastructure, and activities.
a. Changes to the key management system and its policies and procedures should be analyzed and approved before implementation.
b. Changes should be documented to show the reasoning behind the changes and include a path to rollback to the previous status.
c. If unauthorized changes are made to the software, the software should be recovered.
d. There should be security audits after every significant change to the key management system.
e. All audit results should be reported to the system authority."		No relevant controls found.	0	No relevant controls found.		"Key change management is the process of managing all changes to key management governance, organization, infrastructure, and activities.
a. Changes to the key management system and its policies and procedures should be analyzed and approved before implementation.
b. Changes should be documented to show the reasoning behind the changes and include a path to rollback to the previous status.
c. If unauthorized changes are made to the software, the software should be recovered.
d. There should be security audits after every significant change to the key management system.
e. All audit results should be reported to the system authority.
"		0	0			
Cryptography, Encryption & Key Management	Encryption Change Cost Benefit Analysis	CEK-06	"Manage and adopt changes to cryptography-, encryption-, and key management-related
systems (including policies and procedures) that fully account for downstream
effects of proposed changes, including residual risk, cost, and benefits analysis.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"Encryption change cost-benefit analysis is the process of comparing the benefit of encryption changes to its cost.
a. Key change management cost-benefit analysis/return on investment (ROI) should be calculated for all key management-related changes.
b. Every analysis should fully account for downstream effects of proposed changes, including residual risks.
c. Every analysis should be reviewed and approved.
d. Six months after a change, compare the anticipated ROI to the actual ROI.
e. Significant deviation from the planned ROI should be audited.
f. Report all audit results to the system authority."		No relevant controls found.	0	No relevant controls found.		"Encryption change cost-benefit analysis is the process of comparing the benefit of encryption changes to its cost.
a. Key change management cost-benefit analysis/return on investment (ROI) should be calculated for all key management-related changes.
b. Every analysis should fully account for downstream effects of proposed changes, including residual risks.
c. Every analysis should be reviewed and approved.
d. Six months after a change, compare the anticipated ROI to the actual ROI.
e. Significant deviation from the planned ROI should be audited.
f. Report all audit results to the system authority.
"		0	0			
Cryptography, Encryption & Key Management	Encryption Risk Management	CEK-07	"Establish and maintain an encryption and key management risk program
that includes provisions for risk assessment, risk treatment, risk context,
monitoring, and feedback.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"Key risk management is the process of managing the risks to key management governance, organization, infrastructure, and activities.

a. Assess the risks of unauthorized disclosure, modification, destruction, or information loss.
b. Cryptoperiod selections should consider the risk and consequences of information exposure.
c. Evaluate the tradeoffs of manual versus automated key distribution.
d. Reduce compromised key risks by (1) not using such keys for new encryption activities and (2) only using keys to decrypt material previously decrypted under this key.
e. Adjust the audit scope and frequency to align with the risk assessment.
f. Apply algorithm strength in proportion to the risk of information exposure.
g. Assess risks to operational continuity versus the risks of key material data exposure when considering key recovery."		No relevant controls found.	0	No relevant controls found.		"Key risk management is the process of managing the risks to key management governance, organization, infrastructure, and activities.
a. Assess the risks of unauthorized disclosure, modification, destruction, or information loss.
b. Cryptoperiod selections should consider the risk and consequences of information exposure.
c. Evaluate the tradeoffs of manual versus automated key distribution.
d. Reduce compromised key risks by (1) not using such keys for new encryption activities and (2) only using keys to decrypt material previously decrypted under this key.
e. Adjust the audit scope and frequency to align with the risk assessment.
f. Apply algorithm strength in proportion to the risk of information exposure.
g. Assess risks to operational continuity versus the risks of key material data exposure when considering key recovery.
"		0	0			
Cryptography, Encryption & Key Management	CSC Key Management Capability	CEK-08	"CSPs must provide the capability for CSCs to manage their own data
encryption keys.
"		Physio account is managed by LifeNet who owns the CSP relationship and contractual components	2	Ad-hoc, host based solutions that do not align with best practices or security isolation.		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		Keys are managed using AWS Key Vault.	1	The company uses AWS Key Vault for managing encryption keys, providing some capability for key management. However, there is no explicit mention of allowing customers to manage their own encryption keys. The maturity rating is a 1 due to the lack of evidence of a comprehensive customer-managed key solution.		"Key management capability is the process of CSPs providing CSCs the capability to manage CSC-owned or generated encryption keys.
a. The CSC and CSP should agree on the definition and scope of CSC-managed keys and document this (shared responsibility) in the SLA, applicable contracts, policies, and procedures.
b. The CSP should allow the CSC to manage policies, procedures, and processes.
c. The CSP should empower the CSC to manage keys and data encryption keys.
d. The CSP should enable the CSC to manage key encryption keys or master keys used to encrypt data keys.
e. The CSP should allow the CSC to use the key management system (e.g., transactions, reporting, etc.).
f. Optionally, the CSC should supply CSC-generated master encryption keys using bring-your-own-key (BYOK) mechanisms per the SLA."		No relevant controls found.	0	No relevant controls found.		"Key management capability is the process of CSPs providing CSCs the capability to manage CSC-owned or generated encryption keys.
a. The CSC and CSP should agree on the definition and scope of CSC-managed keys and document this (shared responsibility) in the SLA, applicable contracts, policies, and procedures.
b. The CSP should allow the CSC to manage policies, procedures, and processes.
c. The CSP should empower the CSC to manage keys and data encryption keys.
d. The CSP should enable the CSC to manage key encryption keys or master keys used to encrypt data keys.
e. The CSP should allow the CSC to use the key management system (e.g., transactions, reporting, etc.).
f. Optionally, the CSC should supply CSC-generated master encryption keys using bring-your-own-key (BYOK) mechanisms per the SLA.
"		0.6	1.5			
Cryptography, Encryption & Key Management	Encryption and Key Management Audit	CEK-09	"Audit encryption and key management systems, policies, and processes
with a frequency that is proportional to the risk exposure of the system with
audit occurring preferably continuously but at least annually and after any
security event(s).
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"Key audit is the process of assessing the organization, governance, infrastructure, policies, procedures, and activities.
a. Audits assess compliance with ""key management"" policies and procedures.
b. Audits assess the design and effectiveness of ""key management"" controls and the control environment.
c. Audits assess compliance with industry and regulatory standards (e.g., Health Insurance Portability and Accountability Act (HIPAA), payment card industry (PCI)).
d. Audits results are reported to the key management system authority.
e. Audits are performed according to key- and risk-management policies.
f. Request third-party certification reports and review issues with the CSP and auditor.
g. At a minimum, sensitive audit information and sensitive audit tools should be cryptographically protected.
"		No relevant controls found.	0	No relevant controls found.		"Key audit is the process of assessing the organization, governance, infrastructure, policies, procedures, and activities.
a. Audits assess compliance with ""key management"" policies and procedures.
b. Audits assess the design and effectiveness of ""key management"" controls and the control environment.
c. Audits assess compliance with industry and regulatory standards (e.g., Health Insurance Portability and Accountability Act (HIPAA), payment card industry (PCI)).
d. Audits results are reported to the key management system authority.
e. Audits are performed according to key- and risk-management policies.
f. Request third-party certification reports and review issues with the CSP and auditor.
g. At a minimum, sensitive audit information and sensitive audit tools should be cryptographically protected.
"		0	0			
Cryptography, Encryption & Key Management	Key Generation	CEK-10	"Generate Cryptographic keys using industry accepted cryptographic
libraries specifying the algorithm strength and the random number generator
used.
"		SSH keys are generated using standard RSA keygen methods on each EC2 host	2	Ad-hoc, host based solutions that do not align with best practices or security isolation.		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"The key generation process should be cryptographically secure.
a. Keys should be generated:
using random bit generators (RBGs) and possibly other parameters, or
generated based on keys that are created in this fashion.
b. Key management technology and processes should be NIST FIPS validated or NSA-approved or comparable.
c. All relevant transitions/activity should be recorded (logged) in the inventory management system (CKMS)."		No relevant controls found.	0	No relevant controls found.		"The key generation process should be cryptographically secure.
a. Keys should be generated:
using random bit generators (RBGs) and possibly other parameters, or
generated based on keys that are created in this fashion.
b. Key management technology and processes should be NIST FIPS validated or NSA-approved or comparable.
c. All relevant transitions/activity should be recorded (logged) in the inventory management system (CKMS).
"		0.4	2			
Cryptography, Encryption & Key Management	Key Purpose	CEK-11	"Manage cryptographic secret and private keys that are provisioned
for a unique purpose.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		They are distributed with a claranet secure transfer tool	2	Team reliant on Claranet for provisioning. No policies/ procedures as evidence at this juncture		The secrets are managed outside the code in Azure DevOps and AWS Secrets Manager.	2	1. Cryptographic secrets and private keys are stored in Azure DevOps and AWS Secrets Manager, separate from code. 2. Managing secrets outside the code indicates a level of security awareness and control. 3. However, there is no mention of ensuring keys are provisioned for unique purposes, so the maturity cannot be rated higher without more information.		No relevant controls found.	0	No relevant controls found.		"Key distribution is the process of logically or physically transferring keys.
a. Distribution of asymmetric key pairs (public, ephemeral, centrally) requires protection mechanisms.
b. Distribution of symmetric keys requires their own protection mechanisms.
c. Distribution of other key materials requires their own protection mechanisms.
d. Distributed keys should be protected at rest, in storage, in transit, and to the appropriate extent (even when in use).
e. Distribution controls must address confidentiality, integrity, and availability.
f. Manual or automated (preferable) distribution may be used.
g. All relevant transitions/activity should be recorded (logged) in the inventory management system (CKMS)."		"AppSec Team: Stryker's new serverless AWS environment, built using AWS Lambda, API Gateway, S3, and Aurora, leverages similar data security controls: - Secure key management and rotation is handled using AWS KMS. - Secrets are stored using AWS Secrets Manager and encrypted using KMS."	2	Stryker uses AWS KMS for secure management of cryptographic keys in their serverless environment. AWS Secrets Manager is used to store secrets, with the secrets encrypted using KMS. This suggests that keys are provisioned for specific purposes, with KMS providing a centralized and secure key management system. However, there are no details provided on the specific practices followed for key provisioning and management or how the unique purpose of each key is ensured and enforced. More information would be needed on the key management policies and procedures to justify a higher maturity rating.		"Key distribution is the process of logically or physically transferring keys.
a. Distribution of asymmetric key pairs (public, ephemeral, centrally) requires protection mechanisms.
b. Distribution of symmetric keys requires their own protection mechanisms.
c. Distribution of other key materials requires their own protection mechanisms.
d. Distributed keys should be protected at rest, in storage, in transit, and to the appropriate extent (even when in use).
e. Distribution controls must address confidentiality, integrity, and availability.
f. Manual or automated (preferable) distribution may be used.
g. All relevant transitions/activity should be recorded (logged) in the inventory management system (CKMS).
"		0.8	2			
Cryptography, Encryption & Key Management	Key Rotation	CEK-12	"Rotate cryptographic keys in accordance with the calculated cryptoperiod,
which includes provisions for considering the risk of information disclosure
and legal and regulatory requirements.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No controls identified	0	No controls identified		Internal certificates for service-to-service communication are not currently being rotated, which is noted as a finding.	1	1. It is explicitly mentioned that internal certificates for service-to-service communication are not being rotated. 2. Lack of certificate rotation is acknowledged as a finding, indicating it does not align with best practices. 3. No mention of rotating other cryptographic keys in accordance with calculated cryptoperiods or considering risk and regulatory requirements.		No relevant controls found.	0	No relevant controls found.		"Implement regular key rotation policies for all cryptographic keys using AWS KMS or Azure Key Vault. Configure automatic key rotation and ensure that old keys are securely archived or destroyed. Conduct regular reviews to ensure compliance with key rotation policies. Use tools like HashiCorp Vault for managing and automating key rotation processes.

Key rotation generates (based on policy) a new key version of a key used to encrypt data.
a. Non-primary (old) keys should be used to decrypt data previously encrypted before re-encrypting the data with new keys.
b. Old data may be re-encrypted using new keys based on organizational policy and technology capacity.
c. When rotating keys, consider the following principles:
• Cryptographic mechanism strength: algorithm, key length, and mode of operation.
• The volume of information flow or the number of transactions.
• The security life of the data.
• The security functions, such as data encryption, digital signature, and key protection.
• The number of key copies and the distribution of those copies.
d. All relevant transitions/activity should be recorded (logged) in the inventory management system (CKMS)."		No relevant controls found.	0	No relevant controls found.		"Key rotation generates (based on policy) a new key version of a key used to encrypt data.
a. Non-primary (old) keys should be used to decrypt data previously encrypted before re-encrypting the data with new keys.
b. Old data may be re-encrypted using new keys based on organizational policy and technology capacity.
c. When rotating keys, consider the following principles:
• Cryptographic mechanism strength: algorithm, key length, and mode of operation.
• The volume of information flow or the number of transactions.
• The security life of the data.
• The security functions, such as data encryption, digital signature, and key protection.
• The number of key copies and the distribution of those copies.
d. All relevant transitions/activity should be recorded (logged) in the inventory management system (CKMS).
"		0.2	1			
Cryptography, Encryption & Key Management	Key Revocation	CEK-13	"Define, implement and evaluate processes, procedures and technical
measures to revoke and remove cryptographic keys prior to the end of its established
cryptoperiod, when a key is compromised, or an entity is no longer part of the
organization, which include provisions for legal and regulatory requirements.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		A ticket to claranet is executed and they apply their procedure	2	Team reliant on Claranet for provisioning. No policies/ procedures as evidence at this juncture		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		Develop a key revocation process to handle compromised or no longer needed keys. Use AWS KMS or Azure Key Vault to manage key states and transitions. Ensure that keys are revoked promptly and securely. Document all key revocation actions and communicate them to relevant stakeholders. Conduct regular audits to ensure compliance with key revocation policies.		No relevant controls found.	0	No relevant controls found.		"Key revocation removes keys from operational use before their expiration dates.
a. Key revocation of a “symmetric key” restricts the use of the key material.
b. Key revocation of an asymmetric key specifically refers to the private key.
c. Perform emergency revocation when keys are lost or compromised.
d. Revocation statuses should be available to all who have relied on the key.
e. Use certificate revocation lists (CRLs) or other relevant mechanisms to inform stakeholders.
f. ROI: Cost to decrypt then re-encrypt large distributed databases with a significant number of key holders.
g. ROI: Risk of long-term cryptoperiods versus short and the amount of data encrypted with one key.
h. All relevant transitions/activity should be recorded (logged) in the inventory management system (CKMS).
"		0.4	2			
Cryptography, Encryption & Key Management	Key Destruction	CEK-14	"Define, implement and evaluate processes, procedures and technical
measures to destroy keys stored outside a secure environment and revoke keys
stored in Hardware Security Modules (HSMs) when they are no longer needed, which
include provisions for legal and regulatory requirements.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		A ticket to claranet is executed and they apply their procedure	2	Team reliant on Claranet for provisioning. No policies/ procedures as evidence at this juncture		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"Key destruction removes all traces to prevent recovery by physical or electronic means.
a. When a key is to be destroyed, all key copies should be destroyed.
b. Keys should be destroyed when they are not needed to minimize compromise risks.
c. Secret and private keys should be destroyed so they cannot be recovered by any means.
d. Public keys may be kept or destroyed.
e. Notify stakeholders in advance of key destruction.
f. Consider laws, regulations, and their retention requirements for keys and/or metadata.
g. Key recovery information (KRI) should be protected against unauthorized disclosure or destruction.
h. All relevant transitions/activity should be recorded (logged) in the inventory management system (CKMS)."		No relevant controls found.	0	No relevant controls found.		"Key destruction removes all traces to prevent recovery by physical or electronic means.
a. When a key is to be destroyed, all key copies should be destroyed.
b. Keys should be destroyed when they are not needed to minimize compromise risks.
c. Secret and private keys should be destroyed so they cannot be recovered by any means.
d. Public keys may be kept or destroyed.
e. Notify stakeholders in advance of key destruction.
f. Consider laws, regulations, and their retention requirements for keys and/or metadata.
g. Key recovery information (KRI) should be protected against unauthorized disclosure or destruction.
h. All relevant transitions/activity should be recorded (logged) in the inventory management system (CKMS).
"		0.4	2			
Cryptography, Encryption & Key Management	Key Activation	CEK-15	"Define, implement and evaluate processes, procedures and technical
measures to create keys in a pre-activated state when they have been generated
but not authorized for use, which include provisions for legal and regulatory
requirements.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		A ticket to claranet is executed and they apply their procedure	2	Team reliant on Claranet for provisioning. No policies/ procedures as evidence at this juncture		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"Activated keys are used to protect information cryptographically.
a. Pre-activated keys are activated by entering the start date of the validity/cryptoperiod.
b. Keys which are not activated for use are not ready to encrypt data.
c. Non-activated keys should only be used to perform proof-of-possession or key confirmation.
d. If pre-activated keys are no longer needed, they should be destroyed.
e. If there are suspicions about the integrity of a given key, it should be moved to the compromised state.
f.All relevant transitions/activity should be recorded (logged) in the inventory management system (CKMS)."		No relevant controls found.	0	No relevant controls found.		"Activated keys are used to protect information cryptographically.
a. Pre-activated keys are activated by entering the start date of the validity/cryptoperiod.
b. Keys which are not activated for use are not ready to encrypt data.
c. Non-activated keys should only be used to perform proof-of-possession or key confirmation.
d. If pre-activated keys are no longer needed, they should be destroyed.
e. If there are suspicions about the integrity of a given key, it should be moved to the compromised state.
f.All relevant transitions/activity should be recorded (logged) in the inventory management system (CKMS).
"		0.4	2			
Cryptography, Encryption & Key Management	Key Suspension	CEK-16	"Define, implement and evaluate processes, procedures and technical
measures to monitor, review and approve key transitions from any state to/from
suspension, which include provisions for legal and regulatory requirements.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"Suspended keys are not used for a period.
a. Keys may be suspended for leaves of absence or suspicion of compromise.
b. Suspensions should be investigated before transitioning to activation, revocation, or replacement.
c. Suspended keys should not be used to encrypt data, but they can decrypt data.
d. Do not process encryption applied after the beginning of a suspension period.
e. All relevant transitions/activity should be recorded (logged) in the inventory management system (CKMS)."		No relevant controls found.	0	No relevant controls found.		"Suspended keys are not used for a period.
a. Keys may be suspended for leaves of absence or suspicion of compromise.
b. Suspensions should be investigated before transitioning to activation, revocation, or replacement.
c. Suspended keys should not be used to encrypt data, but they can decrypt data.
d. Do not process encryption applied after the beginning of a suspension period.
e. All relevant transitions/activity should be recorded (logged) in the inventory management system (CKMS).
"		0	0			
Cryptography, Encryption & Key Management	Key Deactivation	CEK-17	"Define, implement and evaluate processes, procedures and technical
measures to deactivate keys at the time of their expiration date, which include
provisions for legal and regulatory requirements.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No controls identified	0	No controls identified		Frontend load balancer certificates are managed using AWS Certificate Manager (ACM).	2	The company uses AWS Certificate Manager (ACM) to manage frontend load balancer certificates, which provides some level of control over certificate expiration. However, the information does not specify if there are well-defined processes and procedures for deactivating keys at their expiration date. The use of ACM alone, without mentioning comprehensive key deactivation practices, warrants a maturity rating of 2.		No relevant controls found.	0	No relevant controls found.		"Deactivated keys should not be used to encrypt but can be used to decrypt.
a. Upon the expiration date, keys should not be able to encrypt data.
b. The deactivated state should transition to the destroyed state when keys are no longer needed.
c. Metadata should be retained for audit purposes.
d. All relevant transitions/activity should be recorded (logged) in the inventory management system (CKMS)."		No relevant controls found.	0	No relevant controls found.		"Deactivated keys should not be used to encrypt but can be used to decrypt.
a. Upon the expiration date, keys should not be able to encrypt data.
b. The deactivated state should transition to the destroyed state when keys are no longer needed.
c. Metadata should be retained for audit purposes.
d. All relevant transitions/activity should be recorded (logged) in the inventory management system (CKMS).
"		0.4	2			
Cryptography, Encryption & Key Management	Key Archival	CEK-18	"Define, implement and evaluate processes, procedures and technical
measures to manage archived keys in a secure repository requiring least privilege
access, which include provisions for legal and regulatory requirements.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"Key archiving places keys in long-term storage.
a. Archived key material can support the later recovery of information.
b. While archived key material may be needed in the future, the key material should be destroyed when no longer required.
c. The key recovery process should include the generation, storage, and access of the long-term storage keys used to protect backed-up and archived key information.
d. Archives should be used for long-term key access.
e. The inventory system should record the storage and recovery of archived key information.
f. All relevant transitions/activity should be recorded (logged) in the inventory management system (CKMS)."		No relevant controls found.	0	No relevant controls found.		"Key archiving places keys in long-term storage.
a. Archived key material can support the later recovery of information.
b. While archived key material may be needed in the future, the key material should be destroyed when no longer required.
c. The key recovery process should include the generation, storage, and access of the long-term storage keys used to protect backed-up and archived key information.
d. Archives should be used for long-term key access.
e. The inventory system should record the storage and recovery of archived key information.
f. All relevant transitions/activity should be recorded (logged) in the inventory management system (CKMS).
"		0	0			
Cryptography, Encryption & Key Management	Key Compromise	CEK-19	"Define, implement and evaluate processes, procedures and technical
measures to use compromised keys to encrypt information only in controlled circumstance,
and thereafter exclusively for decrypting data and never for encrypting data,
which include provisions for legal and regulatory requirements.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"Compromised keys/states are keys that may be waiting for the performance of an investigation to determine the appropriate disposition. Compromised keys should be revoked using Stryker's emergency revocation policy.

When appropriate, relevant stakeholders should be notified that keys previously used to encrypt their data have been compromised and that those keys are no longer used for encryption.

These compromised keys should be notated in the organization’s “Compromised Key Lists (CKLs)” along with a summary of users notified, notification timeframes, or reasons that notifications were not made to compromised key users.

Compromised keys await an investigation to determine disposition.
a. Perform emergency revocation when keys are lost or compromised.
b. A compromised status must be available to all who have relied on the key.
c. Use CKLs to inform stakeholders.
d. Compromised status is also reflected in the inventory management system.
e. Use audits to uncover undetected compromised keys.
f. Analyze events to support recovery from compromises.
g. Detail the method for revoking and re-keying compromised keys.
h. Use cryptoperiods to limit compromised key damage.
i. A compromised key should only be used to process data it has protected for the sole purpose of de-encrypting the data.
j. All transitions/activity shall be recorded (logged) and the key state updated in the inventory management system (CKMS)."		No relevant controls found.	0	No relevant controls found.		"Compromised keys/states are keys that may be waiting for the performance of an investigation to determine the appropriate disposition. Compromised keys should be revoked using the organization’s emergency revocation policy.

When appropriate, relevant stakeholders should be notified that keys previously used to encrypt their data have been compromised and that those keys are no longer used for encryption.

These compromised keys should be notated in the organization’s “Compromised Key Lists (CKLs)” along with a summary of users notified, notification timeframes, or reasons that notifications were not made to compromised key users.

Compromised keys await an investigation to determine disposition.
a. Perform emergency revocation when keys are lost or compromised.
b. A compromised status must be available to all who have relied on the key.
c. Use CKLs to inform stakeholders.
d. Compromised status is also reflected in the inventory management system.
e. Use audits to uncover undetected compromised keys.
f. Analyze events to support recovery from compromises.
g. Detail the method for revoking and re-keying compromised keys.
h. Use cryptoperiods to limit compromised key damage.
i. A compromised key should only be used to process data it has protected for the sole purpose of de-encrypting the data.
j. All transitions/activity shall be recorded (logged) and the key state updated in the inventory management system (CKMS).
"		0	0			
Cryptography, Encryption & Key Management	Key Recovery	CEK-20	"Define, implement and evaluate processes, procedures and technical
measures to assess the risk to operational continuity versus the risk of the
keying material and the information it protects being exposed if control of
the keying material is lost, which include provisions for legal and regulatory
requirements.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"Key recovery retrieves or reconstructs keys from backups or archives. When recovering keys, consider:
a. The type of key (e.g., private signature keys or symmetric data encryption keys).
b. The application in which the key will be used (e.g., interactive communication or file storage).
c. Whether the key is “owned” by the local entity, another entity, or is shared.
d. The role of the entity in communication (e.g., sender or receiver).
e. The algorithm or computation in which the key will be used.
f. All relevant transitions/activity should be recorded (logged) in the inventory management system (CKMS).
"		No relevant controls found.	0	No relevant controls found.		"Key recovery retrieves or reconstructs keys from backups or archives. When recovering keys, consider:
a. The type of key (e.g., private signature keys or symmetric data encryption keys).
b. The application in which the key will be used (e.g., interactive communication or file storage).
c. Whether the key is “owned” by the local entity, another entity, or is shared.
d. The role of the entity in communication (e.g., sender or receiver).
e. The algorithm or computation in which the key will be used.
f. All relevant transitions/activity should be recorded (logged) in the inventory management system (CKMS).
"		0	0			
Cryptography, Encryption & Key Management	Key Inventory Management	CEK-21	"Define, implement and evaluate processes, procedures and technical
measures in order for the key management system to track and report all cryptographic
materials and changes in status, which include provisions for legal and regulatory
requirements.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		we use AWS KMS	2	Unable to verify through polices or procedures, this capability or process		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"Cryptographic Key Management Systems (CKMS), whether manual or automated, exist to process, control, store and report key management activity. 

The CKMS should:
a. Capture, track and label all changes in status.
b. Continuously monitor for unknown cryptographic assets.
c. Generate and distribute key information.
d. Acquire or generate public-key certificates.
e.Backup archive and inventory key information.
f. Maintain a database that maps entities to an organization’s certificate or key structure.
g. Provide maintenance and distribution of revoked key or certificate reports.
h. Generate audit requests and process audit responses.
i. Crypto materials include keys, certificates, and HSMs.
j. Key management technology and processes should be NIST FIPS validated and NSA-approved.
k. Cryptographic key management system security policies should protect the confidentiality, integrity, availability, and source authentication of all keys, certificates, algorithms, and metadata.
l. All relevant transitions/activity should be recorded (logged) in the inventory management system (CKMS)."		No relevant controls found.	0	No relevant controls found.		"Cryptographic Key Management Systems (CKMS), whether manual or automated, exist to process, control, store and report key management activity. 

The CKMS should:
a. Capture, track and label all changes in status.
b. Continuously monitor for unknown cryptographic assets.
c. Generate and distribute key information.
d. Acquire or generate public-key certificates.
e.Backup archive and inventory key information.
f. Maintain a database that maps entities to an organization’s certificate or key structure.
g. Provide maintenance and distribution of revoked key or certificate reports.
h. Generate audit requests and process audit responses.
i. Crypto materials include keys, certificates, and HSMs.
j. Key management technology and processes should be NIST FIPS validated and NSA-approved.
k. Cryptographic key management system security policies should protect the confidentiality, integrity, availability, and source authentication of all keys, certificates, algorithms, and metadata.
l. All relevant transitions/activity should be recorded (logged) in the inventory management system (CKMS).
"		0.4	2			
Data Security and Privacy Lifecycle Management	Security and Privacy Policy and Procedures	DSP-01	"Establish, document, approve, communicate, apply, evaluate and maintain
policies and procedures for the classification, protection and handling of data
throughout its lifecycle, and according to all applicable laws and regulations,
standards, and risk level. Review and update the policies and procedures at
least annually.
"		No controls identified	0	No controls identified		No controls identified, no customer or restricted classification data held presently.	0	No controls identified		yes we segregate PHI from PII from the rest of the data	1	Unable to verify through polices or procedures, this capability or process		Policies and procedures for data classification, protection and handling throughout its lifecycle are not explicitly defined.	1	While the company mentions data encryption at rest and in transit, as well as access controls, there is no comprehensive documentation of policies and procedures for data classification, protection and handling throughout the data lifecycle. Compliance with applicable laws, regulations and standards is not addressed. The lack of well-defined and maintained policies and procedures warrants a low maturity rating of 1.		No relevant controls found.	0	No relevant controls found.		"Policies and procedures should include provisions for the following:

a. Data classifications with clear definitions and examples.
b. Acceptable use, handling, and storage of data by classifications.
c. How long the classified data should be retained.
d. How/when the classified data should be destroyed.
e. Responsibilities of data stewards.

Maintain a data inventory and document data flow diagrams and associated technical measures.

Document data protection controls and third-party data sharing practices. This documentation and associated risks should be shared with customers and data owners as needed.

Examples include but are not limited to:
• Access controls and data loss prevention (DLP) solutions with data tagging capabilities.
• Define testing intervals based on data classification types or levels.
• Executive leadership should approve policies (cf. GRC-01).
• Note: Data life cycles include all stages (processing, storage, and transmission)."		Audit team has SOP for document control (ISSOP_QMS_001) with system to have audit. Process owner or document owner responsible for creation and modification. Review process involves process owner, quality assurance, and other relevant teams, then Audit&Assurance pushes to OnePLM (Windchill). OnePLM pushes to SMLS via API.	3	The company has a documented standard operating procedure (SOP) for document control, which includes an audit system. The process involves defined roles and responsibilities for document creation, modification, and review. The review process includes relevant stakeholders such as process owners, quality assurance, and other teams. Approved documents are stored in a centralized system called OnePLM, which integrates with SMLS via API. The existence of a documented SOP and a structured review and storage process indicates a maturity rating of 3. However, to achieve a higher rating, evidence of the SOP being consistently followed, evaluated, and updated annually would be needed, along with explicit coverage of data classification and handling throughout its lifecycle in accordance with laws, regulations, and risk levels.		"Policies and procedures should include provisions for the following:
a. Data classifications with clear definitions and examples.
b. Acceptable use, handling, and storage of data by classifications.
c. How long the classified data should be retained.
d. How/when the classified data should be destroyed.
e. Responsibilities of data stewards.

Maintain a data inventory and document data flow diagrams and associated technical measures.

Document data protection controls and third-party data sharing practices. This documentation and associated risks should be shared with customers and data owners as needed.

Examples include but are not limited to:
• Access controls and data loss prevention (DLP) solutions with data tagging capabilities.
• Define testing intervals based on data classification types or levels.
• Executive leadership should approve policies (cf. GRC-01).
• Note: Data life cycles include all stages (processing, storage, and transmission).
"		0.4	1			
Data Security and Privacy Lifecycle Management	Secure Disposal	DSP-02	"Apply industry accepted methods for the secure disposal of data from
storage media such that data is not recoverable by any forensic means.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		Data deletion should be conducted  securely and effectively to ensure that it is not recoverable by any means, including forensic techniques. Examples include but are not limited to cross-cut shredding or incinerating hard copy materials, and writing zeros.		No relevant controls found.	0	No relevant controls found.		"Data deletion should be conducted  securely and effectively to ensure that it is not recoverable by any means, including forensic techniques. Examples include but are not limited to cross-cut shredding or incinerating hard copy materials, and writing zeros.
"		0	0			
Data Security and Privacy Lifecycle Management	Data Inventory	DSP-03	"Create and maintain a data inventory, at least for any sensitive
data and personal data.
"		No business data held	0	No controls identified		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		The data inventory should provide visibility into the location, volume, and context of all sensitive data and PII through data discovery activities that result in a data inventory. Continuously support the classification process using discovery.		No relevant controls found.	0	No relevant controls found.		"The data inventory should provide visibility into the location, volume, and context of all sensitive data and PII through data discovery activities that result in a data inventory. Continuously support the classification process using discovery.
"		0	0			
Data Security and Privacy Lifecycle Management	Data Classification	DSP-04	"Classify data according to its type and sensitivity level.
"		No controls identified	0	No controls identified		Data classification is not applied, but content is low risk classification.	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		Further clarification is needed on the specific data classification levels (e.g., HIPAA, PII).	1	The company acknowledges the need for further clarification on specific data classification levels such as HIPAA and PII. This indicates an awareness of data classification requirements. However, there is no evidence provided of a comprehensive data classification system or process being in place. The maturity rating is a 1 due to the lack of a fully implemented data classification approach.		"Implement a data classification scheme to categorize data based on its sensitivity and regulatory requirements using AWS Macie or Azure Information Protection. Ensure that data is classified accurately and consistently. Use tools like Varonis or Netwrix for data discovery and classification. Conduct regular reviews to ensure compliance with data classification policies.

Implement data classification by defining organizational data categories, such as public data, confidential data, etc. Automated tools to label files, per their sensitivity levels, may be used. Appropriate security measures/protection should be implemented, per its categorization.

Use data classification, tagging, or metadata fields based on industry-standard frameworks such as (but not limited to):
a. Carnegie Mellon University: Guidelines for Data Classification
b. SANS Institute: Tagging Data to Prevent Data Leakage (Forming Content Repositories)"		No relevant controls found.	0	No relevant controls found.		"Implement data classification by defining organizational data categories, such as public data, confidential data, etc. Automated tools to label files, per their sensitivity levels, may be used. Appropriate security measures/protection should be implemented, per its categorization.

Use data classification, tagging, or metadata fields based on industry-standard frameworks such as (but not limited to):
a. Carnegie Mellon University: Guidelines for Data Classification
b. SANS Institute: Tagging Data to Prevent Data Leakage (Forming Content Repositories)
"		0.2	1			
Data Security and Privacy Lifecycle Management	Data Flow Documentation	DSP-05	"Create data flow documentation to identify what data is processed,
stored or transmitted where. Review data flow documentation at defined intervals,
at least annually, and after any change.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		yes 	1	Some data flow diagrams and documentation presented however, these were for pen testing purposes		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		Review and update the data flow documentation periodically.		No relevant controls found.	0	No relevant controls found.		"Review and update the data flow documentation periodically.
"		0.2	1			
Data Security and Privacy Lifecycle Management	Data Ownership and Stewardship	DSP-06	"Document ownership and stewardship of all relevant documented personal
and sensitive data. Perform review at least annually.
"		No controls identified	0	No controls identified		No controls identified, no customer or restricted classification data held presently.	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"A data responsibility matrix can be defined, documented, and communicated. The matrix should include, but is not limited to:

a. Data type.
b. The associated obligations (regulatory, contractual, or otherwise).
c. The persons or roles responsible for the data.
d. The frequency at which the documented personal and sensitive data should be reviewed."		No relevant controls found.	0	No relevant controls found.		"A data responsibility matrix can be defined, documented, and communicated. The matrix should include, but is not limited to:
a. Data type.
b. The associated obligations (regulatory, contractual, or otherwise).
c. The persons or roles responsible for the data.
d. The frequency at which the documented personal and sensitive data should be reviewed.
"		0	0			
Data Security and Privacy Lifecycle Management	Data Protection by Design and Default	DSP-07	"Develop systems, products, and business practices based upon a principle
of security by design and industry best practices.
"		No controls identified	0	No controls identified		Limited controls on data, retention, and storage.	0	No controls identified		No controls identified	0	No controls identified		The company follows a principle of security by design, leveraging industry-standard AWS services like Cognito, Web Application Firewall, and API Gateway for authentication and access control. They employ a blue-green deployment approach and progressive environment promotion (Edge, Test, QA, Production) to ensure secure and reliable updates. Regular penetration testing and automated security testing (DAST) are performed. All communication between services utilizes TLS 1.2 encryption.	3	The company demonstrates a commitment to security by design principles, utilizing robust AWS security services and following best practices like blue-green deployments and progressive environment promotion. Regular penetration testing and automated security testing further enhance their security posture. The consistent use of TLS 1.2 encryption for all service communication is commendable. However, the maturity rating is limited to a 3 because while these controls are in place, there is insufficient evidence of comprehensive documentation and strict adherence across all systems and processes. Addressing findings like the lack of certificate rotation for internal communication and conducting regular audits would be necessary to achieve a higher rating.		No relevant controls found.	0	No relevant controls found.		Data protection and privacy consideration must be included by default at the design stage and throughout the product development lifecycle. In addition, design documentation should clearly describe how data is protected.		Stryker has a defined secure development lifecycle including threat modeling (using SD Elements), static code analysis (SonarCloud), and software composition analysis (Black Duck). Dynamic testing and API security testing are future initiatives.	3	Stryker has implemented several industry best practices in their software development lifecycle to embed security by design principles. This includes the use of threat modeling with SD Elements to identify and mitigate risks early, static code analysis with SonarCloud to detect vulnerabilities, and software composition analysis using Black Duck to manage third-party component risks. The adoption of these tools and practices demonstrates a commitment to proactively addressing security in the development process. However, the maturity rating is set at 3 because dynamic testing and API security testing are noted as future initiatives and not yet fully integrated into the SDLC. Achieving a higher maturity would require comprehensive coverage of all critical security testing types, along with well-documented processes and consistent application across all development teams.		"Data protection and privacy consideration must be included by default at the design stage and throughout the product development lifecycle. In addition, design documentation should clearly describe how data is protected.
"		0.6	3			
Data Security and Privacy Lifecycle Management	Data Privacy by Design and Default	DSP-08	"Develop systems, products, and business practices based upon a principle
of privacy by design and industry best practices. Ensure that systems' privacy
settings are configured by default, according to all applicable laws and regulations.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		In line with privacy considerations by design and default principles, the default/out-of-the-box settings should align with the applicable regional privacy regulations.		The global privacy team conducts gap analyses to identify areas of improvement in acquired organizations. Remediation actions are developed and implemented within a specified timeframe. The current state of the remediation roadmap for the assessed accounts needs to be obtained from the product teams.	2	The company's global privacy team performs gap analyses on acquired organizations to identify areas requiring improvement in privacy practices. Based on these assessments, remediation actions are defined and executed within designated timeframes. This demonstrates an effort to align acquired entities with the company's privacy standards and address identified gaps. However, the maturity rating is limited to 2 because the current status and progress of the remediation roadmaps for the specific assessed accounts are unclear and require further input from the product teams. To achieve a higher maturity level, the company would need to provide evidence of a well-defined and consistently applied process for assessing, tracking, and remediating privacy gaps in acquired companies, along with confirmation that privacy settings are configured by default in line with applicable laws and regulations. Regular audits and reporting on the effectiveness of these privacy alignment efforts would also be expected for a more mature program.		"In line with privacy considerations by design and default principles, the default/out-of-the-box settings should align with the applicable regional privacy regulations.
"		0	0			
Data Security and Privacy Lifecycle Management	Data Protection Impact Assessment	DSP-09	"Conduct a Data Protection Impact Assessment (DPIA) to evaluate the
origin, nature, particularity and severity of the risks upon the processing
of personal data, according to any applicable laws, regulations and industry
best practices.
"		No controls identified	0	No controls identified		No controls identified, no customer or restricted classification data held presently.	0	No controls identified		Executed by an external team at each submission 	2	They previously worked with a legal team on GDPR compliance when developing their OMS, but ongoing GDPR matters like data deletion requests require manual support actions. It's unclear if they still have an internal legal team and Data Protection Officer (DPO) after the Striker acquisition.		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		Data protection impact assessment, which is essentially risk assessment from a privacy perspective, should be performed by the data controller before processing if such personal data processing is likely to result in a high risk to the rights and freedoms of natural persons.		The global privacy team conducts Data Protection Impact Assessments (DPIAs) for new or changed products and processes involving personal data using the OneTrust platform. The DPIA process includes documenting data categories, purposes, storage, security measures, and third-party involvement. Recommendations are provided based on the assessment, and the DPIA is approved once remediation actions are implemented.	3	Stryker's global privacy team has a defined process for conducting DPIAs using the OneTrust platform. The DPIA questionnaire covers key aspects such as data categories, purposes, storage, security measures, and third-party involvement. Recommendations are provided based on the assessment findings, and approval is granted once remediation actions are completed. This demonstrates a documented and followed process for evaluating data protection risks. However, to achieve a higher maturity rating, additional evidence of strict adherence to the process, regular audits, and integration with other risk management activities would be necessary.		"Data protection impact assessment, which is essentially risk assessment from a privacy perspective, should be performed by the data controller before processing if such personal data processing is likely to result in a high risk to the rights and freedoms of natural persons.
"		0.4	2			
Data Security and Privacy Lifecycle Management	Sensitive Data Transfer	DSP-10	"Define, implement and evaluate processes, procedures and technical
measures that ensure any transfer of personal or sensitive data is protected
from unauthorized access and only processed within scope as permitted by the
respective laws and regulations.
"		No controls identified	0	No controls identified		No controls identified, no customer or restricted classification data held presently.	0	No controls identified		No controls identified	0	No controls identified		The company utilizes private IP addressing and VPC peering for secure internal communication between AWS and external systems. A transit gateway establishes secure connectivity between AWS and the on-premises data center. All communication between services, including internal communication, employs TLS 1.2 encryption.	2	The use of private IP addressing, VPC peering, and a transit gateway demonstrates the company's efforts to protect data during transfer and restrict unauthorized access. The consistent use of TLS 1.2 encryption for all service communication, including internal traffic, is a positive control. However, the maturity rating is limited to a 2 because there is no specific mention of processes and technical measures to ensure personal or sensitive data is processed only within the permitted scope of applicable laws and regulations. More details on their data transfer policies, access controls, and compliance with data protection regulations would be needed to warrant a higher rating.		Encryption is used to protect customer data stored in databases. Keys are managed using AWS Key Vault. Older products have been migrated to TLS 1.2 for secure communication.	2	The company employs encryption to protect sensitive customer data at rest in databases and uses AWS Key Vault for key management. They have also migrated older products to use TLS 1.2 for secure data transmission. However, there is no mention of comprehensive processes or technical measures to ensure unauthorized access is prevented during data transfers or that data is only processed within the permitted scope. More details are needed on the specific procedures in place.		"When defining processes, procedures, and technical measures for data transfer, consider data transfer within the organization and externally.

Personal data transfer in transit must be protected by strong encryption or similar techniques to prevent unauthorized access by eavesdropping or data transfer interception."		No relevant controls found.	0	No relevant controls found.		"When defining processes, procedures, and technical measures for data transfer, consider data transfer within the organization and externally.

Personal data transfer in transit must be protected by strong encryption or similar techniques to prevent unauthorized access by eavesdropping or data transfer interception.
"		0.8	2			
Data Security and Privacy Lifecycle Management	Personal Data Access, Reversal, Rectification and Deletion	DSP-11	"Define and implement, processes, procedures and technical measures
to enable data subjects to request access to, modification, or deletion of their
personal data, according to any applicable laws and regulations.
"		No controls identified	0	No controls identified		No controls identified, no customer or restricted classification data held presently.	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		The data subject should be able to access, view, rectify, or delete personal data in the system or by logging a request with the service provider. The service provider should respond to such requests in alignment with the relevant data protection laws.		Stryker has external Data Protection Officers (DPOs) for Europe, with separate ones for Germany and other countries. The global privacy team is responsible for ensuring data subject requests under GDPR are handled within the 30-day timeframe. Requests are received through various channels and centralized in the global privacy mailbox. The team coordinates with engineering teams to gather the necessary data and applies redactions or exemptions as needed before responding to the data subject.	3	Stryker has designated external DPOs for Europe and has a process in place for handling data subject requests under GDPR. The global privacy team is responsible for ensuring compliance with the 30-day response timeframe. Requests are centralized through a dedicated mailbox, and the team collaborates with engineering to gather the required data, apply necessary redactions or exemptions, and respond to the data subject. This demonstrates a documented process for enabling data subjects to exercise their rights. However, for a higher maturity rating, additional details on the technical measures employed, such as secure communication channels and data retrieval mechanisms, would be needed, along with evidence of regular testing and auditing of the process.		"The data subject should be able to access, view, rectify, or delete personal data in the system or by logging a request with the service provider. The service provider should respond to such requests in alignment with the relevant data protection laws.
"		0	0			
Data Security and Privacy Lifecycle Management	Limitation of Purpose in Personal Data Processing	DSP-12	"Define, implement and evaluate processes, procedures and technical
measures to ensure that personal data is processed according to any applicable
laws and regulations and for the purposes declared to the data subject.
"		No controls identified	0	No controls identified		No controls identified, no customer or restricted classification data held presently.	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"Implement and maintain processes, procedures, and technical measures to ensure the following:

a. The data subject is made aware of the nature and purpose of information collection.
b. The information is relevant and limited to processing requirements.
c. Processing is performed in a reasonable manner that does not infringe upon the data subject's privacy.
d. Processing is for a specific, explicitly defined, and lawful purpose related to a function or activity of the responsible party.
e. Where the controller intends to further process the personal data for an alternative purpose to which the personal data were collected, the data subject should be informed of the purpose and provide consent before additional processing.
f. Information is stored only as long as required."		No relevant controls found.	0	No relevant controls found.		"Implement and maintain processes, procedures, and technical measures to ensure the following:
a. The data subject is made aware of the nature and purpose of information collection.
b. The information is relevant and limited to processing requirements.
c. Processing is performed in a reasonable manner that does not infringe upon the data subject's privacy.
d. Processing is for a specific, explicitly defined, and lawful purpose related to a function or activity of the responsible party.
e. Where the controller intends to further process the personal data for an alternative purpose to which the personal data were collected, the data subject should be informed of the purpose and provide consent before additional processing.
f. Information is stored only as long as required.
"		0	0			
Data Security and Privacy Lifecycle Management	Personal Data Sub-processing	DSP-13	"Define, implement and evaluate processes, procedures and technical
measures for the transfer and sub-processing of personal data within the service
supply chain, according to any applicable laws and regulations.
"		No controls identified	0	No controls identified		No controls identified, no customer or restricted classification data held presently.	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"The CSP should identify subcontractors and sub-processors that participate in the data processing, along with the chain of accountabilities and responsibilities used to ensure that data protection requirements are fulfilled.
The CSP should inform the cloud customer of any intended changes concerning the addition or replacement of subcontractors or sub-processors and allow the cloud customer to object to such changes or terminate the contract.
The data protection obligations agreed upon between the CSP and the cloud customer should be supported by any subcontractors or sub-processors used by the CSP.
The CSP remains liable to the cloud customer for data protection, regardless of whether the CSP uses subcontractors or not."		No relevant controls found.	0	No relevant controls found.		"The CSP should identify subcontractors and sub-processors that participate in the data processing, along with the chain of accountabilities and responsibilities used to ensure that data protection requirements are fulfilled.
The CSP should inform the cloud customer of any intended changes concerning the addition or replacement of subcontractors or sub-processors and allow the cloud customer to object to such changes or terminate the contract.
The data protection obligations agreed upon between the CSP and the cloud customer should be supported by any subcontractors or sub-processors used by the CSP.
The CSP remains liable to the cloud customer for data protection, regardless of whether the CSP uses subcontractors or not.
"		0	0			
Data Security and Privacy Lifecycle Management	Disclosure of Data Sub-processors	DSP-14	"Define, implement and evaluate processes, procedures and technical
measures to disclose the details of any personal or sensitive data access by
sub-processors to the data owner prior to initiation of that processing.
"		No controls identified	0	No controls identified		No controls identified, no customer or restricted classification data held presently.	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"The CSP should document and notify the data owner of the data that will be accessed by sub-processors. Information may include, but are not limited to, categories of data, special categories of data, and processing operations.
"		No relevant controls found.	0	No relevant controls found.		"The CSP should document and notify the data owner of the data that will be accessed by sub-processors. Information may include, but are not limited to, categories of data, special categories of data, and processing operations.
"		0	0			
Data Security and Privacy Lifecycle Management	Limitation of Production Data Use	DSP-15	"Obtain authorization from data owners, and manage associated risk
before replicating or using production data in non-production environments.
"		No controls identified	0	No controls identified		No controls identified, no customer or restricted classification data held presently.	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		Before replicating data or using data in non-production systems copied from the production system, perform a risk analysis and obtain data owner approval. Then, implement privacy risk mitigating techniques such as anonymization, pseudonymization, etc. (if required).		No relevant controls found.	0	No relevant controls found.		"Before replicating data or using data in non-production systems copied from the production system, perform a risk analysis and obtain data owner approval. Then, implement privacy risk mitigating techniques such as anonymization, pseudonymization, etc. (if required).
"		0	0			
Data Security and Privacy Lifecycle Management	Data Retention and Deletion	DSP-16	"Data retention, archiving and deletion is managed in accordance with
business requirements, applicable laws and regulations.
"		Data retention of snapshots is enabled, but not documented or audited	1	Ad-hoc and not complete data management processes.		No controls identified	0	No controls identified		Yes 15 years for non-medical, 99 years for medical (need to verify)	2	Verbal inputs only. Team stated they need to verify these values. No policies/procedures available as of interview		No relevant controls found.	0	No relevant controls found.		RDS snapshots are retained for 30 days, aligning with the SLA provided to customers.	2	The company has a defined data retention policy for RDS snapshots, which are kept for 30 days in accordance with customer SLAs. However, there is no information on how data archiving and deletion is managed more broadly in line with business requirements and applicable regulations. The 30-day snapshot retention alone is not sufficient evidence of a comprehensive data lifecycle management process.		"Develop and implement a data retention policy that complies with business requirements and regulatory obligations using AWS Lifecycle Management or Azure Data Lake. Ensure that data is retained and deleted according to the policy. Use tools like Varonis or Netwrix for managing data retention and deletion. Conduct regular audits to ensure compliance with data retention policies.

Organizational data retention and deletion practices encompassing both physical and electronic data should be established and implemented."		Stryker has an ongoing review of their data classification policy, led by the IT team. Higher standards and stricter access controls are applied to confidential information, including personal data. However, the specific retention periods for the assessed accounts were not readily available and required follow-up with the product teams.	1	Stryker has a data classification policy that is currently under review by the IT team. The policy applies higher standards and stricter access controls to confidential data, including personal information. This suggests that data retention and deletion are managed based on the sensitivity of the data. However, the lack of readily available information on specific retention periods for the assessed accounts indicates that the processes may not be consistently documented or followed. To improve the maturity rating, Stryker should establish and document clear data retention and deletion schedules aligned with business requirements and applicable regulations, and ensure consistent implementation across all systems and accounts.		"Organizational data retention and deletion practices encompassing both physical and electronic data should be established and implemented.
"		1	1.666666667			
Data Security and Privacy Lifecycle Management	Sensitive Data Protection	DSP-17	"Define and implement, processes, procedures and technical measures
to protect sensitive data throughout its lifecycle.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No controls identified	0	No controls identified		TLS 1.2 encryption is used for all communication between services, including internal communication. Certificates are stored in an NFS shared across all services.	2	The use of TLS 1.2 encryption for all service communication, including internally, helps protect sensitive data in transit. Storing certificates in a shared NFS provides centralized certificate management. However, the lack of details around other data protection measures throughout the lifecycle and no mention of formal processes/procedures results in a maturity rating of 2. More comprehensive controls and documentation would be needed for a higher rating.		Encryption is used to protect sensitive customer data stored in databases. Keys are managed using AWS Key Vault.	2	The company utilizes encryption to safeguard sensitive customer data at rest within databases and leverages AWS Key Vault for secure key management. However, details are lacking on the specific processes and technical measures in place to protect sensitive data throughout its entire lifecycle, from collection to destruction. More information is needed on data handling procedures during other stages such as processing, transmission, and backup.		Information rights management technology should be used and applied (when applicable) to all sensitive data. This technology can add a security layer that will help protect files from unauthorized copying, viewing, printing, forwarding, deleting, and editing.		No relevant controls found.	0	No relevant controls found.		"Information rights management technology should be used and applied (when applicable) to all sensitive data. This technology can add a security layer that will help protect files from unauthorized copying, viewing, printing, forwarding, deleting, and editing.
"		0.8	2			
Data Security and Privacy Lifecycle Management	Disclosure Notification	DSP-18	"The CSP must have in place, and describe to CSCs the procedure to
manage and respond to requests for disclosure of Personal Data by Law Enforcement
Authorities according to applicable laws and regulations. The CSP must give
special attention to the notification procedure to interested CSCs, unless otherwise
prohibited, such as a prohibition under criminal law to preserve confidentiality
of a law enforcement investigation.
"		Physio account is managed by LifeNet who owns the CSP relationship and contractual components	2	Some external controls, but not well documented nor monitored.		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		The CSP should have a process that describes how to respond to requests by law enforcement authorities, such as a subpoena, official investigations, or legal proceedings initiated by governmental and/or law enforcement officials. This process should be transparent to the interested CSCs unless otherwise prohibited.		No relevant controls found.	0	No relevant controls found.		"The CSP should have a process that describes how to respond to requests by law enforcement authorities, such as a subpoena, official investigations, or legal proceedings initiated by governmental and/or law enforcement officials. This process should be transparent to the interested CSCs unless otherwise prohibited.
"		0.4	2			
Data Security and Privacy Lifecycle Management	Data Location	DSP-19	"Define and implement, processes, procedures and technical measures
to specify and document the physical locations of data, including any locations
in which data is processed or backed up.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		The CSP should track where data is stored, processed, and backed up to ensure it is in line with the laws and regulations applicable to the CSP and ensure those locations are not prohibited. In addition, the physical locations’ registry should be kept up to date and shareable with CSC (if requested).		No relevant controls found.	0	No relevant controls found.		"The CSP should track where data is stored, processed, and backed up to ensure it is in line with the laws and regulations applicable to the CSP and ensure those locations are not prohibited. In addition, the physical locations’ registry should be kept up to date and shareable with CSC (if requested).
"		0	0			
Governance, Risk and Compliance	Governance Program Policy and Procedures	GRC-01	"Establish, document, approve, communicate, apply, evaluate and maintain
policies and procedures for an information governance program, which is sponsored
by the leadership of the organization. Review and update the policies and procedures
at least annually.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		Organizational leadership should govern the program. The program should include—but is not limited to—policies and procedures regarding legal matters, industry-specific regulations, regional requirements, compliance mandates, security and privacy requirements, and information governance. Management of each business area should include the implementation of all applicable governance policies and procedures. Policies and procedures should be reviewed and updated at least annually.		Stryker's Audit team has an SOP for document control (ISSOP_QMS_001) with a system for auditing. Training documents are managed in SMLS. Policies and procedures are reviewed every 3 years if no revisions are made beforehand. Process owners or document owners are responsible for creation and modification. The review process involves the process owner, quality assurance, and other relevant teams, then Audit & Assurance pushes the documents to OnePLM (Windchill), which then pushes them to SMLS via API.	3	Stryker has established policies and procedures for their information governance program, as evidenced by the Audit team's SOP for document control (ISSOP_QMS_001). The SOP outlines a system for auditing documents, and training materials are managed in SMLS. Policies and procedures are reviewed every 3 years if no revisions are made, with process owners responsible for creation and modification. The review process involves relevant stakeholders, and approved documents are stored in OnePLM and synced with SMLS. This demonstrates a documented and moderately consistent approach to maintaining policies and procedures. However, to achieve a higher maturity rating, Stryker should aim for annual reviews, ensure leadership sponsorship and communication of the program, and conduct regular evaluations of its effectiveness.		"Organizational leadership should govern the program. The program should include—but is not limited to—policies and procedures regarding legal matters, industry-specific regulations, regional requirements, compliance mandates, security and privacy requirements, and information governance. Management of each business area should include the implementation of all applicable governance policies and procedures. Policies and procedures should be reviewed and updated at least annually.
"		0	0			
Governance, Risk and Compliance	Risk Management Program	GRC-02	"Establish a formal, documented, and leadership-sponsored Enterprise
Risk Management (ERM) program that includes policies and procedures for identification,
evaluation, ownership, treatment, and acceptance of cloud security and privacy
risks.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"The enterprise risk management (ERM) program should consider—and not be limited to—cloud-related information security and data privacy risks. The program should include risk management elements such as risk identification, risk assessment, risk treatment, and risk reporting. Management of each business area should consist of the implementation of the applicable ERM program policies and procedures.
The ERM program should also feature a formal statement of risk appetite and may include creating and maintaining a risk register that reflects the likelihood of occurrence, potential business impacts, risk levels, and proposed mitigation actions for each risk.
"		Stryker has a third-party risk management program under the cybersecurity team, with a documented governance structure and defined responsibilities. Inherent risk of a vendor engagement is assessed based on the type of service and data involved. High risk vendors are continuously monitored. The third-party risk management program involves procurement, legal, and compliance teams in an integrated process. Risks and issues identified are communicated to the vendor and tracked to closure.	3	Stryker has a documented third-party risk management program under the cybersecurity team, which assesses the inherent risk of vendor engagements based on the type of service and data involved. High-risk vendors are subject to continuous monitoring. The program involves collaboration with procurement, legal, and compliance teams, indicating an integrated approach to managing risks. Identified risks and issues are communicated to vendors and tracked to closure. This suggests a moderately mature ERM program focused on cloud security and privacy risks. To further enhance maturity, Stryker should ensure that the program is formally sponsored by leadership, includes comprehensive risk identification and evaluation processes, and has well-defined risk treatment and acceptance criteria. Regular reviews and updates of the program's policies and procedures would also be necessary.		"The enterprise risk management (ERM) program should consider—and not be limited to—cloud-related information security and data privacy risks. The program should include risk management elements such as risk identification, risk assessment, risk treatment, and risk reporting. Management of each business area should consist of the implementation of the applicable ERM program policies and procedures.
The ERM program should also feature a formal statement of risk appetite and may include creating and maintaining a risk register that reflects the likelihood of occurrence, potential business impacts, risk levels, and proposed mitigation actions for each risk.
"		0	0			
Governance, Risk and Compliance	Organizational Policy Reviews	GRC-03	"Review all relevant organizational policies and associated procedures
at least annually or when a substantial change occurs within the organization.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"Management-approved defined policies and procedures should be communicated to all employees for adherence. Evaluate policies, procedures, and assigned responsibilities for accuracy and efficacy at least annually and when there are significant internal changes or alterations in the external operating environment.
"		Stryker's Audit team has controls and policies in place for reviewing documents every 3 years if no revisions are made beforehand. Changes go through an initial review and approval cycle. For process owner non-employment, there is a reassignment process in place.	2	Stryker has a process for reviewing policies and procedures every 3 years if no revisions are made earlier. Changes to documents undergo an initial review and approval cycle, and there is a reassignment process for when a process owner leaves the organization. This indicates the existence of some controls and processes for reviewing and updating policies. However, the 3-year review cycle may not be frequent enough to ensure that policies remain current and align with organizational changes. To improve the maturity rating, Stryker should consider implementing an annual review process for all relevant policies and procedures, especially when significant changes occur within the organization. Additionally, more details on the review and approval process, as well as the criteria for determining when a substantial change warrants an immediate review, would be needed to demonstrate a higher level of maturity.		"Management-approved defined policies and procedures should be communicated to all employees for adherence. Evaluate policies, procedures, and assigned responsibilities for accuracy and efficacy at least annually and when there are significant internal changes or alterations in the external operating environment.
"		0	0			
Governance, Risk and Compliance	Policy Exception Process	GRC-04	"Establish and follow an approved exception process as mandated by
the governance program whenever a deviation from an established policy occurs.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No controls identified	0			No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"The exception process should be defined and approved by the management team and communicated across the organization to promote adherence. Integrate exemptions with the information security risk management process, and review organizational risks whenever a deviation from an established policy occurs.
"		Individual teams provided minimal, verbal convenane to controls. No documentation conyeyed or provided to validate.	1	The company has some processes in place for handling exceptions and deviations from established policies, such as the Audit team's SOP for document control (ISSOP_QMS_001) which includes an audit system. However, there is no clear evidence of a comprehensive, organization-wide exception process that is consistently followed whenever policy deviations occur. The individual teams provided only minimal, verbal assurance of controls without supporting documentation. To achieve a higher maturity rating, the company would need to establish and document a formal exception process, communicate it to all relevant stakeholders, and demonstrate that it is routinely adhered to.		"The exception process should be defined and approved by the management team and communicated across the organization to promote adherence. Integrate exemptions with the information security risk management process, and review organizational risks whenever a deviation from an established policy occurs.
"		0	0			
Governance, Risk and Compliance	Information Security Program	GRC-05	"Develop and implement an Information Security Program, which includes
programs for all the relevant domains of the CCM.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No controls identified	0	No controls identified		Regular penetration testing is conducted on the 3D Planner and LMS components. Automated security testing, such as DAST, is performed on the QA environment.	2	The company performs regular penetration testing on key system components and conducts automated security testing in the QA environment, which contributes to an Information Security Program. However, there are no details provided about a comprehensive program covering all relevant domains of the CCM. The lack of a fully documented and implemented program across all areas results in a maturity rating of 2.		Code scans are performed during the build process. Docker containers undergo static code analysis for Kubernetes workloads. Jar files and other artifacts are scanned for VM-based deployments. Unit test cases are conducted on the security side. The Orca tool is used for global scanning and risk identification.	3	The company has implemented various security scanning and code analysis practices as part of their software development lifecycle. Static code analysis is performed on Docker containers for Kubernetes deployments, while jar files and other artifacts are scanned for VM-based deployments. Unit tests are conducted to identify security issues, and the Orca tool is used for comprehensive scanning and risk identification. These practices demonstrate a commitment to integrating security into the development process. However, more details are needed on the specific policies, standards, and governance procedures that guide these activities to warrant a higher maturity rating.		"The program should identify and assign roles, responsibilities, and management commitment.

The CCM domains to address within the information security governance program include, but are not limited to:
a. Audit and assurance
b. Application and interface security
c. Business continuity management and operational resilience
d. Change control and configuration management
e. Cryptography, encryption, and key management
f. Datacenter security
g. Data security and privacy lifecycle management
h. Governance, risk management, and compliance
i. Human resources
j. Identity and access management
k. Interoperability and portability
l. Infrastructure and virtualization security
m. Logging and monitoring
n. Security incident management, e-discovery, and cloud forensics
o. Supply chain management, transparency, and accountability
p. Threat and vulnerability management
q. Universal endpoint management

Management should promote coordination among organizational entities responsible for the different aspects of cloud security and privacy risks. Review the program as required to address threat landscape changes and substantial organization changes."		"Individual teams provided minimal, verbal convenane to controls. No documentation conyeyed or provided to validate. Audit Team Controls/ Policies in place: -ISO 27001, 20000, 9002 -Partial GDPR data -Annual external audit from SGS, in alignment to ISO standards -Just completed last surveillance audit, next audit underway "	2	The company appears to have an Information Security Program in place, as evidenced by their adherence to various ISO standards (27001, 20000, 9002) and partial GDPR compliance. They undergo annual external audits from SGS to assess alignment with these standards. However, the maturity rating is limited to a 2 because the individual teams provided only minimal, verbal assurance of controls without comprehensive supporting documentation. It's unclear if the Information Security Program covers all relevant domains of the CCM and how consistently it is implemented across the organization. To achieve a higher rating, the company would need to provide more detailed evidence of a well-documented, comprehensive program that is regularly reviewed, updated, and communicated to all stakeholders.		"The program should identify and assign roles, responsibilities, and management commitment.

The CCM domains to address within the information security governance program include, but are not limited to:
a. Audit and assurance
b. Application and interface security
c. Business continuity management and operational resilience
d. Change control and configuration management
e. Cryptography, encryption, and key management
f. Datacenter security
g. Data security and privacy lifecycle management
h. Governance, risk management, and compliance
i. Human resources
j. Identity and access management
k. Interoperability and portability
l. Infrastructure and virtualization security
m. Logging and monitoring
n. Security incident management, e-discovery, and cloud forensics
o. Supply chain management, transparency, and accountability
p. Threat and vulnerability management
q. Universal endpoint management

Management should promote coordination among organizational entities responsible for the different aspects of cloud security and privacy risks. Review the program as required to address threat landscape changes and substantial organization changes.
"		1	2.5			
Governance, Risk and Compliance	Governance Responsibility Model	GRC-06	"Define and document roles and responsibilities for planning, implementing,
operating, assessing, and improving governance programs.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		RACI charts (responsible, accountable, consulted, and informed) charts may be used to document roles and responsibilities. Specific people or teams should be assigned for each documented role in the governance program, policies, and procedures. Roles and responsibilities should be reviewed and updated periodically.		"Individual teams provided minimal, verbal convenance to controls. No documentation conveyed or provided to validate. Audit team Controls/Policies in place: -No formal risk assessment, but general security and risky standards go through leadership review -Data related standards must use legal and compliance, and EU compliance for GDPR assessments -DPO assigned Sarah Knight (Global Privacy Officer) -Contractors held to same training requirements -Need to meet with supplier team (Heather Maurer)"	2	There is some evidence that the company has defined roles and responsibilities for their governance programs. They have assigned a Data Protection Officer (Sarah Knight, Global Privacy Officer) and involve legal, compliance, and EU compliance teams in reviewing data-related standards for GDPR. Security and risk standards undergo leadership review. However, the lack of a formal risk assessment process and the minimal, undocumented assurances from individual teams suggest that the governance structure is not yet fully mature. Responsibilities for planning, implementing, operating, assessing and improving the programs are not clearly documented. Engaging with the supplier team (Heather Maurer) could help clarify third-party governance. To improve the maturity rating, the company should comprehensively document all relevant roles and responsibilities and ensure they are understood and consistently applied across the organization.		"RACI charts (responsible, accountable, consulted, and informed) charts may be used to document roles and responsibilities. Specific people or teams should be assigned for each documented role in the governance program, policies, and procedures. Roles and responsibilities should be reviewed and updated periodically.
"		0	0			
Governance, Risk and Compliance	Information System Regulatory Mapping	GRC-07	"Identify and document all relevant standards, regulations, legal/contractual,
and statutory requirements, which are applicable to your organization.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		Documentation should reflect the requirements relevant to the organization and be updated regularly to reflect changes in the internal and external operational environments. Communicate requirement changes to management and other personnel, and implement them promptly.		"Individual teams provided minimal, verbal convenance to controls. No documentation conveyed or provided to validate. Audit team Controls/ Polices in place: -Annual surveillance audit (sampling), every 3 years is full recertification -Results sent to leadership -No noncompliance noted in recent past -3 month remediation for major -1 year for minor, OFI disposition log -CI portal for tracking for decisions 3rd Party Risk team maintains: - Risk Assessment Process - Inherent Risk Questionnaire - Vendor questionnaire - Bitsight scoring system for high risk vendors"	3	The company undergoes annual surveillance audits and full recertification every 3 years to assess compliance with relevant standards and regulations. Audit results are communicated to leadership, and no recent noncompliance's were noted. They have defined remediation timelines (3 months for major issues, 1 year for minor) and maintain an OFI disposition log and CI portal for tracking decisions. The 3rd Party Risk team has a risk assessment process, inherent risk questionnaire, vendor questionnaire, and BitSight scoring for high-risk vendors, demonstrating attention to legal/contractual requirements in the supply chain. However, the specific standards, regulations, and legal/statutory requirements are not enumerated. Individual teams provided minimal, unsubstantiated assurances. To achieve a higher maturity rating, the company should document a comprehensive list of all applicable requirements, maintain evidence of compliance, and ensure consistent adherence across the organization.		"Documentation should reflect the requirements relevant to the organization and be updated regularly to reflect changes in the internal and external operational environments. Communicate requirement changes to management and other personnel, and implement them promptly.
"		0	0			
Governance, Risk and Compliance	Special Interest Groups	GRC-08	"Establish and maintain contact with cloud-related special interest
groups and other relevant entities in line with business context.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"Management should establish and maintain contact with special interest groups or professional associations to receive early warnings and advice regarding new threats, vulnerabilities, and regulatory updates.
"		No relevant controls found.	0	No relevant controls found.		"Management should establish and maintain contact with special interest groups or professional associations to receive early warnings and advice regarding new threats, vulnerabilities, and regulatory updates.
"		0	0			
Identity & Access Management	Identity and Access Management Policy and Procedures	IAM-01	"Establish, document, approve, communicate, implement, apply, evaluate
and maintain policies and procedures for identity and access management. Review
and update the policies and procedures at least annually.
"		LifeNet provisions user accounts inside Physio subscription, then admin users are able to manage access to resource and infrastructure	2	Some external controls, but not well documented nor monitored.		No controls identified	0	No controls identified		yes quarterly	2	Verbal inputs only. No policies/procedures available as of interview		Amazon Cognito is used for authentication and authorization. Users authenticate with the LMS system and receive a set of permissions and roles.	2	The company utilizes AWS Cognito for identity and access management, with users authenticating through the LMS to receive permissions and roles. This demonstrates the implementation of IAM policies and procedures. However, there is no mention of formal documentation, approval, and maintenance processes for these policies/procedures, including at least annual reviews. The lack of comprehensive documentation and review processes results in a maturity rating of 2.		No relevant controls found.	0	No relevant controls found.		"Stryker should document access control policies for the registration, management, and removal of digital identities. Additionally, the guidelines should be communicated within the organization.

The policy should:
a. Include, but not be limited to, roles and responsibilities concerning creation, changes, and deletion of access controls (including a regular review of access).
b. Conduct reviews regularly (at least annually).

The organization should leverage the identity and access management policy to establish a security baseline."		"Individual teams (with exception of 3rd Party Risk) provided minimal, verbal convenane to controls. No documentation conyeyed or provided to validate. Audit team Controls/ Polices in place: -Annual surveillance audit (sampling), every 3 years is full recertification -Results sent to leadership -No noncompliance noted in recent past -3 month remediation for major -1 year for minor, OFI disposition log -CI portal for tracking for decisions 3rd Party Risk team maintains: - Risk Assessment Process - Inherent Risk Questionaire - Vendor questionaire - Bitsight scoring system for high risk vendors"	2	The company's 3rd Party Risk team maintains a risk assessment process, inherent risk questionnaire, vendor questionnaire, and BitSight scoring for high-risk vendors, which likely includes some evaluation of identity and access management (IAM) practices. The annual audits and leadership oversight provide some assurance that IAM policies and procedures are in place. However, the specific details of these policies are not provided, and there is no clear evidence that they are reviewed and updated at least annually as required by the control. Most individual teams could not substantiate their IAM controls with documentation. To improve the maturity rating, the company should establish, document, and regularly review comprehensive IAM policies and procedures, and ensure all relevant stakeholders consistently adhere to them. More details are needed on the specific technical controls implemented.		"Organizations should document access control policies for the registration, management, and removal of digital identities. Additionally, the guidelines should be communicated within the organization.

The policy should:
a. Include, but not be limited to, roles and responsibilities concerning creation, changes, and deletion of access controls (including a regular review of access).
b. Conduct reviews regularly (at least annually).

The organization should leverage the identity and access management policy to establish a security baseline."		1.2	2			
Identity & Access Management	Strong Password Policy and Procedures	IAM-02	"Establish, document, approve, communicate, implement, apply, evaluate
and maintain strong password policies and procedures. Review and update the
policies and procedures at least annually.
"		No controls identified	0	No controls identified		Newly built systems comply with IAM requirements, but existing solutions do not. New systems are not in production use.	2	Some controls such as AWS IAM and Cognito, but not fully deployed or used.		no password only Stryker SSO	2	Verbal inputs only. No policies/procedures available as of interview		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		Establish a strong password policy that includes requirements for complexity, length, and regular rotation using AWS IAM or Azure AD. Implement multi-factor authentication (MFA) for all privileged accounts. Use tools like Okta or Duo Security for managing and enforcing password policies. Conduct regular reviews to ensure compliance with password policies.		No relevant controls found.	0	No relevant controls found.		"Organizations should establish a clear policy on strong password usage for different technical areas. Organizations should also have a monitoring mechanism to evaluate the effectiveness of policy implementation.

The policy should be reviewed periodically (at least annually) based on business requirements. In addition, the policy should clearly describe its applicability and scope, and management should promote effective communication to ensure effective implementation within the organization.

Organizations should also have policies and procedures for all personnel (employees, vendors, or other third parties) who have access to organizational data. Additionally, control-testing strategies should be employed to test these policies and be maintained regularly."		0.8	2			
Identity & Access Management	Identity Inventory	IAM-03	"Manage, store, and review the information of system identities, and
level of access.
"		No controls identified	0	No controls identified		Newly built systems comply with IAM requirements, but existing solutions do not. New systems are not in production use.	2	Some controls such as AWS IAM and Cognito, but not fully deployed or used.		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"Stryker should maintain a database of all system identities having access to different cloud environments and assets. The database should illustrate a correlation between digital identities, assets where the access is provisioned, and the type of access being provisioned (i.e., business users, system users, privilege users, etc.). In addition, the database should be regularly reviewed to ensure access is revoked or changed based on job role changes.

The identity and access management database should incorporate single sign-on and multi-factor authentication for user access.
Database access should be based on need-to-know and least-privilege principles and should follow best practices (such as role-based access control and segregation of duties). Finally, all access (especially privileged access) should be logged and monitored for anomalies and unauthorized use and linked to alerting systems as appropriate."		No relevant controls found.	0	No relevant controls found.		"Organizations should maintain a database of all system identities having access to different cloud environments and assets. The database should illustrate a correlation between digital identities, assets where the access is provisioned, and the type of access being provisioned (i.e., business users, system users, privilege users, etc.). In addition, the database should be regularly reviewed to ensure access is revoked or changed based on job role changes.

The identity and access management database should incorporate single sign-on and multi-factor authentication for user access.
Database access should be based on need-to-know and least-privilege principles and should follow best practices (such as role-based access control and segregation of duties). Finally, all access (especially privileged access) should be logged and monitored for anomalies and unauthorized use and linked to alerting systems as appropriate."		0.4	2			
Identity & Access Management	Separation of Duties	IAM-04	"Employ the separation of duties principle when implementing information
system access.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		OMS developers also handle operational. No segregation	1	Unable to verify through polices or procedures, this capability or process		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		Implement separation of duties by restricting access to production environments and ensuring that different roles have distinct permissions using AWS IAM or Azure AD. Regularly review and update access permissions. Use tools like CyberArk or BeyondTrust for managing privileged access. Conduct regular audits to ensure compliance with separation of duties policies.		No relevant controls found.	0	No relevant controls found.		"Access control policy should provide instruction on separation of environment and separation of duties, and cover the following:
a. Maintain separation of duties between the production, testing, and development environments while limiting read/write access to all environments (such as production, development, and testing).
b. Maintain separation of duties should and require multiple layers of approval (e.g., business approval, system owner approval) to ensure the integrity of access to different systems."		0.2	1			
Identity & Access Management	Least Privilege	IAM-05	"Employ the least privilege principle when implementing information
system access.
"		No controls identified	0	No controls identified		Newly built systems comply with IAM requirements, but existing solutions do not. New systems are not in production use.	2	Some controls such as AWS IAM and Cognito, but not fully deployed or used.		No controls identified	0	No controls identified		The principle of least privilege is followed, with running tasks given a particular IAM role that provides the minimum necessary permissions to access AWS resources/services.	2	The company employs the principle of least privilege, with ECS tasks running under specific IAM roles that limit access to the minimum AWS resources and services required. This demonstrates an implementation of the least privilege principle. However, there is no mention of formal policies, procedures, and documentation around consistently applying this principle across all access provisioning. The lack of comprehensive documentation and consistent application results in a maturity rating of 2.		For non-prod access, it depends on the role. Access is separated based on groups and restricted to necessary resources. Not all access is given.	2	The company follows the principle of least privilege for non-production access by granting access based on roles and restricting it to necessary resources only. This helps limit the potential impact of unauthorized access or misuse of permissions. However, the process for defining and maintaining these access roles is not clearly documented. Regular reviews of non-prod access rights are not mentioned, which are important for ensuring least privilege is consistently enforced over time.		"User and service account access should leverage access control methods, such as role-based access control (RBAC) and attribute-based access control (ABAC). In addition, conduct regular reviews of access processes (including auditing, when appropriate) to identify non-adherence to the principle of least privilege.

Restrict privileged access and access to administrative accounts should be via the principle of least privilege and a need-to-know basis. Furthermore, access should be set to “deny all“ unless specifically allowed."		No relevant controls found.	0	No relevant controls found.		"User and service account access should leverage access control methods, such as role-based access control (RBAC) and attribute-based access control (ABAC). In addition, conduct regular reviews of access processes (including auditing, when appropriate) to identify non-adherence to the principle of least privilege.

Restrict privileged access and access to administrative accounts should be via the principle of least privilege and a need-to-know basis. Furthermore, access should be set to “deny all“ unless specifically allowed."		1.2	2			
Identity & Access Management	User Access Provisioning	IAM-06	"Define and implement a user access provisioning process which authorizes,
records, and communicates access changes to data and assets.
"		No controls identified	0	No controls identified		Newly built systems comply with IAM requirements, but existing solutions do not. New systems are not in production use.	2	Some controls such as AWS IAM and Cognito, but not fully deployed or used.		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		The organizations should address any changes to the identity and access controls using the pre-established baseline. These changes could be from the proactive management of exploits via vulnerability scanning or reactive management of issues via incident management.		No relevant controls found.	0	No relevant controls found.		The organizations should address any changes to the identity and access controls using the pre-established baseline. These changes could be from the proactive management of exploits via vulnerability scanning or reactive management of issues via incident management.		0.4	2			
Identity & Access Management	User Access Changes and Revocation	IAM-07	"De-provision or respectively modify access of movers / leavers or
system identity changes in a timely manner in order to effectively adopt and
communicate identity and access management policies.
"		Access reviews are conducted periodically for Physio infra, tenant, and resources	2	Some external controls, but not well documented nor monitored.		Monthly AWS user reviews conducted	3	Manual but consistent user reviews are performed to remove users from infrastructure level access.		"For employee leaving => Stryker offboarding process
For permission revocation => permission matrix modified and applied
All these request are managed by Steven Diards (our Local IT)"	2	Team suggest local IT & Stryker resource handles process however w/o policy or procedural inputs as of this juncture.		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		Deprovisioning should automatically remove associated authorizations. For systems not integrated into automated processes, deprovisioning processes should be manually carried out by system owners. De-provisions to customer data should be made known to cloud customers where applicable.		No relevant controls found.	0	No relevant controls found.		Deprovisioning should automatically remove associated authorizations. For systems not integrated into automated processes, deprovisioning processes should be manually carried out by system owners. De-provisions to customer data should be made known to cloud customers where applicable.		1.4	2.333333333			
Identity & Access Management	User Access Review	IAM-08	"Review and revalidate user access for least privilege and separation
of duties with a frequency that is commensurate with organizational risk tolerance.
"		No controls identified	0	No controls identified		Monthly AWS user reviews conducted	3	Manual but consistent user reviews are performed to remove users from infrastructure level access.		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"Conduct regular reviews of user access rights to ensure compliance with the principle of least privilege using AWS IAM Access Analyzer or Azure AD. Document the review process and ensure it is conducted at least annually. Use tools like SailPoint or Saviynt for managing and auditing user access. Conduct regular audits to ensure compliance with access review policies.

Separation of duties should be established and implemented between development/test and production environments. With this control, a developer may use an administrator-level account with elevated privileges in the development environment and a separate account with user-level access to the production environment. In addition, appropriate levels of logs should be gathered from the production systems for further monitoring and analysis via security operations.

These operations should be managed using split knowledge and dual control where key management operations are used."		No relevant controls found.	0	No relevant controls found.		"The principle of separation of duties should also be considered when conducting user access reviews.

Access should be reviewed when users resign, are terminated, change roles, and/or no longer need the authorization to carry out duties for any other reason."		0.6	3			
Identity & Access Management	Segregation of Privileged Access Roles	IAM-09	"Define, implement and evaluate processes, procedures and technical
measures for the segregation of privileged access roles such that administrative
access to data, encryption and key management capabilities and logging capabilities
are distinct and separated.
"		No controls identified	0	No controls identified		Monthly AWS user reviews conducted	3	Manual but consistent user reviews are performed to remove users from infrastructure level access.		No controls identified	0	No controls identified		Cognito is used for authentication and authorization, providing users with a set of permissions and roles.	2	The company utilizes Amazon Cognito for managing user authentication and authorization, which allows for the segregation of privileged access roles. However, there is no explicit mention of distinct separation between administrative access to data, encryption, key management, and logging capabilities. More details on the specific implementation and evaluation of these processes would be needed to justify a higher maturity rating.		Only the DevOps team has access to make changes in production. Developers do not have direct access to the production environment.	2	The company segregates privileged access by restricting production changes to only the DevOps team. Developers are not granted direct access to make changes in production environments. This separation of duties helps mitigate the risk of unauthorized modifications and supports the principle of least privilege. However, more specifics are needed on how privileged access roles are defined, provisioned, and monitored. The processes for securing and rotating credentials for privileged accounts are not covered in detail.		"Processes and procedures should be communicated within the organization for adherence and enforcement and regularly reviewed (at least annually).

Separation of duties should be established and implemented between development/test and production environments. With this control, a developer may use an administrator-level account with elevated privileges in the development environment and a separate account with user-level access to the production environment. In addition, appropriate levels of logs should be gathered from the production systems for further monitoring and analysis via security operations.

These operations should be managed using split knowledge and dual control where key management operations are used."		No relevant controls found.	0	No relevant controls found.		"Processes and procedures should be communicated within the organization for adherence and enforcement and regularly reviewed (at least annually).

Separation of duties should be established and implemented between development/test and production environments. With this control, a developer may use an administrator-level account with elevated privileges in the development environment and a separate account with user-level access to the production environment. In addition, appropriate levels of logs should be gathered from the production systems for further monitoring and analysis via security operations.

These operations should be managed using split knowledge and dual control where key management operations are used."		1.4	2.333333333			
Identity & Access Management	Management of Privileged Access Roles	IAM-10	"Define and implement an access process to ensure privileged access
roles and rights are granted for a time limited period, and implement procedures
to prevent the culmination of segregated privileged access.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		"Level 2 support only have logs access
Level 3 support have privileged access 
Access are done through SSO => MFA for all users.
Privilège matrix is managed by our local IT (our devops)"	2	Unable to verify through polices or procedures, this capability or process		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"Administrators should be allowed to log in as themselves and elevate privilege by systematically requesting a new role assignment to obtain the rights they need to perform tasks. This can be accomplished by establishing temporary, time-bound privileged access for both on-premises and cloud-based infrastructure. The duration of approval validity should be automatically limited. Only authorized users/roles should be pre-approved to request elevation of privileged access.

The privileged access roles and rights should be reviewed periodically. Additionally, all the privilege access rights should be assigned based on multiple approval approaches (i.e., system owner, manager of user, etc.).

All privileged accounts and elevation of privileges should be monitored for suspicious activity, such as login failures or attempts to escalate permissions using a security information and event management (SIEM) solution."		No relevant controls found.	0	No relevant controls found.		"Administrators should be allowed to log in as themselves and elevate privilege by systematically requesting a new role assignment to obtain the rights they need to perform tasks. This can be accomplished by establishing temporary, time-bound privileged access for both on-premises and cloud-based infrastructure. The duration of approval validity should be automatically limited. Only authorized users/roles should be pre-approved to request elevation of privileged access.

The privileged access roles and rights should be reviewed periodically. Additionally, all the privilege access rights should be assigned based on multiple approval approaches (i.e., system owner, manager of user, etc.).

All privileged accounts and elevation of privileges should be monitored for suspicious activity, such as login failures or attempts to escalate permissions using a security information and event management (SIEM) solution."		0.4	2			
Identity & Access Management	CSCs Approval for Agreed Privileged Access Roles	IAM-11	"Define, implement and evaluate processes and procedures for customers
to participate, where applicable, in the granting of access for agreed, high
risk (as defined by the organizational risk assessment) privileged access roles.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"Processes and procedures should include the following:
• Access to privileged user IDs should be restricted to least privilege and business need to know.
• Require documented approval by authorized parties specifying required privileges.
• All actions taken by any individual with root or administrative privileges should be logged.
• Use of and changes to privileged accounts, including elevation of privileges should be monitored for suspicious activity such as logon failures or attempts to escalate permissions using a SIEM solution."		No relevant controls found.	0	No relevant controls found.		"Processes and procedures should include the following:
• Access to privileged user IDs should be restricted to least privilege and business need to know.
• Require documented approval by authorized parties specifying required privileges.
• All actions taken by any individual with root or administrative privileges should be logged.
• Use of and changes to privileged accounts, including elevation of privileges should be monitored for suspicious activity such as logon failures or attempts to escalate permissions using a SIEM solution."		0	0			
Identity & Access Management	Safeguard Logs Integrity	IAM-12	"Define, implement and evaluate processes, procedures and technical
measures to ensure the logging infrastructure is read-only for all with write
access, including privileged access roles, and that the ability to disable it
is controlled through a procedure that ensures the segregation of duties and
break glass procedures.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		All privileged/elevated access users actions are monitored and logged by Claranet in a separated account.	2	Claranet responsible for this operation/ process. Unable to verify through polices or procedures, this capability or process 		AWS CloudWatch is enabled for logging. Users are given IAM roles with the least privilege necessary to access resources.	2	The company utilizes AWS CloudWatch for logging and grants users IAM roles with the least privilege required to access resources. However, there is no explicit mention of ensuring the logging infrastructure is read-only for all with write access or controlling the ability to disable it through segregation of duties and break glass procedures. More details on these specific aspects would be needed to assign a higher maturity rating.		No relevant controls found.	0	No relevant controls found.		"Stryker should consider the following for the control's implementation:

a. Logs should be stored in a centralized log management solution with separation of duties maintained by an independent team if possible.
b. Logs should be integrated with a SIEM-type solution for real-time monitoring to raise alerts in case of any violation."		No relevant controls found.	0	No relevant controls found.		"The organization should consider the following for the control's implementation:
a. Logs should be stored in a centralized log management solution with separation of duties maintained by an independent team if possible.
b. Logs should be integrated with a SIEM-type solution for real-time monitoring to raise alerts in case of any violation."		0.8	2			
Identity & Access Management	Uniquely Identifiable Users	IAM-13	"Define, implement and evaluate processes, procedures and technical
measures that ensure users are identifiable through unique IDs or which can
associate individuals to the usage of user IDs.
"		Users are provisioned at the tenant level, but resource identities are not required to be unique or non-shared	1	Ad-hoc, host based solutions that do not align with best practices or security isolation.		AWS Cognito for customer user management, limited internal user management.	2	Customer users are managed, but internal users are not managed to the same level.		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		User access is managed through Active Directory (AD) groups. Users are granted access to resources by being added to the appropriate AD group.	2	The company uses Active Directory groups to manage user access, which allows for users to be uniquely identified and their access to be managed at a group level. However, there is no mention of a documented process for ensuring all users have unique IDs or associating individuals to the usage of those IDs. The use of AD groups provides some control but lacks evidence of a comprehensive, documented, and consistently followed process.		"All users should be assigned a unique ID before allowing access to system components or applications. Allocating a unique ID to each person with access ensures each individual is uniquely accountable for their actions. When such accountability occurs, actions taken on critical data and systems can be traced to known, authorized users and processes.

The organization should have a process to detect any creation of non -individual accounts in any infrastructure/application (either in the cloud or on-premises)."		No relevant controls found.	0	No relevant controls found.		"All users should be assigned a unique ID before allowing access to system components or applications. Allocating a unique ID to each person with access ensures each individual is uniquely accountable for their actions. When such accountability occurs, actions taken on critical data and systems can be traced to known, authorized users and processes.

The organization should have a process to detect any creation of non -individual accounts in any infrastructure/application (either in the cloud or on-premises)."		1	1.666666667			
Identity & Access Management	Strong Authentication	IAM-14	"Define, implement and evaluate processes, procedures and technical
measures for authenticating access to systems, application and data assets,
including multifactor authentication for at least privileged user and sensitive
data access. Adopt digital certificates or alternatives which achieve an equivalent
level of security for system identities.
"		SSH keys in use, but password are not prevented	2	Ad-hoc, host based solutions that do not align with best practices or security isolation.		No controls identified	0	No controls identified		No controls identified	0	No controls identified		Cognito is used for authentication and authorization. All communication between services utilizes TLS 1.2 encryption.	3	The company employs Amazon Cognito for user authentication and authorization, which provides a centralized mechanism for managing access to systems, applications, and data assets. Additionally, all communication between services, including internal communication, is encrypted using TLS 1.2. However, there is no explicit mention of multifactor authentication for privileged users and sensitive data access or the adoption of digital certificates for system identities. More comprehensive documentation and consistent application of these controls would be required to justify a higher maturity rating.		No relevant controls found.	0	No relevant controls found.		"All individual, non-console administrative access and remote access to the systems and applications should be secured using multi-factor authentication. Multi-factor authentication should contain a minimum of two of the three authentication methods:
a. Something you know, such as a password or passphrase.
b. Something you have, such as a token device or smart card or digital certification*.
c. Something you are, such as a biometric.

* Note: a digital certificate is a valid option for “something you have” as long as it is unique for a particular user)"		No relevant controls found.	0	No relevant controls found.		"All individual, non-console administrative access and remote access to the systems and applications should be secured using multi-factor authentication. Multi-factor authentication should contain a minimum of two of the three authentication methods:
a. Something you know, such as a password or passphrase.
b. Something you have, such as a token device or smart card or digital certification*.
c. Something you are, such as a biometric.

* Note: a digital certificate is a valid option for “something you have” as long as it is unique for a particular user)"		1	2.5			
Identity & Access Management	Passwords Management	IAM-15	"Define, implement and evaluate processes, procedures and technical
measures for the secure management of passwords.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"Stryker should adopt the following guidelines for the secure management of passwords:
• Always change vendor-supplied defaults and remove or disable unnecessary default accounts before installing a network system.
• All non-console administrative access should be encrypted using strong cryptography.
• Using strong cryptography, all authentication credentials (such as passwords or phrases) should be rendered unreadable during transmission and storage on all system components.
• Verify user identity before modifying any authentication credential (i.e., performing password resets, provisioning new tokens, or generating new keys).
• Passwords/passphrases should meet the criteria of industry best practices.
• Alternatively, the password/passphrases should have complexity and strength at least equivalent to the parameters specified above.
• Change user passwords/passphrases per the organization password standard.
• Limit password reuse per the organization password standard.
• Set passwords/passphrases for first-time use and upon reset to a unique value for each user and change immediately after the first use.

Document and communicate authentication policies and procedures to all users, including the following concepts:
a. Guidance on selecting strong authentication credentials.
b. Guidance for how users should protect their authentication credentials.
c. Generic user IDs are disabled or removed.
d. Shared user IDs do not exist for system administration and other critical functions.
e. Shared and generic user IDs are not used to administer any system components.
Guidance on selecting strong passwords may include suggestions to help personnel select hard-to-guess passwords that don’t contain:
f. Dictionary words
g. Information about the user (such as the user ID)
h. Names of family members, date of birth, etc.

Guidance for protecting authentication credentials may include not writing down passwords or saving them in insecure files and being alert for malicious individuals who may attempt to exploit their passwords (see NIST 800:53 password controls for details)."		No relevant controls found.	0	No relevant controls found.		"The organization should adopt the following guidelines for the secure management of passwords:
• Always change vendor-supplied defaults and remove or disable unnecessary default accounts before installing a network system.
• All non-console administrative access should be encrypted using strong cryptography.
• Using strong cryptography, all authentication credentials (such as passwords or phrases) should be rendered unreadable during transmission and storage on all system components.
• Verify user identity before modifying any authentication credential (i.e., performing password resets, provisioning new tokens, or generating new keys).
• Passwords/passphrases should meet the criteria of industry best practices.
• Alternatively, the password/passphrases should have complexity and strength at least equivalent to the parameters specified above.
• Change user passwords/passphrases per the organization password standard.
• Limit password reuse per the organization password standard.
• Set passwords/passphrases for first-time use and upon reset to a unique value for each user and change immediately after the first use.

Document and communicate authentication policies and procedures to all users, including the following concepts:
a. Guidance on selecting strong authentication credentials.
b. Guidance for how users should protect their authentication credentials.
c. Generic user IDs are disabled or removed.
d. Shared user IDs do not exist for system administration and other critical functions.
e. Shared and generic user IDs are not used to administer any system components.
Guidance on selecting strong passwords may include suggestions to help personnel select hard-to-guess passwords that don’t contain:
f. Dictionary words
g. Information about the user (such as the user ID)
h. Names of family members, date of birth, etc.

Guidance for protecting authentication credentials may include not writing down passwords or saving them in insecure files and being alert for malicious individuals who may attempt to exploit their passwords (see NIST 800:53 password controls for details)."		0	0			
Identity & Access Management	Authorization Mechanisms	IAM-16	"Define, implement and evaluate processes, procedures and technical
measures to verify access to data and system functions is authorized.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		Managed by Stryker SSO. Devops is responsible of the permission mapping for each user.	3	Managed by Stryker however, polices/procedures not yet available to validate		Cognito is used for authentication and authorization, providing users with a set of permissions and roles.	2	The company utilizes Amazon Cognito for user authentication and authorization, which helps ensure that access to data and system functions is authorized based on the assigned permissions and roles. However, there is no explicit mention of processes or procedures to verify and regularly review these access controls. More comprehensive documentation and evaluation of these processes would be needed to assign a higher maturity rating.		Access to AWS accounts is restricted to the DevOps team. Developers do not have direct access to the production environment. Changes require approval from the product owner before deployment.	3	The company has a process in place to restrict access to AWS accounts, with only the DevOps team having the ability to make changes in production. Developers are prevented from making direct changes, and all changes require approval from the product owner prior to deployment. This demonstrates a level of authorization control for access to systems and data. However, the process is not described in detail and there is no mention of how it is documented or how consistently it is followed.		"The information system should require approvals for authorizations to access the system resources and follow communicated and approved applicable policies.

Stryker should adopt multiple authorization concepts (i.e., user manager, system/information owner)."		"Individual teams provided minimal, verbal convenance to controls. No documentation conveyed or provided to validate."	1	The company text indicates that individual teams have verbally conveyed some controls related to verifying authorized access to data and system functions. However, no documentation was provided to validate these controls. The lack of documented processes and evidence of their application results in a maturity rating of 1, indicating minimal, ad-hoc controls in place.		"The information system should require approvals for authorizations to access the system resources and follow communicated and approved applicable policies.

The organization should adopt multiple authorization concepts (i.e., user manager, system/information owner)."		1.6	2.666666667			
Infrastructure & Virtualization Security	Infrastructure and Virtualization Security Policy and Procedures	IVS-01	"Establish, document, approve, communicate, apply, evaluate and maintain
policies and procedures for infrastructure and virtualization security. Review
and update the policies and procedures at least annually.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		VM are managed by Claranet	2	Managed by Claranet however, polices/procedures not yet available to validate		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"Infrastructure Virtualization Security Policy and Procedures should include, but are not limited to:

a. Governance and control VM lifecycle management.
b. Storage restriction of VM images and snapshots.
c. Backup and failover systems.
d. Tagging for the VM based on sensitivity / risk level.
e. A formal change management process for creation, storage, and use of VM images. Approve changes only when necessary.
f. Consistent security policy and configuration across the physical/virtual network.
g. Implementation of security technologies that span physical and virtual environments with a consistent policy management and enforcement framework.
To implement security technologies that span physical and virtual environments with a consistent policy management and enforcement framework.
h. Firewalls, whether physical or virtual, to isolate groups of VMs from other hosted groups.
i. Design and implementation access from each trust level to physical and virtual management and security systems."		No relevant controls found.	0	No relevant controls found.		"Infrastructure Virtualization Security Policy and Procedures should include, but are not limited to:
a. Governance and control VM lifecycle management.
b. Storage restriction of VM images and snapshots.
c. Backup and failover systems.
d. Tagging for the VM based on sensitivity / risk level.
e. A formal change management process for creation, storage, and use of VM images. Approve changes only when necessary.
f. Consistent security policy and configuration across the physical/virtual network.
g. Implementation of security technologies that span physical and virtual environments with a consistent policy management and enforcement framework.
To implement security technologies that span physical and virtual environments with a consistent policy management and enforcement framework.
h. Firewalls, whether physical or virtual, to isolate groups of VMs from other hosted groups.
i. Design and implementation access from each trust level to physical and virtual management and security systems."		0.4	2			
Infrastructure & Virtualization Security	Capacity and Resource Planning	IVS-02	"Plan and monitor the availability, quality, and adequate capacity
of resources in order to deliver the required system performance as determined
by the business.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"Projections of future capacity requirements should be made regularly (at least annually—with proactive actions taken—to mitigate risks of system overload or downtime due to overwhelming demand or increased workloads.

Cloud service providers should maximize resource utilization and optimize resource allocation to ensure adequate performance is delivered in line with the promised capacity.

Cloud service consumers should specify performance and resource requirements in line with the business objectives."		No relevant controls found.	0	No relevant controls found.		"Projections of future capacity requirements should be made regularly (at least annually—with proactive actions taken—to mitigate risks of system overload or downtime due to overwhelming demand or increased workloads.

Cloud service providers should maximize resource utilization and optimize resource allocation to ensure adequate performance is delivered in line with the promised capacity.

Cloud service consumers should specify performance and resource requirements in line with the business objectives."		0	0			
Infrastructure & Virtualization Security	Network Security	IVS-03	"Monitor, encrypt and restrict communications between environments
to only authenticated and authorized connections, as justified by the business.
Review these configurations at least annually, and support them by a documented
justification of all allowed services, protocols, ports, and compensating controls.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		Flux matrix + cloud trail monitoring alerts + ORCA + firewall rules	3	"For application and infrastructure monitoring, they use several tools:
- Imperva web application firewall to check for bot attacks, illegal access, etc.
- Orca CSPM to scan and evaluate their security posture 
- Aqua scan to check for vulnerabilities in VM images
- They also scan VMs with BlackDuck and Tenable twice
- AWS CloudTrail integrated with CloudWatch to monitor all actions in the AWS account"		All communication between services, including internal communication, utilizes TLS 1.2 encryption.	2	The company ensures that all communication between services, including internal communication, is encrypted using TLS 1.2. This demonstrates an effort to restrict communications between environments to authenticated and authorized connections. However, there is no explicit mention of monitoring these communications or conducting annual reviews supported by documented justifications of allowed services, protocols, ports, and compensating controls. More comprehensive documentation and regular evaluation of these configurations would be required to justify a higher maturity rating.		No relevant controls found.	0	No relevant controls found.		" Implement a defense-in-depth strategy for network security using AWS Security Hub, GuardDuty, and VPC Flow Logs. Regularly review and update firewall rules, security group settings, and VPC configurations. Ensure that all network communications are encrypted using protocols like TLS 1.2 or higher. Conduct regular audits to ensure compliance with network security policies.

Container application-aware network monitoring tools should be leveraged for:

a. Automated determination of proper container networking surfaces, including both inbound ports and process-port bindings.
b. Detection of traffic flows between containers and other network entities over both wire traffic and encapsulated traffic.
c. Detection of network anomalies—such as unexpected traffic flows within the organization’s network, port scanning, or outbound access to potentially dangerous destinations.
d. Detection of invalid or unexpected malicious processes—and data they introduce into the environment."		Stryker's Drupal-based CMS is hosted on hardened Amazon EC2 instances behind a VPN gateway. Access requires authentication through SecurID MFA. Azure WAF and Azure Front Door are used to protect the EC2-hosted web applications. All data in transit is encrypted using TLS 1.2.	3	The company employs several technical controls to restrict and encrypt communications between environments. These include hosting the CMS on hardened EC2 instances behind a VPN gateway, requiring MFA for access, utilizing Azure WAF and Front Door for protection, and encrypting all data in transit using TLS 1.2. These measures indicate the existence of documented processes that are followed with moderate consistency. However, there is no mention of annual reviews of these configurations or documented justifications for allowed services and protocols, preventing a higher maturity rating.		"Network communications justified by the business should be allowed, encrypted, and require authorization. Conversely, unjustified network communications should be disallowed.

Container application-aware network monitoring tools should be leveraged for:
a. Automated determination of proper container networking surfaces, including both inbound ports and process-port bindings.
b. Detection of traffic flows between containers and other network entities over both wire traffic and encapsulated traffic.
c. Detection of network anomalies—such as unexpected traffic flows within the organization’s network, port scanning, or outbound access to potentially dangerous destinations.
d. Detection of invalid or unexpected malicious processes—and data they introduce into the environment."		1	2.5			
Infrastructure & Virtualization Security	OS Hardening and Base Controls	IVS-04	"Harden host and guest OS, hypervisor or infrastructure control plane
according to their respective best practices, and supported by technical controls,
as part of a security baseline.
"		Some agents are installed, but OS and other baselines not enforced	1	Ad-hoc solutions that are incomplete and not documented nor tracked.		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"Implement OS hardening practices for all systems using CIS benchmarks or DISA STIGs. Regularly update and patch systems to address known vulnerabilities. Use tools like Ansible or Chef for automating OS hardening processes. Conduct regular audits to ensure compliance with OS hardening policies.

a. Hosts that run containers should only run containers and not other apps—such as web servers or databases—outside of containers.
b. Hosts that run containers should be continuously scanned for vulnerabilities and updated promptly.
c. The host OS should not run unnecessary system services.
d. Access to the container host should be based on the need-to-know and least privilege principles.
e. File integrity monitoring and host intrusion detection should be leveraged for containers."		No relevant controls found.	0	No relevant controls found.		"Supporting technical controls should aid situations when only the ports, protocols, and services necessary to meet business needs are provided. Such controls should be based on benchmarks (e.g., CIS).

Implement anti-malware, file integrity monitoring, and logging, and utilize hardware rooted trust in virtual trusted platform modules (vTPMs).

Whenever possible, organizations should use minimalistic, container-specific host operating systems (OSs), with all other services and functionality disabled—and with read-only file systems and other hardening practices employed to reduce attack surfaces.
a. Hosts that run containers should only run containers and not other apps—such as web servers or databases—outside of containers.
b. Hosts that run containers should be continuously scanned for vulnerabilities and updated promptly.
c. The host OS should not run unnecessary system services.
d. Access to the container host should be based on the need-to-know and least privilege principles.
e. File integrity monitoring and host intrusion detection should be leveraged for containers."		0.2	1			
Infrastructure & Virtualization Security	Production and Non-Production Environments	IVS-05	"Separate production and non-production environments.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		"2 AWS account : 1 staging and 1 production.
Environments are segregated by namespaces inside a same accounts.
All devs follow a training to perform level 3 support.
Until then they have only access to logs.è
Violation are detected and managed by Claranet our HDS CSP provided."	4	Unable to validate as procedures and policies not readily available		The deployment process involves progressively moving changes through different environments: Edge (dev), Test, QA, and Production.	3	The company follows a deployment process that separates production and non-production environments. Changes are progressively moved through different stages, including Edge (dev), Test, QA, and Production, each with its specific purpose and testing requirements. This demonstrates a structured approach to isolating development, testing, and production environments. However, more details on the specific controls and procedures in place to maintain this separation would be needed to assign a higher maturity rating.		Production and non-production environments are separated into different AWS accounts. Dedicated accounts are used for production controls and development purposes.	3	The company separates production and non-production environments into distinct AWS accounts. Dedicated accounts are utilized for production controls and development activities. This segregation of environments helps to mitigate the risk of unintended interactions and changes. However, the specifics of how this separation is enforced and maintained are not detailed, and there is no mention of a documented policy or procedure.		"Separation of the environments may include:

• Stateful inspection firewalls
• Domain/realm authentication sources
• Clear segregation of duties for personnel accessing these environments as part of their job duties

Apply sanitization routines on data before loading into non-production, and define environmental boundaries.

Production workloads should be isolated from the lower environments (e.g., development, testing) when possible."		"Code is promoted through dev/test/prod environments."	2	The company text briefly mentions that code is promoted through development, test, and production environments, indicating some level of separation between these environments. However, the lack of detail on the specific processes and controls in place to enforce this separation limits the maturity rating to a 2. More information on the technical measures and documented procedures for maintaining the segregation of environments would be needed to justify a higher rating.		"Separation of the environments may include:
• Stateful inspection firewalls
• Domain/realm authentication sources
• Clear segregation of duties for personnel accessing these environments as part of their job duties

Apply sanitization routines on data before loading into non-production, and define environmental boundaries.

Production workloads should be isolated from the lower environments (e.g., development, testing) when possible."		2	3.333333333			
Infrastructure & Virtualization Security	Segmentation and Segregation	IVS-06	"Design, develop, deploy and configure applications and infrastructures
such that CSP and CSC (tenant) user access and intra-tenant access is appropriately
segmented and segregated, monitored and restricted from other tenants.
"		LifeNet provisions user accounts inside Physio subscription, then admin users are able to manage access to resource and infrastructure	2	Account level isolation, but inside of the Physio account, user isolation is not well controlled.		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		Implement network segmentation and segregation to isolate different environments and restrict access using AWS VPC or Azure Virtual Network. Regularly review and update network configurations. Use tools like Cisco ACI or VMware NSX for advanced network segmentation. Conduct regular audits to ensure compliance with segmentation policies.		No relevant controls found.	0	No relevant controls found.		"The following should be considered for control implementation:
a. Established policies, procedures, and best-practices
b. Possible definitions of segmentation should range from “total isolation” to “partial logical separation of business-critical assets and/or personal data/sensitive user data, and sessions”.
c. Compliance with legal, statutory, and regulatory compliance obligations in-scope for particular use-cases or scenarios

Workloads between tenants and business lines should be segmented per the least privilege concept to reduce the attack surface. In addition, workload tagging, resource names, and identification should be used for workloads."		0.4	2			
Infrastructure & Virtualization Security	Migration to Cloud Environments	IVS-07	"Use secure and encrypted communication channels when migrating servers,
services, applications, or data to cloud environments. Such channels must include
only up-to-date and approved protocols.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		Older products have been migrated to TLS 1.2 for secure communication.	2	The company has made efforts to migrate older products to TLS 1.2 in order to enable secure communication channels. This shows a recognition of the importance of using up-to-date and secure protocols. However, there is no indication that this is a consistent policy across all migrations or that there are documented procedures in place to ensure only approved protocols are used.		"Secure communication—when migrating physical servers, services, applications, or data to virtualized environments—could use a combination of confidentiality, integrity, authentication, source authentication, authorization, and non-repudiation.

Building a secure channel of information transmission can be implemented at various network layers. Secure information transmission channels (ports and protocol) should be used such as : SSL, SSH, TLS operates at the application level, IPsec, ICMP at the network level, and PPTP, ARP are at the link layer.

Only up-to-date versions for these protocols should be used (deprecated versions should not be used). Furthermore, only a secure port (e.g., 443) should be used."		No relevant controls found.	0	No relevant controls found.		"Secure communication—when migrating physical servers, services, applications, or data to virtualized environments—could use a combination of confidentiality, integrity, authentication, source authentication, authorization, and non-repudiation.

Building a secure channel of information transmission can be implemented at various network layers. Secure information transmission channels (ports and protocol) should be used such as : SSL, SSH, TLS operates at the application level, IPsec, ICMP at the network level, and PPTP, ARP are at the link layer.

Only up-to-date versions for these protocols should be used (deprecated versions should not be used). Furthermore, only a secure port (e.g., 443) should be used."		0.4	2			
Infrastructure & Virtualization Security	Network Architecture Documentation	IVS-08	"Identify and document high-risk environments.
"		Applications were rated during initial deployment as low risk, not systems of record, and not containing customer or sensitive data.	3	Initial risk rating and determination, but no ongoing architecture process for changes.		No controls identified	0	No controls identified		"High level architecture are available in PSRT.
More technical schema are confidential and cannot be disclosed."	2	Unable to acquire this documentation to validate		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"The documents or diagrams should include, but are not limited to, the details below:
a. Architecture diagrams, security zone descriptions, and related policies
b. All components (physical, logical)
c. Hypervisors, workloads, hosts, and networks (physical, virtual), etc.
d. Physical site details for each workload
e. Traffic flow between various components
f. All communication channels, including out-of-band communication channels
g. Defined roles and responsibilities
h. Security zones, workloads on each host, security levels for the workloads, etc.,
i. Identify and document dependencies between the different environments and how they impact the risk assessment."		No relevant controls found.	0	No relevant controls found.		"The documents or diagrams should include, but are not limited to, the details below:
a. Architecture diagrams, security zone descriptions, and related policies
b. All components (physical, logical)
c. Hypervisors, workloads, hosts, and networks (physical, virtual), etc.
d. Physical site details for each workload
e. Traffic flow between various components
f. All communication channels, including out-of-band communication channels
g. Defined roles and responsibilities
h. Security zones, workloads on each host, security levels for the workloads, etc.,
i. Identify and document dependencies between the different environments and how they impact the risk assessment."		1	2.5			
Infrastructure & Virtualization Security	Network Defense	IVS-09	"Define, implement and evaluate processes, procedures and defense-in-depth
techniques for protection, detection, and timely response to network-based attacks.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		"For application and infrastructure monitoring, they use several tools:
- Imperva web application firewall to check for bot attacks, illegal access, etc.
- Orca CSPM to scan and evaluate their security posture 
- Aqua scan to check for vulnerabilities in VM images
- They also scan VMs with BlackDuck and Tenable twice
- AWS CloudTrail integrated with CloudWatch to monitor all actions in the AWS account
"	3	"They are protected by a Web Application firewall provided by Imperva. 
In AWS, networking is controlled through the VPC configuration between assets."		The system leverages private IP addressing and VPC peering for internal communication between AWS and external systems. A transit gateway is used to establish secure connectivity between AWS and the on-premises data center. Security groups are used to control access to publicly exposed resources.	3	The company implements network segmentation techniques such as VPC peering and transit gateways to isolate and protect sensitive environments. Security groups are employed to restrict access to publicly exposed resources. However, there is no explicit mention of defense-in-depth techniques or well-defined processes for timely response to network-based attacks. More information on incident response procedures and regular testing of these controls would be needed to justify a higher rating.		GuardDuty is used for threat detection and monitoring on AWS. CloudTrail logs are utilized for auditing purposes.	2	The company leverages AWS GuardDuty for threat detection and monitoring within their AWS environment. CloudTrail logs are used to support auditing activities. These tools provide some capabilities for detecting and responding to network-based attacks, but there is no mention of a comprehensive, defense-in-depth strategy or documented processes for effective protection and timely response.		"Vulnerabilities in a physical environment also apply in a virtual environment. Configuration flaws/vulnerabilities in the applications, firewalls, or networks will be vulnerable to exploits. Defense-in-depth techniques should be leveraged for both physical, logical, and administrative, etc., controls.

Defense-in-depth techniques/insights that should be considered include:
a. Deep packet analysis, traffic throttling, and black-holing.
b. Ingress/egress traffic patterns may include media access control (MAC) spoofing and ARP poisoning attacks and/or distributed denial-of-service (DDoS) attacks.
c. Perimeter firewalls implemented and configured to restrict unauthorized traffic.
d. Security settings enabled with strong encryption for authentication and transmission, replacing vendor default settings (e.g., encryption keys, passwords, and SNMP community strings).
e. Develop capabilities to detect unauthorized (rogue) network devices in the network and disconnect quickly."		No relevant controls found.	0	No relevant controls found.		"Vulnerabilities in a physical environment also apply in a virtual environment. Configuration flaws/vulnerabilities in the applications, firewalls, or networks will be vulnerable to exploits. Defense-in-depth techniques should be leveraged for both physical, logical, and administrative, etc., controls.

Defense-in-depth techniques/insights that should be considered include:
a. Deep packet analysis, traffic throttling, and black-holing.
b. Ingress/egress traffic patterns may include media access control (MAC) spoofing and ARP poisoning attacks and/or distributed denial-of-service (DDoS) attacks.
c. Perimeter firewalls implemented and configured to restrict unauthorized traffic.
d. Security settings enabled with strong encryption for authentication and transmission, replacing vendor default settings (e.g., encryption keys, passwords, and SNMP community strings).
e. Develop capabilities to detect unauthorized (rogue) network devices in the network and disconnect quickly."		1.6	2.666666667			
Security Incident Management, E-Discovery, & Cloud Forensics	Security Incident Management Policy and Procedures	SEF-01	"Establish, document, approve, communicate, apply, evaluate and maintain
policies and procedures for Security Incident Management, E-Discovery, and Cloud
Forensics. Review and update the policies and procedures at least annually.
"		Inherited policies from LifeNet	3	Some inherited policies and procedures, but unknown controls or efficacy.		Account relies on Stryker incident response processes.	3	Shared incident response services team with processes and escalations in place.		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"Management-approved policies and procedures for organizations and personnel who manage incidents should incorporate clearly defined roles and responsibilities—including guidelines on managing the “chain of custody” for forensic evidence collected from affected systems, devices, cloud services, applications, and personnel. These policies, procedures, and supporting systems should result in legally admissible evidence.

Policies should require establishing a core, qualified, and standing incident response team that holds the capability to assess, respond, learn, and communicate appropriately.

Appropriate reporting standards and procedures shall include lessons learned and key performance indicators (KPIs), which should be defined and implemented for incident response processes and training.

Appropriate information should be shared with affected third parties (including customers) promptly."		A formal security incident response plan is not documented for the legacy Drupal system. The new system will require a runbook but it has not been written yet. SOC Level 1 triages alerts and escalates confirmed incidents to Level 2 IR team. Asset owners are engaged to take action. Quarterly incident response exercises are conducted, but have not included cloud-specific scenarios yet.	2	The company has an incident response process in place, involving SOC Level 1 triage, escalation to Level 2 IR team, and engagement of asset owners. Quarterly exercises are conducted to test playbook execution and team responses. However, a formal incident response plan is not yet documented for the legacy system, and the runbook for the new system is still to be written. Cloud-specific incident response testing has also not been implemented. These gaps in documentation and cloud-focused processes limit the maturity rating to a 2, indicating that some controls and processes exist but lack comprehensive documentation and consistency across all systems.		"Management-approved policies and procedures for organizations and personnel who manage incidents should incorporate clearly defined roles and responsibilities—including guidelines on managing the “chain of custody” for forensic evidence collected from affected systems, devices, cloud services, applications, and personnel. These policies, procedures, and supporting systems should result in legally admissible evidence.

Policies should require establishing a core, qualified, and standing incident response team that holds the capability to assess, respond, learn, and communicate appropriately.

Appropriate reporting standards and procedures shall include lessons learned and key performance indicators (KPIs), which should be defined and implemented for incident response processes and training.

Appropriate information should be shared with affected third parties (including customers) promptly."		1.2	3			
Security Incident Management, E-Discovery, & Cloud Forensics	Service Management Policy and Procedures	SEF-02	"Establish, document, approve, communicate, apply, evaluate and maintain
policies and procedures for the timely management of security incidents. Review
and update the policies and procedures at least annually.
"		Manual review based on tickets from LifeNet and Stryker teams	2	Ad-hoc, manual review of issues and incidents.		Account relies on Stryker incident response processes.	3	Shared incident response services team with processes and escalations in place.		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		Incident response requests flow through the CCI email to the DevOps team. A dedicated person with read-only access investigates security issues.	2	The company has a basic workflow for handling incident response requests, with a dedicated email alias (CCI) for receiving requests which are then triaged by the DevOps team. A specific individual with read-only access is responsible for investigating security issues. While this provides a high-level process, there are no details on documented procedures, timelines, or evaluation of the effectiveness of this approach.		Policies and procedures should address personnel involved in the entire incident and event management lifecycle— which includes prevention, identification, investigation, and resolution—as well as periodic training for this personnel.		Individual teams provided minimal, verbal convenance to controls. No documentation conveyed or provided to validate.	1	The company has some incident response policies and procedures in place, but they are not well-documented or consistently followed across teams. The audit team mentioned having an SOP for document control (ISSOP_QMS_001) and a system for auditing, but no specific details were provided on incident management procedures. Individual teams could only provide minimal, verbal assurance of controls, without any supporting documentation. The lack of comprehensive, documented, and consistently applied incident management policies and procedures warrants a low maturity rating of 1.		Policies and procedures should address personnel involved in the entire incident and event management lifecycle— which includes prevention, identification, investigation, and resolution—as well as periodic training for this personnel.		1.4	2.333333333			
Security Incident Management, E-Discovery, & Cloud Forensics	Incident Response Plans	SEF-03	"'Establish, document, approve, communicate, apply, evaluate and maintain
a security incident response plan, which includes but is not limited to: relevant
internal departments, impacted CSCs, and other business critical relationships
(such as supply-chain) that may be impacted.'
"		Inherited policies from LifeNet	3	Some inherited policies and procedures, but unknown controls or efficacy.		Account relies on Stryker incident response processes.	3	Shared incident response services team with processes and escalations in place.		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		Incident response plans should provide a roadmap for handling incidents involving the organization’s cloud services and the products and services upon which those services rely. These plans should apply whether those dependencies are internal (such as IT, operations, support, and legal) or external (suppliers, vendors, partners, customers, and other third parties).		"A formal security incident response plan is not documented for the legacy Drupal system. The new system will require a runbook but it has not been written yet. Incident Response Process: (5-2 interview) - SOC Level 1 triages alerts from Orca and other tools, assigning priority - For confirmed incidents requiring immediate action, Level 1 escalates to Level 2 incident response - IR team reaches out to asset owners (via Suganya's team) to take action - Asset owners are expected to be available 24/7 for critical incidents - In extreme cases, a ""break glass"" process allows the security team to directly isolate resources - No defined SLAs exist yet for owner response time, but IR expects immediate response to contain incidents - Orca alerts are treated as incidents until investigated and confirmed false positive - Integrating Orca into the SOAR platform is in progress to streamline ticketing and metrics - For non-cloud, majority of alerts come through Sentinel from various integrated tools"	2	The company has an incident response process in place, but it lacks formal documentation and has some gaps. For the legacy Drupal system, no security incident response plan is documented. The new system will require a runbook, but it has not been written yet. The current process involves SOC Level 1 triaging alerts, escalating confirmed incidents to Level 2 IR, and engaging asset owners for remediation. However, there are no defined SLAs for owner response times. Integration of Orca into the SOAR platform to improve ticketing and metrics is in progress. The process covers key aspects like triaging, escalation, and stakeholder engagement, but the lack of comprehensive documentation, undefined SLAs, and varying maturities between legacy and new systems limit the overall maturity to a 2 rating.		Incident response plans should provide a roadmap for handling incidents involving the organization’s cloud services and the products and services upon which those services rely. These plans should apply whether those dependencies are internal (such as IT, operations, support, and legal) or external (suppliers, vendors, partners, customers, and other third parties).		1.2	3			
Security Incident Management, E-Discovery, & Cloud Forensics	Incident Response Testing	SEF-04	"Test and update as necessary incident response plans at planned intervals
or upon significant organizational or environmental changes for effectiveness.
"		No controls identified	0	No controls identified		Account relies on Stryker incident response processes.	3	Shared incident response services team with processes and escalations in place.		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"Conduct regular incident response tests to evaluate the effectiveness of the incident response plan using scenarios that cover different types of incidents, including cloud-specific ones. Document test results and implement improvements based on lessons learned. Use tools like Splunk Phantom or AWS Security Hub for managing and automating incident response activities.

Organizations should also test, update, and improve incident response plans after:
a. Significant organizational changes.
b. External supply chain disruptions and natural disasters.
c. Security attacks, particularly those resulting in security breaches."		No relevant controls found.	0	No relevant controls found.		"Periodically test, update, and verify the effectiveness of incident response plans using various event scenarios. For critical operations, plans should be tested at least annually. Test results should be documented and communicated—with follow-up action plans developed as appropriate.

Incident response plans should be reconciled with the organization's business continuity and disaster recovery plans.

Organizations should also test, update, and improve incident response plans after:
a. Significant organizational changes.
b. External supply chain disruptions and natural disasters.
c. Security attacks, particularly those resulting in security breaches."		0.6	3			
Security Incident Management, E-Discovery, & Cloud Forensics	Incident Response Metrics	SEF-05	"Establish and monitor information security incident metrics.
"		No controls identified	0	No controls identified		Account relies on Stryker incident response processes.	3	Shared incident response services team with processes and escalations in place.		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"Define and monitor key performance indicators (KPIs) for incident response using tools like Splunk or AWS Security Hub. Regularly review these metrics to identify areas for improvement. Document and communicate incident response metrics to relevant stakeholders. Conduct regular audits to ensure compliance with incident response metrics. 

Metrics may quantify:
a. Volume of events and ratio of events to incidents.
b. Incidents by type, product, department, severity, etc.
c. Timeliness of procedural execution for identification, investigation, and resolution.
d. Variances from documented procedures."		No relevant controls found.	0	No relevant controls found.		"Organizations should define, implement and monitor metrics associated with events and incidents to detect any weaknesses in the operational processes or technical controls which support effective incident management. Metrics may quantify:
a. Volume of events and ratio of events to incidents.
b. Incidents by type, product, department, severity, etc.
c. Timeliness of procedural execution for identification, investigation, and resolution.
d. Variances from documented procedures."		0.6	3			
Security Incident Management, E-Discovery, & Cloud Forensics	Event Triage Processes	SEF-06	"Define, implement and evaluate processes, procedures and technical
measures supporting business processes to triage security-related events.
"		No controls identified	0	No controls identified		Account relies on Stryker incident response processes.	3	Shared incident response services team with processes and escalations in place.		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"Processes, procedures, and technical measures should be defined and implemented to support the investigation and evaluation of security-related events that allow the organization to prioritize events by severity and impact. The objective for these measures is to prioritize the timely analysis of event information and rapid engagement of the incident response process.

Methodologies—including processes, tools, or machine learning algorithms used in incident handling—should periodically be reviewed for efficacy and accuracy in the current operating environment."		"SOC Level 1 triages alerts from Orca and other tools, assigning priority. For confirmed incidents requiring immediate action, Level 1 escalates to Level 2 incident response. Orca alerts are treated as incidents until investigated and confirmed false positive."	2	The company has a process for triaging security events, with SOC Level 1 assigning priority to alerts from Orca and other tools. Confirmed incidents are escalated to Level 2 incident response for further action. Orca alerts are treated as incidents until investigated and confirmed as false positives. However, the process is not fully documented, and there is no mention of defined procedures and technical measures supporting the triage process. The lack of comprehensive documentation and evaluation of the triage processes limits the maturity rating to a 2.		"Processes, procedures, and technical measures should be defined and implemented to support the investigation and evaluation of security-related events that allow the organization to prioritize events by severity and impact. The objective for these measures is to prioritize the timely analysis of event information and rapid engagement of the incident response process.

Methodologies—including processes, tools, or machine learning algorithms used in incident handling—should periodically be reviewed for efficacy and accuracy in the current operating environment."		0.6	3			
Security Incident Management, E-Discovery, & Cloud Forensics	Security Breach Notification	SEF-07	"Define and implement, processes, procedures and technical measures
for security breach notifications. Report security breaches and assumed security
breaches including any relevant supply chain breaches, as per applicable SLAs,
laws and regulations.
"		No controls identified	0	No controls identified		Account relies on Stryker incident response processes.	3	Shared incident response services team with processes and escalations in place.		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"Security breach notification processes and procedures should reflect legal and regulatory requirements, which may be applicable based on data types processed, organizational geography, or customer geography, etc. Organizational procedures should also reflect contractual customer and partner commitments regarding breach notifications. Security breach governance should include document procedures and instructions as well as training to familiarize personnel with their respective roles and responsibilities.

Accurately and promptly report information security breaches to affected, relevant parties through predefined communication channels, per applicable legal, statutory, and regulatory obligations. Clearly describe the event which occurred and its result, and identify any required or recommended actions for the affected parties. Where applicable, notifications should be sent to relevant parties in a timely manner."		No relevant controls found.	0	No relevant controls found.		"Security breach notification processes and procedures should reflect legal and regulatory requirements, which may be applicable based on data types processed, organizational geography, or customer geography, etc. Organizational procedures should also reflect contractual customer and partner commitments regarding breach notifications. Security breach governance should include document procedures and instructions as well as training to familiarize personnel with their respective roles and responsibilities.

Accurately and promptly report information security breaches to affected, relevant parties through predefined communication channels, per applicable legal, statutory, and regulatory obligations. Clearly describe the event which occurred and its result, and identify any required or recommended actions for the affected parties. Where applicable, notifications should be sent to relevant parties in a timely manner."		0.6	3			
Security Incident Management, E-Discovery, & Cloud Forensics	Points of Contact Maintenance	SEF-08	"Maintain points of contact for applicable regulation authorities,
national and local law enforcement, and other legal jurisdictional authorities.
"		No controls identified	0	No controls identified		Account relies on Stryker incident response processes.	3	Shared incident response services team with processes and escalations in place.		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"Maintain points of contact by establishing liaisons and preparing them for any investigations requiring rapid engagement with law enforcement.

Document and update security incident contact information regularly. Additionally, processes and responsibilities should be documented and maintained for information accuracy that reflects organizational changes to internal operations and external regulatory environments. Personnel sending security notifications should use these identified contacts."		No relevant controls found.	0	No relevant controls found.		"Maintain points of contact by establishing liaisons and preparing them for any investigations requiring rapid engagement with law enforcement.

Document and update security incident contact information regularly. Additionally, processes and responsibilities should be documented and maintained for information accuracy that reflects organizational changes to internal operations and external regulatory environments. Personnel sending security notifications should use these identified contacts."		0.6	3			
Threat & Vulnerability Management	Threat and Vulnerability Management Policy and Procedures	TVM-01	"Establish, document, approve, communicate, apply, evaluate and maintain
policies and procedures to identify, report and prioritize the remediation of
vulnerabilities, in order to protect systems against vulnerability exploitation.
Review and update the policies and procedures at least annually.
"		Manual review based on tickets from LifeNet and Stryker teams	2	Ad-hoc, manual review of issues and incidents.		No controls identified	0	No controls identified		Quarterly we perform a deep threat and vulnerability review.	3	Team executes vulnerability threat reviews quarterly. No evidence or policy update process or that of prioritizing of vulnerability remediation		Regular penetration testing is conducted on the 3D Planner and LMS components separately. Automated security testing, such as DAST (Dynamic Application Security Testing), is performed on the QA environment.	2	The company performs regular penetration testing and automated security testing (DAST) to identify vulnerabilities in their systems. However, there is no information on formal policies and procedures governing vulnerability management, including prioritization and remediation timelines. More details on the vulnerability management lifecycle and its integration into the SDLC would be needed to justify a higher rating.		Orca tool is used for global scanning and risk identification. Identified risks are communicated to the team for patching.	2	The company uses the Orca tool to perform global vulnerability scanning and risk identification within their environment. When risks are identified by this tool, they are communicated to the relevant teams for patching and remediation. This demonstrates some level of vulnerability management process. However, there are no specifics provided on the policies for prioritization, SLAs for remediation timelines, or metrics for evaluating the effectiveness of this program.		"A policy on threat and vulnerability management (TVM) should be established that includes the intent, purpose, and governance of how a CSP or CSC must address threats and vulnerabilities for their respective scope under the SSRM.

At a minimum, the policy should specify:
a. What should be covered under the scope, especially the need to comply with applicable laws, regulations, and contractual requirements.
b. The frequency of assessments.
c. The methods that should be used.
d. How and when assessments and significant vulnerabilities should be reported, including when it’s appropriate to share vulnerability information with customers and business partners.
e. How reports should be reviewed.
f. How actions to address relevant risks and opportunities should be tracked to closure.
g. Approval of CSP native and (where applicable) third-party data/asset protection capabilities and relevant services for use by appropriate CSC authorities.
h. A well-defined incident response process aligned with an organization's risk tolerance, accompanied by appropriate communication and notifications.
i. Acceptable periods of remediation of threats in order of severity and criticality of computing infrastructure.
j. Log review and correlation procedures with appropriate threat intelligence capabilities for log, events, metrics, and incidents (preferably through a centralized service)."		"Individual teams execute. No defined"	1	There is minimal evidence of vulnerability management policies and procedures. The statement "Individual teams execute" suggests that some vulnerability management activities are performed, but there are no defined, documented, and consistently followed processes across the organization. The lack of a centralized, standardized approach to identifying, reporting, and prioritizing vulnerability remediation indicates an ad-hoc and immature vulnerability management posture, warranting a low maturity rating of 1.		"A policy on threat and vulnerability management (TVM) should be established that includes the intent, purpose, and governance of how a CSP or CSC must address threats and vulnerabilities for their respective scope under the SSRM.

At a minimum, the policy should specify:
a. What should be covered under the scope, especially the need to comply with applicable laws, regulations, and contractual requirements.
b. The frequency of assessments.
c. The methods that should be used.
d. How and when assessments and significant vulnerabilities should be reported, including when it’s appropriate to share vulnerability information with customers and business partners.
e. How reports should be reviewed.
f. How actions to address relevant risks and opportunities should be tracked to closure.
g. Approval of CSP native and (where applicable) third-party data/asset protection capabilities and relevant services for use by appropriate CSC authorities.
h. A well-defined incident response process aligned with an organization's risk tolerance, accompanied by appropriate communication and notifications.
i. Acceptable periods of remediation of threats in order of severity and criticality of computing infrastructure.
j. Log review and correlation procedures with appropriate threat intelligence capabilities for log, events, metrics, and incidents (preferably through a centralized service)."		1.8	2.25			
Threat & Vulnerability Management	Malware Protection Policy and Procedures	TVM-02	"Establish, document, approve, communicate, apply, evaluate and maintain
policies and procedures to protect against malware on managed assets. Review
and update the policies and procedures at least annually.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No controls identified	0	No controls identified		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		"Malware protection policies should focus on inspecting both inbound and outbound traffic and implementing controls to detect, prevent, block, and remove malware. Include expectations of time objectives for remediation programs that seek to ensure systems are free of infection when they connect to enterprise computing resources. Malware protection should be integrated across all computing infrastructure, including compute, network, endpoints, and secure access gateways.

Organizations should centrally manage malware protection mechanisms, including planning, implementing, assessing, authorizing, and monitoring organizational-defined malware protection security controls. This process will help to cohesively address malware within predefined timeframes.

Threat and vulnerability management policy should include the ability to address malware as a specific threat element. This should provide the organization with a guideline to handle malware using appropriate tools, relevant automation, and operational frameworks to meet their risk tolerance.

If malware is identified by antivirus or anti-malware applications using a signature- or behavior-based detection process, malware removal should be updated according to applicable contractual agreements and organizational standards. Additionally, prevention software and associated signatures should be deployed centrally by the service provider throughout their environment."		No relevant controls found.	0	No relevant controls found.		"Malware protection policies should focus on inspecting both inbound and outbound traffic and implementing controls to detect, prevent, block, and remove malware. Include expectations of time objectives for remediation programs that seek to ensure systems are free of infection when they connect to enterprise computing resources. Malware protection should be integrated across all computing infrastructure, including compute, network, endpoints, and secure access gateways.

Organizations should centrally manage malware protection mechanisms, including planning, implementing, assessing, authorizing, and monitoring organizational-defined malware protection security controls. This process will help to cohesively address malware within predefined timeframes.

Threat and vulnerability management policy should include the ability to address malware as a specific threat element. This should provide the organization with a guideline to handle malware using appropriate tools, relevant automation, and operational frameworks to meet their risk tolerance.

If malware is identified by antivirus or anti-malware applications using a signature- or behavior-based detection process, malware removal should be updated according to applicable contractual agreements and organizational standards. Additionally, prevention software and associated signatures should be deployed centrally by the service provider throughout their environment."		0	0			
Threat & Vulnerability Management	Vulnerability Remediation Schedule	TVM-03	"Define, implement and evaluate processes, procedures and technical
measures to enable both scheduled and emergency responses to vulnerability identifications,
based on the identified risk.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		AV update every day at 10 AM	0	No controls identified		No relevant controls found.	0	No relevant controls found.		Vulnerabilities identified by Orca are communicated to the team. The DevOps team collaborates with the dev team to recommend and implement patches.	2	When the Orca tool identifies vulnerabilities, the information is communicated to the DevOps and dev teams. Those teams then collaborate to recommend and implement patches to remediate the issues. This shows a process for responding to identified vulnerabilities, but lacks details on the prioritization, consistency, and evaluation of this process. No mention of SLAs or the ability to handle emergency responses.		"Establish a formal vulnerability management process that includes regular scans, risk assessment, and prioritization of vulnerabilities using tools like Tenable.io or Qualys. Ensure that critical vulnerabilities are remediated within defined SLAs and track remediation progress using a centralized system like Jira. Conduct regular audits to ensure compliance with vulnerability management policies.

Vulnerability remediation schedules should be approved and communicated to all relevant stakeholders (and included in SLA's)."		No relevant controls found.	0	No relevant controls found.		"An integrated TVM  system should be implemented that can maintain records of threats and vulnerabilities found over time and the result of their mitigation actions. The Integrated TVM system should be used to mitigate all future risks, by leveraging the previous experiences of the mitigation activities.

A full remediation schedule should be considered. The schedule should classify and prioritize vulnerabilities in order of their severity and threat to the environment, aligned to the expectations of TVM Policy.

Vulnerability remediation schedules should be approved and communicated to all relevant stakeholders (and included in SLA's)."		0.4	2			
Threat & Vulnerability Management	Detection Updates	TVM-04	"Define, implement and evaluate processes, procedures and technical
measures to update detection tools, threat signatures, and indicators of compromise
on a weekly, or more frequent basis.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		Tools are provided by Stryker (Blackduck, ORCA)	2	Team suggests Stryker is responsible and with tools illustrated. No policies or procedures or process documentation available to validate		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		A rolling schedule of detection, reporting, and mitigation should be established so that all actions to address threats and non-conformance are performed on time and reported to the integrated TVM system for monitoring and oversight. In addition, where applicable, implement automation so that threats and non-conformance are mitigated on time.		No relevant controls found.	0	No relevant controls found.		A rolling schedule of detection, reporting, and mitigation should be established so that all actions to address threats and non-conformance are performed on time and reported to the integrated TVM system for monitoring and oversight. In addition, where applicable, implement automation so that threats and non-conformance are mitigated on time.		0.4	2			
Threat & Vulnerability Management	External Library Vulnerabilities	TVM-05	"Define, implement and evaluate processes, procedures and technical
measures to identify updates for applications which use third party or open
source libraries according to the organization's vulnerability management policy.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		Currently done manually. Planned to integrate dependency track in our CI to fix it	1	Manual process. No policies or procedures available to validate		No relevant controls found.	0	No relevant controls found.		Static code analysis is performed on Docker containers for Kubernetes workloads and on jar files and other artifacts for VM-based deployments.	2	The company performs static code analysis on Docker containers used in Kubernetes deployments as well as on artifacts like jar files used in VM deployments. This provides some ability to identify vulnerabilities in third-party and open source components. However, there is no information on how frequently this analysis is performed, how findings are triaged and remediated, or how this process is evaluated for effectiveness.		"Where a CSC or a CSP uses third party or open source libraries, these should be tracked, scanned and reported on in the integrated TVM system. Installed or used packages, libraries and/or runtimes that are part of their solution with their running version should be included. TVM scans can be performed automatically and the findings should be promptly reported to the integrated TVM system. This activity should be monitored to avoid operational gaps.

The organization should leverage global threat intelligence about threat signatures and vulnerability databases that may contain indicators of attack and compromise. It should also consider implementing automated & recurring processes so that human errors can be avoided."		"AppSec Team: Black Duck SCA Tool Functionality: Open-source vulnerability Management Detects Inventory all open source in apps & containers. Protect by finding and fixing known open-source vulnerabilities in development and production."	2	The company uses Black Duck SCA tool for managing open-source vulnerabilities in applications and containers. The tool detects and inventories all open-source components, helping to identify and fix known vulnerabilities in development and production environments. However, there is no mention of a defined process for regularly updating the tool's vulnerability database or evaluating and prioritizing the identified vulnerabilities based on risk. The lack of documented processes and evaluation criteria limits the maturity rating to a 2, indicating that while some controls are in place, they may not be consistently applied or optimized.		"Where a CSC or a CSP uses third party or open source libraries, these should be tracked, scanned and reported on in the integrated TVM system. Installed or used packages, libraries and/or runtimes that are part of their solution with their running version should be included. TVM scans can be performed automatically and the findings should be promptly reported to the integrated TVM system. This activity should be monitored to avoid operational gaps.

The organization should leverage global threat intelligence about threat signatures and vulnerability databases that may contain indicators of attack and compromise. It should also consider implementing automated & recurring processes so that human errors can be avoided."		0.6	1.5			
Threat & Vulnerability Management	Penetration Testing	TVM-06	"Define, implement and evaluate processes, procedures and technical
measures for the periodic performance of penetration testing by independent
third parties.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		Pentest are done by a Stryker team from another division every 6 month (FDA compliance).	4	3rd party via Stryker executes		Regular penetration testing is conducted on the 3D Planner and LMS components separately by independent third parties.	3	The company engages independent third parties to perform periodic penetration testing on their key system components (3D Planner and LMS). However, there is no information on the specific processes, procedures, or technical measures governing these tests. More details on the frequency, scope, and methodology of the penetration testing program would be needed to warrant a higher rating.		Penetration testing is performed on automation scales. More details on the penetration testing process should be obtained from the Relays and Engineering team.	1	It is mentioned that penetration testing is performed on automation scales, which suggests some level of periodic testing. However, no details are provided on the frequency, scope, or independence of this testing. The need to obtain more information from other teams indicates a lack of centralized visibility and control over this process. Without further details, only a minimal maturity rating can be justified.		"Schedule regular penetration tests conducted by independent third parties using reputable firms like NCC Group or Offensive Security. Ensure that findings are documented, prioritized, and remediated promptly. Integrate penetration test results into the overall vulnerability management program. Conduct regular audits to ensure compliance with penetration testing policies.

A written and signed authorization should be obtained and verified before and after services are rendered. Penetration test schedules should be published on the integrated TVM system to ensure tactics, techniques, and test procedures adhere to documented policies."		"AppSec Team: -Pentesting or 3rd Party scanning: BlackDuck"	1	The company performs some penetration testing using the Black Duck tool, but there is no evidence of a well-defined and regularly scheduled process for independent third-party penetration testing. The reliance on a single tool and the lack of mention of independent testing or defined testing intervals suggests an ad-hoc approach to penetration testing, warranting a low maturity rating of 1.		"A formal schedule of red team exercises interspersed with risk assessments, remediation, and penetration testing aligned to the applicable service model (I-P-SaaS, and XaaS) should be established. Penetration testing should comply with all applicable laws and regulations.
A written and signed authorization should be obtained and verified before and after services are rendered. Penetration test schedules should be published on the integrated TVM system to ensure tactics, techniques, and test procedures adhere to documented policies."		1.6	2.666666667			
Threat & Vulnerability Management	Vulnerability Identification	TVM-07	"Define, implement and evaluate processes, procedures and technical
measures for the detection of vulnerabilities on organizationally managed assets
at least monthly.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		Antivirus scan performed on real time	3	Team does not mention scanning for this control however it is executed via 3rd party (pen test & local team vulnerability scanning) 		Automated security testing, such as DAST (Dynamic Application Security Testing), is performed on the QA environment.	2	The company conducts automated vulnerability scanning (DAST) on their QA environment, indicating some level of regular vulnerability detection. However, the frequency of these scans is not specified, and there is no mention of vulnerability scanning on production or other environments. More information on the comprehensiveness and consistency of vulnerability scanning across all relevant assets would be required to justify a higher rating.		No relevant controls found.	0	No relevant controls found.		Perform regular vulnerability scans on all managed assets using tools like Tenable.io or Qualys. Ensure that scans are conducted at least monthly and that findings are documented and prioritized for remediation. Integrate scanning results into the overall vulnerability management program. Conduct regular audits to ensure compliance with vulnerability identification policies.		"AppSec Team: -Orca for scanning across env -Scanning for legacy/non-updated apps: BlackDuck looking at SBOM, taskforce asking for more connections/actions, CCOE to look at old/unused envs"	2	The company uses Orca for vulnerability scanning across environments and for legacy or non-updated applications. Orca scans the software bill of materials (SBOM) to identify vulnerabilities. A taskforce is working on increasing the connections and actions based on Orca findings, and the Cloud Center of Excellence (CCOE) is looking into old and unused environments. However, there is no mention of a defined process for performing these scans on a monthly or more frequent basis. The lack of a documented and consistently applied scanning schedule limits the maturity rating to a 2.		"The integrated TVM system should track vulnerabilities to closure and report them to build oversight of residual risks. Furthermore, the system should retain information that can be reused in future remediation activities.

Organizations should consider establishing an external-facing vulnerability disclosure program to allow external parties to communicate detected vulnerabilities."		1	2.5			
Threat & Vulnerability Management	Vulnerability Prioritization	TVM-08	"Use a risk-based model for effective prioritization of vulnerability
remediation using an industry recognized framework.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		"Patch and update are done on new version release.
Critical/high are mandatory for patch.
Medium/low are mandatory if exploitable else it is mark as nice to have.
For patches included in release => handled as a normal development.
For a hotfix for production => Patch must be validated bu V&V to ensure no regression. It mean : deployment to preprod then validation then potential fix and revalidation then deployment to production."	3	Team does not allude to risk based model or framework for vulnerability prioritization. Vulnerability classification notes provided to left		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		Vulnerabilities should be prioritized in terms of their relative risk, importance, organizational impact, and urgency. When evaluating impact, consider exposure levels to applicable threats from the organization’s specific usage and/or implementation. When evaluating importance, consider the criticality and value of the affected assets. Finally, when assessing urgency, consider the Common Vulnerability Scoring System (CVSS) ratings and timeframes, the relevance to current and ongoing threats, and the effort required for remediation.		"AppSec Team: Orca rolls up data across BU or env."	1	The company uses Orca to aggregate vulnerability data across business units and environments, which could potentially support a risk-based prioritization model. However, there is no explicit mention of using an industry-recognized framework or a defined risk-based model for prioritizing vulnerability remediation. The lack of a documented and standardized approach to risk-based prioritization indicates an ad-hoc process, resulting in a low maturity rating of 1.		Vulnerabilities should be prioritized in terms of their relative risk, importance, organizational impact, and urgency. When evaluating impact, consider exposure levels to applicable threats from the organization’s specific usage and/or implementation. When evaluating importance, consider the criticality and value of the affected assets. Finally, when assessing urgency, consider the Common Vulnerability Scoring System (CVSS) ratings and timeframes, the relevance to current and ongoing threats, and the effort required for remediation.		0.6	3			
Threat & Vulnerability Management	Vulnerability Management Reporting	TVM-09	"Define and implement a process for tracking and reporting vulnerability
identification and remediation activities that includes stakeholder notification.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		"A ticket is created through redmine in the Product owner backlog. It must be tagged with the ""Security"" tag.
Communication and prioritization is done by the Product Owner."	3	Control partially met - Appears that no stakeholder notification other than manual process exists. No policies or procedures to validate		No relevant controls found.	0	No relevant controls found.		Identified vulnerabilities are tracked as Jira tickets and linked to change requests.	2	The company tracks identified vulnerabilities as tickets in Jira and links them to associated change requests. This provides a mechanism for tracking and reporting on vulnerability remediation activities. However, there is no mention of how other stakeholders are notified or how the overall process is managed and communicated.		The integrated TVM system should have comprehensive vulnerability tracking capabilities. Capabilities should include when discoveries were made and remediated, systems impacted, reasons for the delay (where applicable), and any communications that may have been made to stakeholders.		"AppSec Team: For in prod Orca detections process for remediation: task force to reach out to owner for alerting and tracking"	2	The company has a process for tracking and reporting vulnerability remediation activities for in-production Orca detections. A task force reaches out to asset owners for alerting and tracking the remediation progress. However, there is no mention of a comprehensive process that includes stakeholder notification beyond the asset owner. The lack of a fully defined and documented process for tracking, reporting, and notifying all relevant stakeholders limits the maturity rating to a 2.		The integrated TVM system should have comprehensive vulnerability tracking capabilities. Capabilities should include when discoveries were made and remediated, systems impacted, reasons for the delay (where applicable), and any communications that may have been made to stakeholders.		1	2.5			
Threat & Vulnerability Management	Vulnerability Management Metrics	TVM-10	"Establish, monitor and report metrics for vulnerability identification
and remediation at defined intervals.
"		No controls identified	0	No controls identified		No controls identified	0	No controls identified		"We perform a global analysis each quarter.
It generate a remediation plan for the next release.
For the OMS is it quite up to date (we perform patching at the start of each release).
For Blueprint each new version is patched with all available patches.
Issue are send to each team Product Owner. If not prioritized it is escalated to the Program Manager."	3	Control partially met - Appears that no stakeholder notification other than manual process exists. No policies or procedures to validate		No relevant controls found.	0	No relevant controls found.		No relevant controls found.	0	No relevant controls found.		The integrated TVM system should be used to collect and report metrics about the vulnerability management program. Metrics should demonstrate the coverage, efficacy, and efficiency of operational TVM activities.		No relevant controls found.	0	No relevant controls found.		The integrated TVM system should be used to collect and report metrics about the vulnerability management program. Metrics should demonstrate the coverage, efficacy, and efficiency of operational TVM activities.		0.6	3

---

Above, I have provided to you data for the following Statement of Work:

Page 1
STATEMENT OF WORK NO 1 Cloud Security Assessment
This Statement of Work for Cloud Security Assessment (this “SOW”) is entered into effective as of March 8,
2024 (“SOW Effective Date”) by and between Stryker Corporation, with a place of business at 1941
Stryker Way Portage, MI 49002 (“Stryker” or “Customer”) and World Wide Technology, LLC, with a place
of business at One World Wide Way, Saint Louis, Missouri 63146 (“Contractor” or “WWT”) subject to the
Master Services Agreement entered into by and between Stryker Corporation and Contractor effective July
10, 2023 (the “Agreement”). Capitalized terms not elsewhere defined in this SOW shall have the meanings
ascribed to them in the Agreement.
1. Term.
a. SOW Term. This SOW is effective as of the SOW Effective Date and shall continue in full force
and effect until the earlier of: (a) the Completion Date (as defined below), or (b) termination
of this SOW in accordance with the terms of the Agreement (the “SOW Term”). In the event
this SOW survives termination of the Agreement, the terms of the Agreement shall continue
to govern for so long as the SOW remains in effect.
b. Completion Date. The Services set forth in this SOW are scheduled to commence on the SOW
Effective Date or March 08, 2024, with an estimated completion date of April 26, 2024 or the
date in which the Services or Deliverables are completed in accordance with the Timelines or
Milestones set forth in this SOW and have been accepted by Stryker (the “Completion Date”).
2. Contractor Project Manager. Contractor’s manager for performance of the Services is:
Name: Dennis Thomasson
Title: Senior Director
Tel. No.: (309) 408-2899
Email Address: Dennis.Thomasson@wwt.com
3. Stryker Project Manager. Stryker’s manager for review, approval, and acceptance of the Services is:
Name: Suganya Sivakumar
Title: Sr. Manager
Tel. No.: 269 251 2958
Email Address: Suganya.sivakumar@stryker.com
4. Scope of Services. Pursuant to this SOW, Contractor shall perform the following services: This project
aims to deliver an overview of current cloud governance and security control domains. As part of this,
WWT will perform interviews with relevant Stryker resources, review relevant documentation, and
examine Stryker’s existing Amazon Web Services (AWS) environments. The output will be a review of
current controls, a gap analysis of each control domain, and recommendations for further efforts. As
described above, this project is intended to align with the Cloud Security Alliance’s Cloud Control
Matrix version 4.0 (CCM) as a guide for completeness and coverage of control domains. This is scoped
to include the following CCM domains: Application and Interface Security, Audit Assurance and
Page 2
Compliance, Business Continuity Management and Operational Resilience, Change Control and
Configuration Management, Data Security and Information Lifecycle Management, Encryption and Key
Management, Governance and Risk Management, Identity and Access Management (IAM),
Infrastructure and Virtualization Security, Security Incident Management/E-Discovery/Cloud
Forensics, and Threat and Vulnerability Management. (the “Services”).
This SOW has been developed based on the assumption that there are no scheduled cutover/change
windows or change control requirements. If change control or scheduled cutovers are required, this
will be managed through the Change Order process
Knowledge transfer provided by WWT will not include any courseware or formal lab manuals. It will
be hands-on knowledge transfer on the deployed solution within the Stryker environment. This is an
informal sharing of information between technical peers and is intended to supplement but not replace
any manufacturer’s formal system implementation or administration classes. Formal classroom
offerings may be offered and scheduled through WWT
5. Deliverables. In performing or as a result of the performance of the Services, Contractor shall provide
the deliverables described in Exhibit A to this SOW (the “Deliverables”).
6. Charges and Payment.
a. Charges. In consideration for Contractor providing the Services as set forth in this SOW,
Stryker agrees to pay Contractor on a FIRM FIXED PRICE basis as set forth below (the
“Project Charges”):
MILESTONE* MILESTONE FEE USD MILESTONE COMPLETION
DUE DATE
Completion of the project as
described in this SOW $249,565.87 April 26, 2024
Total NOT TO EXCEED
Project Charges $249,565.87 --------
Travel Expenses – (NTE Budget) $0 .00 --------
TOTAL $249,565.87 --------
* Milestones are more fully described in Exhibit A to this SOW.
b. Travel Expenses. All travel expenses must be consistent with the Travel Expense and
Reimbursement Policy Exhibit and approved by Stryker in advance by writing.
c. Purchase Order, Payment Terms and Invoices. The Project Charges specified above shall
become due and payable in accordance with the terms of the Agreement. Invoices are to be
submitted through the Stryker supplier portal (i.e., Coupa) with attention to the Stryker
Project Manager designated below and must match the applicable purchase order.
d. No Other Charges. Except as expressly stated in this SOW, there are no additional fees,
charges or expenses incurred by Stryker in connection with this SOW. In no event will Stryker
pay Supplier for expenses or charges in excess of the total amount set forth in the table above.
e. Termination for Convenience. Stryker may terminate this SOW without penalty at any time
for any reason or no reason, upon 5 days prior written notice to Contractor unless the terms
of the MSA are conflicting and set forth an alternative agreement, in such case the terms of the
MSA will prevail.
Page 3
IN WITNESS WHEREOF, the Parties execute this SOW as of the SOW Effective Date. Each person who signs
this SOW represents that such person is fully authorized to sign the SOW on behalf of the applicable Party.
STRYKER CORPORATION WORLD WIDE TECHNOLOGY, LLC
By: By:
Name: Name:
Title: Title:
Date: Date:
Page 4
Exhibit A to SOW
1. Deliverables. The Deliverables include the following:
a. Project Plan. A “Project Plan” that provides a detailed description of the project, including
the project milestones, tasks, methods, procedures and timing of the steps Contractor shall
take to implement the Project Services and provide the Deliverables. Once approved, the
Project Plan may not be changed without Stryker’s prior written consent.
b. Reports. Reports, including the following status reports to be provided within the
timeframes set forth in the Project Plan:
i. Activities performed during the reporting period
ii. Activities planned for the next reporting period
iii. Hours summary
A. Hours originally estimated
B. Hours expended during this reporting period
C. Hours expended to date
D. Estimated hours remaining
iv. Problems, concerns and recommendation
v. Detailed Project Plan document attached (Stryker Project Plan.docx) with below
sections:
A. Project Plan timeline
B. Additional reports for each reporting period
C. Workstream 1 analysis example
c. Languages other than English.
i. N/A
d. Additional Deliverables
i. Gap Analysis of each CCM Control Domain
ii. Summary Report of all findings
iii. Future state recommendations
e. Project Plan: Deliverables and Timeline
A. Project Plan:
i. Timelines and Deliverables listed will be mutually agreed upon by Stryker and WWT
and defined in the project plan. If changes are desired, WWT will work with Stryker to
prioritize, articulate potential impacts to project and align on next steps.
ii. The project is planned to last eight (8) weeks, with weekly review and feedback
sessions to hand over deliverables, align on next steps, and tune deliverables in line
with Stryker feedback to the WWT team.
iii. In addition, there will be daily standup calls to review each workstream’s efforts and
identify blockers or areas where assistance is required.
iv. The project’s eight (8) reporting periods are defined below, with each period denoting
a week. Here, week is defined as any working week (Monday through Friday),
regardless of whether a holiday is observed or not.
a) Period 1: Team alignment and discovery of partner teams for WWT/Stryker and
Access, documents sharing, and discovery first steps (Report delivery period)
b) Period 2: Control domains 1-3 discovery and review
c) Period 3: Control domains 1-3 analysis and delivery (Report delivery period)
d) Period 4: Control domains 4-7 discovery and review
e) Period 5: Control domains 4-7 analysis and delivery (Report delivery period)
f) Period 6: Control domains 8-11 discovery and review
g) Period 7: Control domains 8-11 analysis and delivery (Report delivery period)
Page 5
h) Period 8: Gap analysis across workstreams and recommendation prioritization and
final report delivery and next phase prioritization (Report delivery period)
ii. For each period identified, workstreams will work in parallel with each delivering their
analyzed domains by end of week.
iii. This timeline is dependent on actual start date and control domains may be covered in a
different order than noted above to avoid duplicative discovery efforts, but each control
domains period will cover the identified quantity of domains.
B. Additional Reports:
i. For each reporting period identified above, WWT shall deliver the following reports (in
alignment with Stryker SOW Exhibit A documentation)
i. Activities performed during the reporting period
ii. Activities planned for the next reporting period
iii. Hours summary
1. Hours originally estimated
2. Hours expended during this reporting period
3. Hours expended to date
4. Estimated hours remaining
ii. Problems, concerns and recommendation
iii. Domain Analysis documentation: each control domain shall deliver a report at the
conclusion of their work containing the below information:
1. Currently deployed capabilities for each listed control
2. Coverage of control(s) and maturity assessment (as per capability maturity model)
3. Steps and prioritization for remediating any identified gaps
4. Recommendation for additional controls or areas of focus
C. Domain Analysis Documentation Example:
i. Below is a short exemplar deliverable for each control domain and its possible contents.
These reports are intended to summarize findings and highlight pertinent and
prioritized information. This example is meant to show the sort of information conveyed
for each control in each domain and does not represent the full depth, content, or
recommendations. It will be accompanied by a slide reviewing prioritized information
for each control and a spreadsheet containing all the findings.
ii. Exemplar for Cryptography, Encryption, & Key Management control domain:
i. Control title: Data Encryption
1. After review WWT found there is a control in place for encryption at-rest using
virtual disk storage encryption with disk sharding provided by the cloud services
provider.
2. This service offering is rated as Managed due to repeatable process, deployment
automation, and recovery capability.
3. There is a gap in encryption in-transit for data transmitted across the network.
To close this gap, implementation of public key infrastructure to provide
certificates for Transport Layer Security (TLS) encryption of traffic is
recommended.
4. WWT also recommends deploying field level encryption of sensitive data at rest
in data stores utilizing a hardware security module or similar solution.
Documentation of recommended security policies for enforcement and
mitigation to be included.
iii. At the conclusion of the project period, WWT shall deliver a summary report and
presentation to the Stryker project team containing the below information:
i. Summary of findings for each control domain
ii. Prioritized controls that may apply across control domains
iii. Recommendations for next steps and further collaboration with Stryker and WWT
teams
iv. CCM Domains in and out of scope:
Page 6
i. The below CCM domains are not included this effort and will not be reviewed or included
in any findings
Domain - CCM In Scope
Application and Interface Security Yes
Audit Assurance and Compliance Yes
Business Continuity Management and Op Resilience Yes
Change Control and Configuration Management Yes
Data Security and Information Lifecycle Management Yes
Data Center Security No
Encryption and Key Management Yes
Governance and Risk Management Yes
Human Resources Security No
Identity and Access Management Yes
Infrastructure and Virtualization Security Yes
Interoperability and Portability No
Mobile Security No
Security Incident Management, E-Discovery, and Cloud Forensics Yes
Supply Chain Management, Transparency, and Accountability No
Threat and Vulnerability Management Yes
Physical & Environmental Security No
D. Stryker Responsibilities
i. Stryker will have suitable technical staff as mutually agreed upon by both parties
available for the duration of the engagement as defined by the project schedule. The
Stryker staff will need to participate in and support the various tasks of the project as
required as defined by the project schedule or other tasks not directly stated, but have a
direct impact on completion of this project
ii. Stryker will on-board WWT employees based on identified need, including remote
access, as mutually agreed by both parties during the course of the project
iii. Stryker will be responsible for any project delays or costs caused by failure to deliver or
by delayed provision of information, systems, or feedback from Stryker or third party
vendors
iv. Stryker is responsible for the timely execution of Stryker change control processes. Any
change control process delays that impact the time and level of effort to deliver the
solution will incur a change order for the time difference
v. The services may include WWT advice and recommendations, but all decisions in
connection with the implementation of such advice and recommendations will be the
responsibility of, and made by, Stryker
vi. Stryker acknowledges that WWT may deliver the Services through a combination of
employees, contractors, and subcontractors working under WWT’s direction, at WWT’s
discretion
vii. Stryker acknowledges that all business days worked by WWT as part of this project will
be consecutive unless agreed to in advance by both Stryker and WWT
viii. Stryker acknowledges that WWT is not providing any warranty regarding, and is not
liable for, any third party or Stryker software, documentation, equipment, tools or other
products or materials, even if recommended by WWT
Page 7
ix. Notwithstanding any conflicting or contrary terms in the Agreement, including any
applicable order of precedence, Stryker understands that WWT personnel located
globally may perform the Services herein and, by its authorized signature, Stryker
expressly acknowledges and approves
x. Stryker is responsible for the safety conditions at Stryker sites. If WWT Personnel are
required to be onsite during this engagement, the parties are proceeding under the
assumption that there are no onsite safety hazards. Stryker is not required to complete
a WWT Customer Safety Assessment Questionnaire (“Safety Questionnaire”). Upon
arrival at each site, WWT Personnel will perform a brief visual inspection for onsite
safety hazards. If WWT Personnel identifies any onsite safety hazard(s), then Stryker will
complete a Safety Questionnaire, available at https://wwt.com/csq, for each site or for
each group of sites with reasonably similar risks. A Change Order will address the onsite
hazards, personnel safety measures, and any additional requirements
xi. Stryker acknowledges that if at any time, the United States Government or its duly
appointed representatives issues a safety, terrorism, tariff, or other legally binding
statement that impacts WWT’s ability to transact business in the affected country, WWT
reserves the right the defer or exclude scope obligations for the countries impacted.
WWT will reduce the cost commensurate with the reduced scope
E. Contractor Responsibilities
xii. WWT tasks in this SOW will be completed during normal business hours between 8:00
a.m. and 5:00 p.m. project site local time, Monday through Friday, excluding WWT-
observed holidays, unless otherwise negotiated and noted in this SOW
xiii. WWT shall rely upon any standard operating procedures or practices of Stryker and any
direction, or regulatory or other guidance provided by Stryker as agreed to during the
project initiation
2. Service Levels.
a. General. Contractor shall perform the Services in accordance with the Agreement and this
SOW, including the below SLAs and shall immediately notify Stryker when Contractor fails, or
anticipates a failure of, any Service Level.
SERVICE LEVEL* MEASUREMENT SLA CREDIT AMOUNT
Timely Deliverables Meets the deliverable date set forth in
the approved project plan.
5% of fees of the impacted
milestone
b. Root Cause Analysis. If Contractor fails to meet a Service Level, Contractor shall (a) promptly
investigate and report on the root cause of the issue, (b) advise Stryker of the remedial efforts
underway with respect to the failure to meet the Service Level, (c) correct the issue and begin
meeting the Service Level and (d) take appropriate preventive measures so that the issue does
not reoccur.
c. Service Level Credits. If Contractor fails to meet a Service Level, Stryker shall receive a
monetary credit against the prices set forth in this SOW (“Service Level Credits”). For clarity,
Service Level Credits are a reduction in price to reflect the reduced value of the Services and
are not liquidated damages for Contractor’s failure to meet a Service Level. Repeated failure
to meet a Service Level in a 6-month period shall be deemed a material breach.
d. Continuous Improvement Reviews. Contractor shall, on a continuous basis, (a) as part of its
quality management process, identify ways to improve the Service Levels and (b) identify and
apply proven techniques and tools that would benefit Stryker either operationally or
Page 8
financially, and shall submit to Stryker for review and approval. In addition, Contractor shall
implement the annual Service Level improvements in accordance with this SOW.
3. Service Locations.
a. Contractor shall provide the Project Services at the following locations:
i. Remote
4. Key Personnel and Approved Subcontractors.
a. Key Personnel.
i. Contractor’s Project Manager will be the single point of contact for all communications
with Stryker’s Project Manager and will serve as the interface between Contractor and
all approved subcontractors participating in the project. Contractor’s Project Manager
shall be deemed Key Personnel (as defined in the Agreement).
ii. Additional Key Personnel are listed in Section – Project Team below.
iii. Contractor shall not replace or reassign any individual in a Key Personnel position during
the SOW Term, unless Stryker consents to such reassignment or replacement, or such
individual (1) voluntarily resigns from Contractor, (2) is dismissed by Contractor for
misconduct (e.g., fraud, drug abuse, theft), or (3) fails to perform his or her duties and
responsibilities pursuant to this SOW or the Agreement.
b. Approved Subcontractors.
i. None
5. Project Team.
Contractor’s
Project Team Role Description Resource Name Location
Project
Coordinator
Responsible for overseeing project
implementation, rollout, on-
going support and commercial
terms, executing required tasks
as per Project Plan.
TBD TBD
Principal Cloud
Security
Consultant
Responsible for aligning work
across workstreams and
efforts. Involved in preparation
of reports and analysis
deliverables.
Patrick Hodges Raleigh, NC
Principal Cloud
Security
Consultant
Responsible for meeting with
Stryker teams, review of
documentation, and analysis of
results in alignment with
reporting and documentation
plans.
TBD TBD
Senior Cloud
Security
Consultant
Responsible for meeting with
Stryker teams, review of
documentation, and analysis of
results in alignment with
reporting and documentation
plans.
TBD TBD
Management
Consultant
Accountable for assisting project
manager and other consultants
in ensuring teams communicate
and plan effectively
TBD TBD
Page 9
6. Technology.
a. Technology to be provided by Stryker:
i. Access to Stryker internal documentation on cloud security products, processes,
policies, and platforms (read only is preferred for least privilege consideration).
ii. Access to Stryker communication platforms for internal communication.
iii. Access to Stryker internal document sharing platform for sharing of information and
documents.
b. Technology to be provided by Contractor:
i. Usage of X-Analytics included as tool for analysis of information.
7. Post Implementation Review. A post implementation review will take place and involve both
Stryker and Contractor. The post implementation review will take place within 30 days of the project
completion to review and resolve any outstanding issues, decide on future plans for enhancements
and sign off on implementation of Project Services that remain outstanding.

----

Now, my only task that remains is to come up with good, overarching recommendations for the Stryker company - Can you give me 7 such, well thought out, for presentation to their c-suite, recommendations to put into a power point slide? Please do not be generic - be specific to the content above that has been provided. You can be higher level for the initial and then substantiate with specifics with additional details for each. 
