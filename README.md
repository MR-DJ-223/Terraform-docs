# Terraform-docs
# MY PHONE
--------------------What is terraform Associate---------------
# P:-   The Hashicrop Terraform Associate is speciality certification in terraform. An infrastructure as code (IAC)
	tool that is declarative and cloud agnostic.

 P:- Consider the terraform Associate if you 
	-* prefer a DevOps enginner Role
	* Automating infrastructure or writting scenario
	* Working with multiple cloud providers
	* Enjoy designing and iterating to end to end cloud infrastructure

P:- Terraform is the 3rd most cloud skill in demand for DevOps Role(AWS->Azure->Terraform->k8)

Note : - Terraform easy to learn , But hard to master.

-------------------*************************-------------------------

Exam Over View:-

1. Understand infrastructure as a code(IAC) concepts
2. Understand Terraform purpose vs other IAC's
3. Understand Terraform Basic's 
4. Use the Terraform CLI(Outside of core work flow)
5. Interact with terraform modules
6. navigate terraform work flow
7. Implement and maintain state
8. Read, generate, and modify configuration
9. Understand terraform cloud and enterprise capabilities

To pass this exam, we have to get 700/1000 score 
total 57 questions in examination, you can afford to get 17 questions wrong
ans Type :-
	* multiple choice
	* multiple select
	* fill blanks (one word ex: tarraform.tfstate)
Before prepare Exam check Exam version (currently 3.0)

Popular IAC Tools:-

Declarative:-
 * What you see what you get, Expliclt
 * More verbase , but zore chance of mis-configuration
 * Use's scrinting languages EX: JSON,YAML,XML
 * ARM templates :- Supports only Azure
 * Azure Blueprint:- supports only Azure management ralative services
 * Cloud Formation:- Only AWS
 * Cloud deployment manager :- supports only google cloud
 * terraform :- Supports many cloud services providers (CSP's) & cloud services

Imperative :-
 * You say what you want, & the rest is filled in implicit
 * Less verbose , you cloud end up with mis-configuration
 * Use's programming language EX: python, Ruby, javascript
 * AWS cloud development kit(CDK)
   * only AWS
   * Many build in template for opinionated better purpose
 * Pulumi :- supports AWS,Azure,GCP,K8)

Declarative + :-
 * Terraform is declarative but the terraform language features imperative-like functionality
 
 -------------declarative-------------------------------------------------Imperative-----------
 * YAML,JSON,XML                        * HCL-ish(Terraform)       * Ruby, python , javascript, etc
 * limited or no support for            * supports		   * Imperative features is the utility of the  
    imperative-like features	        * Loops(for each)            entire feature supports the ...
 * In some cases yoou can add behaviour * Dynamic blocks
   by extending the bule flow           * locals
   ex: cloudformation macro             * complex data, structure
					* maps, collections

P:- What is Infrastructure life cycle.
 * A number of clearly defind & distint revoke phases whick are used by DevOps enginners to
   Plan->design->build->test->deliver->maintain->retire cloud infrastructure
Ex:
 What is DAY 1 , Day 2, and Day 3
Day 0-2 : is a simplified way ro describe phases 
 * Day 0 : plan and design
 * Day 1 : Develop & Iterate
 * Day 2 : Go live & maintainces

P:- How does IAC enhance the infrastructure life cycle
 * Reliability :-
 	* IAC makes changes idempotent, consistant, repeatable,&predictable
Note : Idempotent-- No matter how many times you run IAC , you will always end up with the same state that is expected
 * manageability :
	* enable mutation via core
	* revised with minimal changes
 * sensibility:
	* Avoid financial & reputational losses to ever loss of life when considering government & military department on infrastructure.

Non Idempotent:-
 * When idempotent my IAC configuration file it work provision & launch 2 VM's
 * when i update my IAC & deploy again, when i end up with 2 vm's with a total 4 VM's
Idempotent :-
 * When i deploy my IAC configurations file it will provision  & launch 2 VM's
 * When i update my IAC & deploy Again, it will update the VM's if changed by modification or deleting & creating the VM's

Privisioning   vs deployment    vs Orchestration

Provisioning :- To prepare  a server with system's data & safe while make it ready for H/W operation using configuration management
 tools like puppet, ansible , cheif, bash, scripts. powershell , or cloud -init , you can provision a server
Development :- Development is the act of delivering a version of your applications to run a provision server,
 Development cloud be performed via AWS, code pipeline, Hornes, jenkins, github, ACt.. cercleCI
Orchestration :- Orchestration is the act of coordinating multiple syatems or services
 * Orchestration is a common term when working with microservices caontainers & kubernates
 * Orchestration cloud be kubernates , salt, falut
configuration Drift : 
 * canfiguration drift is when provisioned infrastructure has an unexpected configuration changes due to
    * team mumber manually adjecting config options
    * malicious actosrs
    * side affects from API's,SDK,CLI
# hkjasdf;ka;skdf
- line
- 
