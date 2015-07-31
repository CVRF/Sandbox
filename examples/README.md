# CVRF Examples
This is a collection of examples of CVRF files, as well as other proof-of-concept extensions.

## cvrfFiles
A collection of examples of CVRF files.

## stixCvrf

Examples on how to carry a CVRF document within Structured Threat Information eXpression (STIX). Currently, STIX supports the ability to embed CVRF documents inside a STIX "exploit target". [Exploit targets](http://stixproject.github.io/data-model/1.2/et/ExploitTargetType/) in STIX are used to represent things that might be the target of an attack, such as vulnerabilities, misconfigurations, and weaknesses. 

Those [exploit targets](http://stixproject.github.io/data-model/1.2/et/ExploitTargetType/) can then be either used independently or, more likely, related to other constructs to build a more comprehensive picture. For example, you can create a TTP (TTP = tactics, techniques, and procedures) representing a piece of malware and then use the TTP => Exploit Target relationship to denote that that piece of malware exploits the vulnerability described by the CVRF document. If you'd like to see an example of this we could do that.

In the stixCvrf are examples of a valid STIX document with a single exploit target that contains a CVRF document.

Another possibility is that to make it easier for people to use we could collaboratively develop an "idiom" (example) to describe how to use CVRF inside STIX, similar to the [idiom for representing a vulnerability by CVE in STIX](http://stixproject.github.io/documentation/idioms/cve/).
