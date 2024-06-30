
 <div id='top'></div>

# CyberOwl

 > Last Updated 30/06/2024 09:24:18 UTC
 
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
 |[](https://www.cert.ssi.gouv.fr/avis/CERTFR-2024-AVI-0529/)|De multiples vulnérabilités ont été découvertes dans les produits IBM. Certaines d'entre elles permettent à un attaquant de provoquer une exécution de code arbitraire à distance, une élévation de privilèges et un déni de service à distance.|Publié le 28 juin 2024|
 |[](https://www.cert.ssi.gouv.fr/avis/CERTFR-2024-AVI-0528/)|De multiples vulnérabilités ont été découvertes dans le noyau Linux de Red Hat. Certaines d'entre elles permettent à un attaquant de provoquer une élévation de privilèges, une atteinte à la confidentialité des données et un contournement de la politique de sécurité.|Publié le 28 juin 2024|
 |[](https://www.cert.ssi.gouv.fr/avis/CERTFR-2024-AVI-0527/)|De multiples vulnérabilités ont été découvertes dans le noyau Linux de Debian LTS. Elles permettent à un attaquant de provoquer une élévation de privilèges, une atteinte à la confidentialité des données et un déni de service.|Publié le 28 juin 2024|
 |[](https://www.cert.ssi.gouv.fr/avis/CERTFR-2024-AVI-0526/)|De multiples vulnérabilités ont été découvertes dans le noyau Linux de SUSE. Certaines d'entre elles permettent une élévation de privilèges, un déni de service à distance et une atteinte à la confidentialité des données.|Publié le 28 juin 2024|
 |[](https://www.cert.ssi.gouv.fr/avis/CERTFR-2024-AVI-0525/)|De multiples vulnérabilités ont été découvertes dans les produits Juniper Networks. Elles permettent à un attaquant de provoquer une exécution de code arbitraire à distance et un contournement de la politique de sécurité.|Publié le 28 juin 2024|
 |[](https://www.cert.ssi.gouv.fr/avis/CERTFR-2024-AVI-0524/)|De multiples vulnérabilités ont été découvertes dans les produits VMware. Elles permettent à un attaquant de provoquer un déni de service à distance, une atteinte à la confidentialité des données et un contournement de la politique de sécurité.|Publié le 28 juin 2024|
 |[](https://www.cert.ssi.gouv.fr/avis/CERTFR-2024-AVI-0523/)|De multiples vulnérabilités ont été découvertes dans Microsoft Edge. Elles permettent à un attaquant de provoquer une exécution de code arbitraire à distance et un problème de sécurité non spécifié par l'éditeur.|Publié le 28 juin 2024|
 |[](https://www.cert.ssi.gouv.fr/avis/CERTFR-2024-AVI-0522/)|Une vulnérabilité a été découverte dans OpenSSL. Elle permet à un attaquant de provoquer une atteinte à la confidentialité des données et un déni de service.|Publié le 27 juin 2024|
 |[](https://www.cert.ssi.gouv.fr/avis/CERTFR-2024-AVI-0521/)|De multiples vulnérabilités ont été découvertes dans GitLab. Certaines d'entre elles permettent à un attaquant de provoquer un déni de service à distance, une atteinte à la confidentialité des données et une atteinte à l'intégrité des données.|Publié le 27 juin 2024|
 |[](https://www.cert.ssi.gouv.fr/avis/CERTFR-2024-AVI-0520/)|De multiples vulnérabilités ont été découvertes dans les produits Progress. Elles permettent à un attaquant de provoquer un contournement de la politique de sécurité|Publié le 26 juin 2024|
 
 ---

## OBS-Vigilance [:arrow_heading_up:](#cyberowl)

 |Title|Description|Date|
 |---|---|---|
 |[<a href="https://vigilance.fr/vulnerability/FFmpeg-use-after-free-via-av-hwframe-ctx-init-44171" class="noirorange"><b>FFmpeg</b>: use after free via av_hwframe_ctx_init(<wbr>)</wbr></a>](https://vigilance.fr/vulnerability/FFmpeg-use-after-free-via-av-hwframe-ctx-init-44171)|An attacker can force the reuse of a freed memory area of FFmpeg, via av_hwframe_ctx_init(|Visit link for details|
 |[<a href="https://vigilance.fr/vulnerability/FFmpeg-buffer-overflow-via-image-copy-plane-44170" class="noirorange"><b>FFmpeg</b>: buffer overflow via image_copy_plane()</a>](https://vigilance.fr/vulnerability/FFmpeg-buffer-overflow-via-image-copy-plane-44170)|An attacker can trigger a buffer overflow of FFmpeg, via image_copy_plane(), in order to trigger a denial of service, and possibly to run code...|Visit link for details|
 |[<a href="https://vigilance.fr/vulnerability/FFmpeg-buffer-overflow-via-ff-bwdif-filter-intra-c-44169" class="noirorange"><b>FFmpeg</b>: buffer overflow via ff_bwdif_filter_<wbr>intra_c()</wbr></a>](https://vigilance.fr/vulnerability/FFmpeg-buffer-overflow-via-ff-bwdif-filter-intra-c-44169)|An attacker can trigger a buffer overflow of FFmpeg, via ff_bwdif_filter_|Visit link for details|
 |[<a href="https://vigilance.fr/vulnerability/buildah-information-disclosure-via-containerignore-dockerignore-44168" class="noirorange"><b>buildah</b>: information disclosure via containerignore / dockerignore</a>](https://vigilance.fr/vulnerability/buildah-information-disclosure-via-containerignore-dockerignore-44168)|An attacker can bypass access restrictions to data of buildah, via containerignore / dockerignore, in order to read sensitive information...|Visit link for details|
 |[<a href="https://vigilance.fr/vulnerability/IBM-i-privilege-escalation-via-Unqualified-Library-Call-44167" class="noirorange"><b>IBM i</b>: privilege escalation via Unqualified Library Call</a>](https://vigilance.fr/vulnerability/IBM-i-privilege-escalation-via-Unqualified-Library-Call-44167)|An attacker can bypass restrictions of IBM i, via Unqualified Library Call, in order to escalate his privileges...|Visit link for details|
 |[<a href="https://vigilance.fr/vulnerability/Webmin-privilege-escalation-via-Shell-Autocomplete-44166" class="noirorange"><b>Webmin</b>: privilege escalation via Shell Autocomplete</a>](https://vigilance.fr/vulnerability/Webmin-privilege-escalation-via-Shell-Autocomplete-44166)|An attacker can bypass restrictions of Webmin, via Shell Autocomplete, in order to escalate his privileges...|Visit link for details|
 |[<a href="https://vigilance.fr/vulnerability/FRRouting-overload-via-MP-GR-Dynamic-Capability-44162" class="noirorange"><b>FRRouting</b>: overload via MP/GR Dynamic Capability</a>](https://vigilance.fr/vulnerability/FRRouting-overload-via-MP-GR-Dynamic-Capability-44162)|An attacker can trigger an overload of FRRouting, via MP/GR Dynamic Capability, in order to trigger a denial of service...|Visit link for details|
 |[<a href="https://vigilance.fr/vulnerability/MediaWiki-Cross-Site-Scripting-via-RightsLogFormatter-php-44161" class="noirorange"><b>MediaWiki</b>: Cross Site Scripting via RightsLogFormatter.<wbr>php</wbr></a>](https://vigilance.fr/vulnerability/MediaWiki-Cross-Site-Scripting-via-RightsLogFormatter-php-44161)|An attacker can trigger a Cross Site Scripting of MediaWiki, via RightsLogFormatter.|Visit link for details|
 |[<a href="https://vigilance.fr/vulnerability/Linux-kernel-multiple-vulnerabilities-dated-29-04-2024-44160" class="noirorange"><b>Linux kernel</b>: multiple vulnerabilities dated 29/04/2024</a>](https://vigilance.fr/vulnerability/Linux-kernel-multiple-vulnerabilities-dated-29-04-2024-44160)|An attacker can use several vulnerabilities of the Linux kernel, dated 29/04/2024...|Visit link for details|
 |[<a href="https://vigilance.fr/vulnerability/GitLab-CE-EE-multiple-vulnerabilities-42419" class="noirorange"><b>GitLab CE/EE</b>: multiple vulnerabilities</a>](https://vigilance.fr/vulnerability/GitLab-CE-EE-multiple-vulnerabilities-42419)|An attacker can use several vulnerabilities of GitLab CE/EE...|Visit link for details|
 
 ---

## MA-CERT [:arrow_heading_up:](#cyberowl)

 |Title|Description|Date|
 |---|---|---|
 
 ---

## VulDB [:arrow_heading_up:](#cyberowl)

 |Title|Description|Date|
 |---|---|---|
 