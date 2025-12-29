## What is PCI DSS SAQ?
**PCI DSS SAQ** stands for Payment Card Industry Data Security Standard (Self-Assessment Questionnaire) - a set of security requirements designed to help organizations protect cardholder data. It is a self-assessment tool used by businesses that process, store, or transmit payment card information.
## What it’s used for
- To evaluate compliance with PCI DSS security standards
- To identify potential security risks in payment systems
- To confirm that cardholder data is handled securely
## Common SAQ types
There are different SAQ types depending on how payments are processed, for example:
- SAQ A – for fully outsourced payment processing
- SAQ A-EP – for e-commerce with some system involvement
- SAQ D – for businesses that store or process cardholder data
- SAQ B-IP has been developed to address requirements applicable to merchants who process cardholder data only via standalone, PTS-approved point-of-interaction (POI) devices with an IP connection to the payment processor
- SAQ C-VT merchants process cardholder data only via a virtual payment terminal and do not store cardholder data on any computer system
## An incident response plan
PCI DSS requires a documented plan for responding to a cardholder data breach or security incident. Key elements that need to be included in the plan:
- **Roles and responsibilities** (who does what during an incident)
- **Detection and reporting** (how staff report suspicious activity)
- **Communication** (internal and external notifications, including acquirer and PCI SSC if needed)
- **Testing** (annual review and test of the plan)
## ASV Scans
ASV scans are required for vendors that handle payment card data or are connected to systems that process payment card information.
> ASC scans are required only if the vendor’s systems are internet-facing and connected to the cardholder data environment.

SAQ TYPE      | ASV SCAN REQUIRED | REASON | 
------------- | ------------------| --------
SAQ A         | No                | Payment processing is fully outsourced, and systems do not handle or affect cardholder data.|
SAQ A-EP      | Yes               | E-commerce systems can impact the security of the payment process and are internet-facing.|
SAQ D         | Yes               | Systems store, process, or transmit cardholder data and are in full PCI DSS scope.|
SAQ B-IP      | Yes               | IP-connected payment terminals are internet-facing and require vulnerability scanning.|
SAQ C-VT      | No                | Payments are entered manually via a browser-based virtual terminal with no system storage of card data.|
