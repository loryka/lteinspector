lteinspector
=====
Abstract—In this paper, we investigate the security and privacy
of the three critical procedures of the 4G LTE protocol (i.e.,
attach, detach, and paging), and in the process, uncover potential
design flaws of the protocol and unsafe practices employed by the
stakeholders. For exposing vulnerabilities, we propose a modelbased
testing approach LTEInspector which lazily combines a
symbolic model checker and a cryptographic protocol verifier
in the symbolic attacker model. Using LTEInspector, we have
uncovered 10 new attacks along with 9 prior attacks, categorized
into three abstract classes (i.e., security, user privacy,
and disruption of service), in the three procedures of 4G LTE.
Notable among our findings is the authentication relay attack that
enables an adversary to spoof the location of a legitimate user
to the core network without possessing appropriate credentials.
To ensure that the exposed attacks pose real threats and are
indeed realizable in practice, we have validated 8 of the 10 new
attacks and their accompanying adversarial assumptions through
experimentation in a real testbed.

## LTEINSPECTOR - ATTACKING 4G LTE NETWORKS 
This is a repository to hold information, packages, notes, resources, scripts, binaries and other material related to, ["LTEInspector: A Systematic Approach for Adversarial Testing of 4G LTE"](http://wp.internetsociety.org/ndss/wp-content/uploads/sites/25/2018/02/ndss2018_02A-3_Hussain_paper.pdf).

The paper was authored by four students: 

Syed Rafiul Hussain
Purdue University
hussain1@purdue.edu

Omar Chowdhury
The University of Iowa
omar-chowdhury@uiowa.edu

Shagufta Mehnaz
Purdue University
smehnaz@purdue.edu

Elisa Bertino
Purdue University
bertino@purdue.edu

