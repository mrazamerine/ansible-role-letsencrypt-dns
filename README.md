# Ansible role – LetsEncrypt-DNS

Ansible role for generating a LetsEncrypt SSL certificate using a DNS challenge and AWS Route 53.


## Variables

* **diffie\_hellman\_size** – Diffie-Hellman group bit size (int) [2048]

* **letsencrypt\_agreement** – LetsEncrypt agreement (string)

* **letsencrypt\_aws\_access\_key** – AWS access key for Route 53 (string)

* **letsencrypt\_aws\_secret\_key** – AWS secret key for Route 53 (string)

* **letsencrypt\_csr\_city** – Certificate signing request city (string)

* **letsencrypt\_csr\_country** – Certificate signing request country (string) [US]

* **letsencrypt\_csr\_department** – Certificate signing request department (string) [IT]

* **letsencrypt\_csr\_organization** – Certificate signing request organization (string)

* **letsencrypt\_csr\_state** – Certificate signing request state (string)

* **letsencrypt\_domain\_name** –  Domain name on certificate (string)

* **letsencrypt\_email** – Email for certificate reminders (string)

* **letsencrypt\_remaining\_days** – Days remaining renewal threshold (int) [15]

* **letsencrypt\_zone** – DNS zone of letsencrypt domain (string)
