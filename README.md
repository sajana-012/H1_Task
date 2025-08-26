# Threat Modeling

Braiterman et al 2020: Threat Modeling Manifesto

Threat modeling is analyzing representations of a system to highlight concerns about security and privacy characteristics.

## Security Hygiene

Basics practices everyone should follow:

1. Use strong, unique passwords and also multi-factor authentication
2. Keep systems and apps updated
3. Back up important data
4. Encrypt sensitive data
5. Limit access: only give rights people actually need
6. Educate staff/users on security basics

### Threat Model for Imaginary Company: HealthTrack (Fitness and Health Tracking App)

1. What are we working on?

- Assets: Customer health data, payment info, servers, mobile app.
   
- Business goal: Provide service safely, keep customers trust.
   
- Customer interactions: Mobile app, website, email.

2. What can go wrong?

- Spoofing: Attacker logs in as user.
   
- Tampering: Data changed (fake health status).
   
- Information disclosure: Health data leaked.
   
- Denial of Service: App unavailable.
   
- Prioritized risk: Data leak (high impact).

3. What are we going to do about it?

- Reduce attack surface.
   
- Strong login with MFA.
   
- Encrypt health data.
   
- Backups and insurance for worst cases.

4. Did we do a good enough job?

- Regular audits and penetration tests.
   
- Continuous monitoring.
   
- Update threat model after changes.

#### Sources 

Karvinen 2024: Information Security Course, https://terokarvinen.com/information-security/

Braiterman et al 2020: Threat Modeling Manifesto

Shostack 2022: World's Shortest Threat Modeling Course

OWASP CheatSheets Series Team 2021: Threat Modeling Cheat Sheet

Darknet Diaries Podcast 
