# Resume: John A. Sexton
<table>

<tr>
<td>Name:</td>
<td>John A. Sexton</td>
</tr>

<tr>
<td>Title:</td>
<td>Staff Software Engineer</td>
</tr>

<tr>
<td>Focus areas:</td>
<td>Platform SRE | DevOps Architecture | Cloud Architecture | CICD | Digital Transformation | Public Speaking </td>
</tr>

<tr>
<td>Profile:</td>
<td><a href="https://www.linkedin.com/in/john-sexton-8b943a18/">LinkedIn</a></td>
</tr>

<tr>
<td>LastUpdate:</td>
<td>April 2020</td>
</tr>

</table>

### SUMMARY
> Staff Software Engineer specializing in Digital Transformation, Site Reliability Engineering (SRE) and DevOps Architectures; Establishing: configuration management, Infrastructure as Code (IaC), source control management (SCM), branching and merging design patterns, observability, audit, test automation, and security compliance practices, all in large enterprise, mission critical and core revenue environments; Servicing geographically dispersed systems and teams, utilizing Agile methodologies like Kanban, Scrum, Lean & Kata; Leveraging best in class industry standard tooling as defined by CNCF and practices as quantified by industry white-papers such as the annual DORA State of DevOps Report; Driving improved: Time to Value (T2V), quality, efficiency and compliance, while reducing manual efforts required via API driven Enterprise design patterns

### PROFESSIONAL EXPERIENCE <br>
**Macys Technology, Retail Order Management, Duluth GA 2016-present** <br>
**Staff Software Engineer** <br>
_Previous Titles: "Staff DevOps Engineer", "Lead DevOps Engineer, D2C DevOps Architecture" and "Systems Specialist, Development, D2C DevOps Architecture"_
* Led large-scale Digital Transformation effort, migrating 100+ Java services from CI, to CICD, accelerating deployment cadence from every 2 months to daily, radically reducing deployment team effort required to implement production changes. Implemented following advancements:
  * From SVN to Git - Co-led small team that rolled out GitLab Enterprise to entire Macys Technology footprint
  * From branching anti-pattern to modern trunk based development pattern
  * From legacy SOA, SOAP, XML services to true containerized, 12-factor REST API microservices
  * From very basic CI to advanced CI, with compliance gates & modern declarative CD via Spinnaker & Helm
  * From 1000+ handcrafted VMs to 100% defined as Ruby code in Chef Cookbooks
  * From no containers on-prem to a cloud native, container orchestration practice via Docker, Helm, Kubernetes & GKE
  * From no observability to whitebox/blackbox monitoring via Stackdriver, Prometheus & Grafana
  * From no IaC practice, to Terraform provisioned Kubernetes, Spanner, Datastore, PubSub, CloudTasks, Dataflow self-service
  * From 100% human monitoring to automated Prometheus alert-manager alerts firing PagerDuty incident response incidents
  * From 100% on-prem DataCenter to all lower lifecycle environments in GCE, to all greenfield projects in GKE via Docker / Kubernetes
* Led other key engineering initiatives:
  * Converted all freestyle Jenkins jobs to declarative groovy DSL pipeline as code, reducing manual touch & enabling self-provisioning
  * Migrated team from Test Driven Development TDD to Behavior Driven Development BDD paradigm
  * Engineered platforms from fixed property files to dynamic feature toggle practices
  * Provided multiple key:value stores for both Legacy and Cloud Native applications using Zookeeper & Kubernetes-configmaps
  * Integrated Atlassian FishEye and Jira with GitLab Enterprise to establish full traceability and visibility from story to feature branch to commit
  * implemented and iteratively improved Configuration Management practice using Opscode Chef and Django API translation layer to achieve multi-cloud provisioning while writing against a single internal API framework at VM level
* DevOps Thought Leadership efforts:
  * Continuously evaluated/re-evaluated current level of DevOps Maturity against an objective DevOps Maturity Model
  * Developed long term Platform Engineering road maps and quantified results via Value Stream Mapping & Platform metrics
  * Collaborated with Agile Coach to reorganize single function team silos into cross-functional "Macys Delivery Teams"
  * Established inner-sourcing Enterprise code sharing model using GitLab Enterprise on company intranet
  * Co-chaired DevOps Core Council, planning activities for the DevOps community of practice to socialize DevOps best-practices throughout Macys Technology
* KeyNotes and Training:
  * DevOpsATL Nov 2016: _Building High Trust DevOps Cultures at Enterprise Scale_
  * Macys Boardroom Tech Talk Aug 2017: _Behavior Driven Development_
  * Co-created “Macys First DevOps Dojo” with DevOps Council  
  * Created Curated DevOps Content playlists on Skillport LMS portal

**Verizon, Enterprise Professional Services BI, Alpharetta, GA 2013 – 2015** <br>
**Lead Systems Architect & Senior Systems Administrator (MTS-IV)** <br>
_Verizon, Tampa, FL 2000-2012_ <br>
_Previous Titles: "Senior Systems Architect & Senior Systems Administrator (MTS-III)", "Senior Systems Administrator (MTS-II)"", "Systems Administrator (MTS-I)"_
* Led large-scale Digital Transformation effort, migrating 120+ Java services from CI only, to Continuous Deployment design patterns, accelerating deployment cadence from every 2 months during late night change windows, to multiple times a day during prime business hours
* Reorganized Planning, Development, Testing and Ops silos into smaller cross-functional "Verizon Pods" inspired by "Amazon 2 Pizza Teams" and "Spotify Squads", resulting in right sizing teams to initiatives, increased crossing and embedding, reducing blame, which improved collaboration and affinity, which in turn increased development velocity
* Developed Jenkins continuous integration (CI), continuous delivery and continuous deployment (CD) automations, integrating business processes, SDLC governance, disaster recovery, test automation, enterprise monitoring, and configuration management for WAN scope applications used by Verizon SalesForce SFDC Team, servicing Enterprise Customers
* Implemented Blue | Green methodology using geographically distributed cluster switching, at Netscaler GSLB load balancer level, resulting in zero downtime deployments
* Led first team at Verizon effort to automate Change Management compliance via API calls in CD Jenkins automations
* Virtualized Web services and API interface tests with CA-LISA / CA-DevTest to decouple external team integration partner dependencies in lower lifecycle environments, eliminating issues where partner teams might cause delays in development velocity
* Implemented automated continuous testing in all lifecycles, to meet continuous delivery goals
* Leveraged Sonatype Nexus as repository for build artifacts to ensure code reproducibility
* Configured System instrumentation testing, via Jenkins API calls to CA-APM, to perform deployment readiness checks, that gated automated deployments off health checks, to avoid deploying to an overburdened or unavailable host
* Automated System under test (SuT) performance stress test loads, with HP LoadRunner API calls from Jenkins
* Compared Pivotal Cloud Foundry and RedHat Openshift PaaS offerings in POC, implemented PCF, implemented Openstack Cloud in on-prem data centers, performing 'cf push' deploys to on-prem Openstack VMs, and public cloud Amazon Web Services AWS EC2 in Q4 2015
* Designed and implemented BI data warehouse on Oracle OBIA for Verizon enterprise customer facing sales portal, performing system architecture including scaling, storage, system resources, security, high availability (HA) clustering, and configuration management tasks

### CORE COMPETENCIES
* **Cloud Platforms:** Google Cloud Platform (GCP) <br>
* **GCP Tooling:** GKE, GCE, GCS, PubSub, Spanner, Datastore, Dataflow, GCLB, CloudArmor, IaP, IAM, VPC, gcloudSDK <br>
* **Containerization:** Kubernetes, AppEngine, Docker, Dockerhub, gcr.io <br>
* **Observability:** Prometheus, Grafana, Stackdriver <br>
* **Ingress:** Nginx <br>
* **CI/CD:** Spinnaker, Helm, Jenkins-X, Jenkins, Maven, Artifactory, Sonarqube, Checkmarx <br>
* **Infrastructure as Code (IaC):** Terraform <br>
* **Configuration Management:** Docker, Chef <br>
* **Source Control Management SCM:** git-scm.com, GitLab Enterprise, GitLab, GitHub, Subversion (SVN) <br>
* **Languages:** Groovy, Bash, Python, SQL, REST, Ruby, Java <br>
* **Markup/Markdown:** yaml, json, markdown, html, xml <br>
* **OS:** Linux (Alpine, CoreOS, CentOS, Ubuntu, RedHat Enterprise Linux RHEL) <br>
* **Planning:** Jira <br>

### PROFESSIONAL AWARDS
##### Macys
* Earned two Macys "Make Magic Awards" which honor about 200 out of 4000 IT employees
  * Macys Make Magic Award for DevOps Thought Leadership in 2016
  * Macys Make Magic Award for CA-Endevor to Compuware ISPW scm migration in 2018

##### Verizon
* Earned 5 CIO recognitions at Verizon in the last 2 years in a company of over 16,000 IT employees
  * Team of 5 awarded 1st place in annual "Verizon DevOps Challenge", judged by internal DevOps Council, and external cloud industry judges from Microsoft, IBM, Mirantis, and Pivotal
  * Led the team awarded 3rd place in a CA-LISA Service Virtualization Hack-a-thon by virtualizing 120+ services in a single day
  * Performed regulatory compliance officer role for multiple large application portfolios - security scan audits, remediation, PCI/SOX, and GSAM compliance certification
  * Migrated a legacy revenue application & decommissioned legacy systems to remediate security vulnerabilities
  * Remediated 53 critical security vulnerabilities in 30 days, clearing a poorly maintained, inherited, PCI/SOX-compliant application suite

### PROFESSIONAL DEVELOPMENT TRAINING
<table>

<tr>
<td>Google Cloud</td>
<td>Sun Java Core</td>
<td>Sun Java / SpringBoot</td>
</tr>

<tr>
<td>RedHat Openshift</td>
<td>Opscode Chef Foundations</td>
<td>Mirantis Openstack</td>
</tr>

<tr>
<td>Pivotal Cloud Foundry</td>
<td>Mirantis Agile</td>
<td>Lean Six Sigma</td>
</tr>

</table>

### RECENT CONFERENCES ATTENDED
<table>

<tr>
<td>Google Cloud Next '18</td>
<td>DevOps Days 2019</td>
<td>Jenkins-X 2019</td>
</tr>

<tr>
<td>Cloudbees Days 2017</td>
<td>Nginx Conf 2018</td>
<td>DevOps Tech Summit 2018</td>
</tr>

</table>
