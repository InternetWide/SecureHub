# SecureHub: Network security toolkit

> *SecureHub is a collection of open source projects from the ARPA2 project.
> It is a desktop frontend for provisioned network security.*

## Tooling included

  * Graphical interfaces for identity selection and sign-on
  * Support for optional PKCS #11 hardware tokens
  * Web client proxy to aid security  (FUTURE OPTION: aid privacy)
  * Email client proxy (IMAP, POP3, SMTP)  (UNDER DEVELOPMENT)
  * Chat client proxy (XMPP)  (UNDER DEVELOPMENT)
  * Password agreement over public email or irc (UNDER DEVELOPMENT)

## Software Sub-projects

SecureHub consists of the following major sub-projects:

  * **TLS Pool** as an independent TLS implementation that can easily be
    integrated with any application that requires TLS security.
  * **SteamWorks** is a provisioning platform; its use in SecureHub is for
    provisioned security settings, such as trust anchors and pinning
    information.  Future editions are also likely to integrate with
    central identity provisioning from the InternetWide next-phase
    project IdentityHub.
  * **Kerberos** integration is used within the TLS Pool; it serves to
    provide your identity to a site or service using this central
    authentication infrastructure.  (UNDER DEVELOPMENT)

## Getting started

QUICKSTART.sh (UNDER DEVELOPMENT)
