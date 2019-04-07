# udacity-blockchain-architecture
Architect a Blockchain Supply Chain Solution for Certification Schemes - Part A

## Overview
This architecture is for a decentralized approach for certifaction schemes and certification issuance and verification.
Any party can become a Certifier (e.g. Coffee Barista Training group, Vehicle Testing)

## Example Use Cases
| Authority                         | Certifier                   | Recipient     | Inspector         |
|-----------------------------------|-----------------------------|---------------|-------------------|
|Specialty Coffee Association       |London School Of Coffee      |Trainee Barista| Starbucks Manager |
|Driver and Vehicle Licensing Agency|Pymans Garage                |Car Owner      | Insurance company |
|Oracle Corporation                 |Oracle Certified Professional|Database Admin | Deutsche Bank HR  |

A Certifier would probably have a single Authority per Certificate.  Many certificates can be awarded from a scheme and potentially many "Inspectors" could request access to view one or more awarded certificates of a recipient.
