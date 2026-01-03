
 <div id='top'></div>

# CyberOwl

 > Last Updated 03/01/2026 21:24:57 UTC
 
 A daily updated summary of the most frequent types of security incidents currently being reported from different sources.
 
 For more information, please check out the documentation [here](./docs/README.md).
 
 ---
 |CyberOwl Sources|Description|
 |---|---|
 |[US-CERT](#us-cert-arrow_heading_up)|United States Computer Emergency and Readiness Team.|
 |[MA-CERT](#ma-cert-arrow_heading_up)|Moroccan Computer Emergency Response Team.|
 |[CERT-FR](#cert-fr-arrow_heading_up)|The French national government Computer Security Incident Response Team.|
 |[IBM X-Force Exchange](#ibmcloud-arrow_heading_up)|A cloud-based threat intelligence platform that allows to consume, share and act on threat intelligence.|
 |[ZeroDayInitiative](#zerodayinitiative-arrow_heading_up)|An international software vulnerability initiative that was started in 2005 by TippingPoint.|
 |[OBS Vigilance](#obs-vigilance-arrow_heading_up)|Vigilance is an initiative created by OBS (Orange Business Services) since 1999 to watch public vulnerabilities and then offer security fixes, a database and tools to remediate them.|
 |[VulDB](#vuldb-arrow_heading_up)|Number one vulnerability database documenting and explaining security vulnerabilities, threats, and exploits since 1970.|
 
 > Suggest a source by opening an [issue](https://github.com/karimhabush/cyberowl/issues)! :raised_hands:
 ---

## US-CERT [:arrow_heading_up:](#cyberowl)

 |Title|Description|Date|
 |---|---|---|
 
 ---

## CERT-FR [:arrow_heading_up:](#cyberowl)

 |Title|Description|Date|
 |---|---|---|
 |[](https://www.cert.ssi.gouv.fr/avis/CERTFR-2026-AVI-0002/)|De multiples vulnérabilités ont été découvertes dans les produits IBM. Certaines d'entre elles permettent à un attaquant de provoquer un déni de service à distance, une atteinte à la confidentialité des données et une atteinte à l'intégrité des données.|Publié le 02 janvier 2026|
 |[](https://www.cert.ssi.gouv.fr/avis/CERTFR-2026-AVI-0001/)|De multiples vulnérabilités ont été découvertes dans le noyau Linux de SUSE. Elles permettent à un attaquant de provoquer une atteinte à l'intégrité des données et un déni de service.|Publié le 02 janvier 2026|
 |[](https://www.cert.ssi.gouv.fr/avis/CERTFR-2025-AVI-1142/)|De multiples vulnérabilités ont été découvertes dans Moxa NPort. Certaines d'entre elles permettent à un attaquant de provoquer une élévation de privilèges, un déni de service à distance et une atteinte à l'intégrité des données.|Publié le 31 décembre 2025|
 |[](https://www.cert.ssi.gouv.fr/avis/CERTFR-2025-AVI-1141/)|De multiples vulnérabilités ont été découvertes dans le noyau Linux de Red Hat. Elles permettent à un attaquant de provoquer un contournement de la politique de sécurité, un déni de service et un problème de sécurité non spécifié par l'éditeur.|Publié le 26 décembre 2025|
 |[](https://www.cert.ssi.gouv.fr/avis/CERTFR-2025-AVI-1140/)|De multiples vulnérabilités ont été découvertes dans le noyau Linux de SUSE. Certaines d'entre elles permettent à un attaquant de provoquer une atteinte à la confidentialité des données, un contournement de la politique de sécurité et un déni de service.|Publié le 26 décembre 2025|
 |[](https://www.cert.ssi.gouv.fr/avis/CERTFR-2025-AVI-1139/)|De multiples vulnérabilités ont été découvertes dans le noyau Linux d'Ubuntu. Elles permettent à un attaquant de provoquer un problème de sécurité non spécifié par l'éditeur.|Publié le 26 décembre 2025|
 |[](https://www.cert.ssi.gouv.fr/avis/CERTFR-2025-AVI-1138/)|De multiples vulnérabilités ont été découvertes dans VMware Tanzu Platform. Elles permettent à un attaquant de provoquer un problème de sécurité non spécifié par l'éditeur.|Publié le 26 décembre 2025|
 |[](https://www.cert.ssi.gouv.fr/avis/CERTFR-2025-AVI-1137/)|De multiples vulnérabilités ont été découvertes dans les produits IBM. Certaines d'entre elles permettent à un attaquant de provoquer une exécution de code arbitraire à distance, un déni de service à distance et une atteinte à la confidentialité des données.|Publié le 26 décembre 2025|
 |[](https://www.cert.ssi.gouv.fr/avis/CERTFR-2025-AVI-1136/)|De multiples vulnérabilités ont été découvertes dans le noyau Linux de Debian LTS. Certaines d'entre elles permettent à un attaquant de provoquer une élévation de privilèges, une atteinte à la confidentialité des données et une atteinte à l'intégrité des données.|Publié le 19 décembre 2025|
 |[](https://www.cert.ssi.gouv.fr/avis/CERTFR-2025-AVI-1135/)|De multiples vulnérabilités ont été découvertes dans le noyau Linux d'Ubuntu. Certaines d'entre elles permettent à un attaquant de provoquer une exécution de code arbitraire, une atteinte à la confidentialité des données et une atteinte à l'intégrité des données.|Publié le 19 décembre 2025|
 
 ---

## OBS-Vigilance [:arrow_heading_up:](#cyberowl)

 |Title|Description|Date|
 |---|---|---|
 |[<a href="https://vigilance.fr/vulnerability/MongoDB-Server-out-of-bounds-memory-reading-via-Zlib-Compressed-Protocol-Headers-49179" class="noirorange"><b>MongoDB Server</b>: out-of-bounds memory reading via Zlib Compressed Protocol Headers</a>](https://vigilance.fr/vulnerability/MongoDB-Server-out-of-bounds-memory-reading-via-Zlib-Compressed-Protocol-Headers-49179)|An attacker can force a read at an invalid memory address of MongoDB Server, via Zlib Compressed Protocol Headers, in order to trigger a denial of service, or to obtain sensitive information...|Visit link for details|
 |[<a href="https://vigilance.fr/vulnerability/Elasticsearch-overload-via-Oversized-User-Settings-Data-49168" class="noirorange"><b>Elasticsearch</b>: overload via Oversized User Settings Data</a>](https://vigilance.fr/vulnerability/Elasticsearch-overload-via-Oversized-User-Settings-Data-49168)|An attacker can trigger an overload of Elasticsearch, via Oversized User Settings Data, in order to trigger a denial of service...|Visit link for details|
 |[<a href="https://vigilance.fr/vulnerability/Redis-buffer-overflow-via-XACKDEL-STREAMID-STATIC-VECTOR-LEN-48641" class="noirorange"><b>Redis</b>: buffer overflow via XACKDEL STREAMID_STATIC_<wbr>VECTOR_LEN</wbr></a>](https://vigilance.fr/vulnerability/Redis-buffer-overflow-via-XACKDEL-STREAMID-STATIC-VECTOR-LEN-48641)|An attacker can trigger a buffer overflow of Redis, via XACKDEL STREAMID_STATIC_|Visit link for details|
 |[<a href="https://vigilance.fr/vulnerability/QEMU-buffer-overflow-via-e1000-receive-iov-48640" class="noirorange"><b>QEMU</b>: buffer overflow via e1000_receive_iov()</a>](https://vigilance.fr/vulnerability/QEMU-buffer-overflow-via-e1000-receive-iov-48640)|An attacker, in a guest system, can trigger a buffer overflow of QEMU, via e1000_receive_iov(), in order to trigger a denial of service, and possibly to run code...|Visit link for details|
 |[<a href="https://vigilance.fr/vulnerability/Thunar-multiple-vulnerabilities-dated-03-11-2025-48638" class="noirorange"><b>Thunar</b>: multiple vulnerabilities dated 03/11/2025</a>](https://vigilance.fr/vulnerability/Thunar-multiple-vulnerabilities-dated-03-11-2025-48638)|An attacker can use several vulnerabilities of Thunar, dated 03/11/2025...|Visit link for details|
 |[<a href="https://vigilance.fr/vulnerability/Rust-astral-tokio-tar-file-read-write-via-PAX-Header-Desynchronization-48637" class="noirorange"><b>Rust astral-tokio-tar</b>: file read/write via PAX Header Desynchronization</a>](https://vigilance.fr/vulnerability/Rust-astral-tokio-tar-file-read-write-via-PAX-Header-Desynchronization-48637)|An attacker can bypass access restrictions of Rust astral-tokio-tar, via PAX Header Desynchronization, in order to read or alter files...|Visit link for details|
 |[<a href="https://vigilance.fr/vulnerability/ISC-Kea-denial-of-service-via-hostname-char-Option-Content-48636" class="noirorange"><b>ISC Kea</b>: denial of service via hostname-char Option Content</a>](https://vigilance.fr/vulnerability/ISC-Kea-denial-of-service-via-hostname-char-Option-Content-48636)|An attacker can cause a fatal error of ISC Kea, via hostname-char Option Content, in order to trigger a denial of service...|Visit link for details|
 |[<a href="https://vigilance.fr/vulnerability/IBM-i-privilege-escalation-via-SQL-Services-48635" class="noirorange"><b>IBM i</b>: privilege escalation via SQL Services</a>](https://vigilance.fr/vulnerability/IBM-i-privilege-escalation-via-SQL-Services-48635)|An attacker can bypass restrictions of IBM i, via SQL Services, in order to escalate his privileges...|Visit link for details|
 |[<a href="https://vigilance.fr/vulnerability/Rack-five-vulnerabilities-dated-03-11-2025-48633" class="noirorange"><b>Rack</b>: five vulnerabilities dated 03/11/2025</a>](https://vigilance.fr/vulnerability/Rack-five-vulnerabilities-dated-03-11-2025-48633)|An attacker can use several vulnerabilities of Rack, dated 03/11/2025...|Visit link for details|
 |[<a href="https://vigilance.fr/vulnerability/PHP-information-disclosure-via-getimagesize-49149" class="noirorange"><b>PHP</b>: information disclosure via getimagesize()</a>](https://vigilance.fr/vulnerability/PHP-information-disclosure-via-getimagesize-49149)|An attacker can bypass access restrictions to data of PHP, via getimagesize(), in order to read sensitive information...|Visit link for details|
 
 ---

## MA-CERT [:arrow_heading_up:](#cyberowl)

 |Title|Description|Date|
 |---|---|---|
 
 ---

## VulDB [:arrow_heading_up:](#cyberowl)

 |Title|Description|Date|
 |---|---|---|
 