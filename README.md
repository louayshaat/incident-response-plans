# incident-response-plans

## AWS Incident Response Runbook Samples

These run-books are created to be used as templates only. They should be customized by administrators working with AWS to suit their particular needs, risks, available tools and work processes. These guides are not official AWS documentation and are provided as-is to customers using AWS products and who are looking to improve their incident response capability.

The run-books included below cover several common scenarios faced by AWS customers. They outline steps based on the [NIST Computer Security Incident Handling Guide](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-61r2.pdf) (Special Publication 800-61 Revision 2) that can be used to:

* Gather evidence
* Contain and then eradicate the incident
* recover from the incident
* Conduct post-incident activities, including post-mortem and feedback processes

Interested readers may also find the AWS Security Incident Response Guide (first published in June 2019) a useful guide as an overview of how the below steps were created.

Each runbook corresponds to a unique incident and there are 5 parts to handling each incident type, following the NIST guidelines referenced above. Each part corresponds to an action in that NIST document.

It is not sufficient to customize these scenarios to the need of your customers, organization or applications. It is important that these runbook scenarios are tested (for example, in Game Days) prior to deployment to your knowledge management system and that all responders are familiar with the actions required to respond to an incident.

Note that some of the incident response steps noted in each scenario may incur costs in your AWS account(s) for services used in either preparing for, or responding to incidents. Customizing these scenarios and testing them will help you to determine if additional costs will be incurred. You can use AWS Cost Explorer and look at costs incurred over a particular time frame (such as when running Game Days) to establish what the possible impact might be.

## Sample run books

- [Web Application Dos/DDoS Attack](samples/DDoSAttack.md)
- [Unintended access to an S3 Bucket](samples/s3-unintendedaccess.md)
- [Credential Leakage/Compromise](samples/cred-leakage.md)
