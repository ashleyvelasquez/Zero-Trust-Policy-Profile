## Policy Engine (PE)
The policy engine is the decision-maker of the zero trust system. It acts like the brain evaluating all security signals and verifying things like the users identity,device security, and network location. The PE makes the final decision to allow or deny access.

## Policy Administrator (PA)
The policy adminstrator manages and applies the access policies. It acts like the rule setter because it takes the decison made from the PE and prepares the system to enforce the decision. 

## Policy Enforcement Point (PEP)
the policy enforcement point is the gatekeeper that enforces access decisions. It seets between the user and the protectd resource. If allowed, the PEP allows the connect, if denied, the PEP blocks access. 

## Zero Trust Principle: Verify Explicity
the verify explicity principle means that every user and device must be verified before access is given. FOr example, if an HR employee tries to access a database at the water treatment facility, the policy engine checks multiple security singals. It verifies the employees login credentials, confrims the device is secure and company approved, and checks that the user is connected to the secure company network. If verified succesfully, the policy engine allows access. This protects important information from unauthorized access. 

| Policy Requirement (Signal) | Condition to be Met by User | Action if Condition is Met |
|-----------------------------|-----------------------------|-----------------------------|
| User Identity | User must log in with valid HR employee credentials and multi-factor authentication (MFA) | Grant Access |
| Device Posture | User must be using a company-approved device with updated security patches and antivirus enabled | Grant Access |
| Network Context | User must be connected through the company’s secure network or approved VPN | Grant Access |

# Git Repository Metadata

Project: Lab 02 - Zero Trust Policy

Filename: ZT-Policy-Profile.md

Commit Message: Added Zero Trust Policy Profile for Lab 02 - https://github.com/ashleyvelasquez/Zero-Trust-Policy-Profile

Due Date: Feb 27, 2026

