# 🌱 Blockchain-based Cocoa Supply Chain Monitoring

Welcome to a transparent and ethical way to monitor cocoa supply chains on the blockchain! This project uses the Stacks blockchain and Clarity smart contracts to track cocoa from farm to consumer, ensuring compliance with child labor prevention standards through immutable records, certifications, and audits.

## ✨ Features

🔍 Full traceability of cocoa batches from harvest to distribution  
🚫 Automated checks for child labor compliance using verified audits  
📝 Immutable registration of farms, workers, and supply chain events  
✅ Certification issuance for ethical sourcing  
💰 Incentive tokens for compliant participants  
⚖️ Dispute resolution for reported violations  
📊 Real-time reporting and verification tools  
🛡️ Prevention of duplicate or fraudulent entries  

## 🛠 How It Works

This project involves 8 smart contracts written in Clarity to handle different aspects of the supply chain monitoring. Here's a high-level overview:

### Core Smart Contracts
1. **UserRegistry.clar**: Registers participants (farmers, auditors, processors, etc.) with verified identities and roles.  
2. **FarmRegistry.clar**: Records farm details, including worker lists and initial compliance declarations.  
3. **HarvestTracking.clar**: Logs cocoa harvests with timestamps, quantities, and worker involvement proofs.  
4. **AuditSubmission.clar**: Allows certified auditors to submit on-site inspection reports, flagging any child labor issues.  
5. **CertificationIssuer.clar**: Issues digital certificates for compliant batches based on audits and tracking data.  
6. **TransportAndProcessing.clar**: Tracks movement and processing stages, ensuring chain-of-custody integrity.  
7. **ComplianceEnforcer.clar**: Automates rules to detect and flag non-compliance, integrating with audits.  
8. **IncentiveToken.clar**: Mints and distributes tokens to reward ethical practices, with staking for long-term compliance.

**For Farmers and Producers**  
- Register your farm and workers via UserRegistry and FarmRegistry.  
- Record a harvest event with details (e.g., batch ID, date, workers) using HarvestTracking.  
- Submit for audit through AuditSubmission—pass to earn a certificate from CertificationIssuer.  
- Track shipments and processing with TransportAndProcessing to maintain the chain.  

Boom! Your cocoa batch is now traceable and certified as child-labor-free.

**For Auditors and Regulators**  
- Verify your role in UserRegistry.  
- Conduct inspections and upload reports to AuditSubmission.  
- Use ComplianceEnforcer to enforce rules and flag issues automatically.  
- Resolve disputes via built-in mechanisms in ComplianceEnforcer.  

**For Consumers and Buyers**  
- Query any batch ID to view full traceability using HarvestTracking and TransportAndProcessing.  
- Verify certifications instantly with CertificationIssuer.  
- Check compliance reports from AuditSubmission for peace of mind.  

That's it! A decentralized system promoting ethical cocoa production while solving real-world child labor issues through blockchain transparency.