# 🏢 Active Directory Security Lab

Practical laboratory for studying **Active Directory security** from enumeration to domain compromise and detection.

## Focus Areas

- Active Directory fundamentals
- LDAP / SMB / RPC enumeration
- Authentication: Kerberos, NTLM and LDAP
- Credential access
- Privilege escalation
- Lateral movement
- Persistence
- Domain compromise
- Detection & mitigation

## Structure

```text
active-directory-security-lab/
├── 01-fundamentals/
├── 02-enumeration/
│   ├── ldap/
│   ├── smb/
│   ├── rpc/
│   └── bloodhound/
├── 03-authentication/
│   ├── kerberos/
│   ├── ntlm/
│   └── ldap/
├── 04-credential-access/
│   ├── kerberoasting/
│   ├── asrep-roasting/
│   └── credential-dumping/
├── 05-privilege-escalation/
├── 06-lateral-movement/
├── 07-persistence/
├── 08-domain-compromise/
└── 09-detection-and-mitigation/
```

## Lab Methodology

Each technique should document:

**Objective → Concept → Lab → Enumeration → Attack → Validation → Mitigation → Detection → Lessons Learned**

> ⚠️ All experiments are performed only in authorized educational or laboratory environments.
