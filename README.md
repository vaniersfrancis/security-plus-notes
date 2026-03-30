# Security+ Notes
## SY0-701 Study Notes and Learning Progress

---

## Progress
- Started: March 26, 2026
- Last Updated: March 28, 2026
- Current Focus: Security Controls, CIA Triad

### Control categories 
- Technical =  firewalls, anti-virus
- Managerial = Security policies, day to day processes
- Operational = Security guards, awareness programs
- Physical = limit physical access (badge readers, fences. locks)

### Control Types
- Preventive = blocks attacks (firewall rules) 
- Deterrent = does not directly prevent access, more of a "WARNING DO NOT ENTER"
- Detective = identifies and logs (may not prevent access) like a motion detector thatll alert you
- Corrective = after detection you can apply a control (backup restore,create policies, law enforcement)
- Compensating = temporary fix until you have perm resolve for incident (firewall to prevent vulnerability,power generator)
- Directive = instructs or guides behavior (policies, procedures, training)


## CIA Triad (AIC) - Fundamentals of security
- C - Confidentiality = prevents unauthorized access to data (encryption, access control, MFA)
- I - Integrity = ensures data is not modified without detection (hashing, digital signatures, certificates)
- A - Availability = ensures systems and data are accessible when needed (redundancy, fault tolerance, patching)
- Hash = takes input data and produces a fixed-length scrambled output (used to verify integrity)
- Non-repudiation = ensures someone cannot deny performing an action (e.g., digital signatures)

- ## Gap Analysis -Comparing current security state to desired state "where we are vs where we would like to be"
- helps identify missing security controls so organizations can reduce risk and improve their security posture.”

## Zero Trust 
Policy enforcement point (PEP) "The gatekeeper" all traffic in network must pass through so we decide to allow/deny 
-gathers all info and provides it to Policy Decision Point
Policy decision point (PDP) -Examines authentication and makes the decision to allow on the network
Policy Engine - looks at all request and compares to pre-policy and other sourcesthen grant/deny/revokes
Policy Admin- takes the engines decision and provides it to PEP

## Physical Security 
-channel ppl through a specific access point, keeps out other things
Access control vestibules - a room you pass through to access the whole building 
-CCTV (Closed circuit television) video surveillance 
