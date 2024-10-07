```mermaid
sequenceDiagram
    Attacker->>+Firewall: Hello Firewall, give me access?
    Attacker->>+Firewall: Firewall, Trust this link?
    Firewall-->>-Attacker: prove your authentication
    Firewall-->>-Attacker: your authentication failed! Access denied
