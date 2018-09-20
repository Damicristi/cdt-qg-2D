# Causal Dynamical Triangulations (CDT) (1+1) Dimensions
 [![Open Issues](https://img.shields.io/github/issues-raw/Damicristi/cdt-qg-2D.svg)](https://github.com/Damicristi/cdt-qg-2D/issues)
[![Join the chat at https://gitter.im/physicslog/cdt-qg-2D](https://img.shields.io/badge/gitter-join%20chat%20→-brightgreen.svg)](https://gitter.im/physicslog/cdt-qg-2D)

Author: [Damodar Rajbhandari](https://damodarrajbhandari.com.np), Outreach blogger at [Physics Log](http://www.physicslog.com/)  
In the Collaboration with: [Dr. Jonah Maxwell Miller](mailto:jonah.maxwell.miller@gmail.com) and [Prof. Dr. Udayaraj Khanal](mailto:khanalu@yahoo.com)

## Introduction

After introducing the General Theory of Relativity (in 1915), Einstein pointed out that quantum effects will lead to modifications of his theory. We call the unknown theory required to study these effects “quantum gravity”. Unfortunately, a naive quantization of general relativity appears to be perturbatively non-renormalizable. This is one of the greatest challenges facing in modern theoretical physics.

One can attempt to construct a theory of quantum gravity by defining a non-perturbative quantum field theory as a sum over histories. This technique is a modification of Feynman path integral formulation which was first put forwarded by Stephen Hawking and Gary William Gibbons for their quantum gravity approach “Euclidean quantum gravity ”. In-short, instead of superposing the usual Lorentzian spacetimes, they used Euclidean spaces which have four space dimensions. The hope of Euclidean quantum gravity was that spacetime could be assumed to be Euclidean and that time would emerge dynamically. Unfortunately, this did not work out. In the 1990s, this work was combined with quantum Regge calculus so that it could be formulated non-perturbatively. This was called Dynamical Triangulations. This technique failed due to unboundedness in the gravitational action. And also the path integral knows nothing about causality (i.e. light cone structure of the spacetime) and there’s no specification that any test matter will bounded by light cones. In an effort to resolve these issues, Renate Loll, Jan Ambjørn and Jerzy Jurkiewicz reformulated this construction, but with Lorentzian signature imposed from the start. They only map into Euclidean signature via Wick rotation after constructing the theory. Thus, Causal Dynamical Triangulations was born (initially, it was named as Lorentzian Dynamical Triangulations). This approach provides concrete evidence that one must include causal structure, in the sense of having a well-defined light cones everywhere. This model imposed preferred foliation of time so that we can track of time direction. But the question is, does CDT rely on distinguished time slicing? To answer this question, Renate Loll and Samo Jordan introduced the more general version of CDT which is called CDT without preferred foliation (equivalent to say, Locally causal dynamical triangulations) and found the answer to be hopefully no.

The main motivation for choosing this approach is that it is relies on very few fundamental physical principles and attempts to quantize gravitational degree of freedom without introduction of additional variables, extra dimensions or new symmetries widely used by String theory (for example). Moreover, it comes with definite numerical approximation scheme. To study the numerical simulations of 1+1 dimensional CDT with non-foliated structure, we requires new Monte Carlo moves, which are significantly more difficult to implement than the generalized Pachner moves used in standard CDT.

## Background theories
1. General Relativity
2. Quantum Field Theory
3. Regge Calculus

## Theory Keywords
1. Einstein Hibert Action
2. Feynmann Path Integral
3. Gauss-Bonnet Theorem
4. Wick Rotation
5. Euler characteristics
6. Periodic Boundary Condition
7. Boltzmann Probability

## Simulation Keywords
1. Python v3.x with Object oriented programming
2. Data Structure
3. Causality Test
4. Metropolis-Hastings Algorithm
5. Toroidal Topology
6. Monte-Carlo Moves
7. Volume fixing terms

## Basics Reading (Online Stuffs)
1. [Wikibooks: Spacetime](https://en.wikibooks.org/wiki/Special_Relativity/Spacetime)
2. [PBS Space Time](https://www.youtube.com/channel/UC7_gcs09iThXybpVgjHZ_7g/playlists) 
3. [Einstein Online](http://www.einstein-online.info/index.html)
4. [The Physics Mill](http://www.thephysicsmill.com/)

## Recommended Reading Materials
Please go to this link: [readings.physicslog.com](https://readings.physicslog.com#causal-dynamical-triangulations).

## Code Documentation
Please download from this link: [Damodar's Bachelor Approved Thesis by Tribhuvan University](https://www.researchgate.net/publication/327108635_An_Open_Source_Code_for_Causal_Dynamical_Triangulations_Without_Preferred_Foliation_in_11-_Dimensions_with_Elementary_Expositions).

## Presentation
Plese download from this link: [Final Bachelor Defense Presentation](https://www.researchgate.net/publication/326837831_An_open_source_code_for_Causal_Dynamical_Triangulations_without_preferred_foliation_in_11-_dimensions_with_elementary_expositions?_iepl%5BviewId%5D=7N81OWlysW0sGWe7ejoAv9G2&_iepl%5Bcontexts%5D%5B0%5D=projectUpdatesLog&_iepl%5BtargetEntityId%5D=PB%3A326837831&_iepl%5BinteractionType%5D=publicationTitle).

## How you can contribute to our open source code?
Our programming language preference is Python 3.x. version under the object oriented paradigm. The goals and target of this project are:

- [x] Data structure
- [x] Causality test
- [x] Alexander move
- [x] Collapse move
- [ ] Inverse Alexander move
- [ ] Inverse collapse move
- [ ] Flip move
- [ ] Inverse flip move
- [ ] Pinching move
- [ ] Inverse pinching move
- [ ] Volume control terms to fixed the spacetime topology
- [ ] Metropolis-Hastings algorithm
- [ ] Python Script consisting of input data to run the simulation
- [ ] Generate Quantum spacetime ensembles

## Forum
You can join our discussions at [![Join the chat at https://gitter.im/physicslog/cdt-qg-2D](https://img.shields.io/badge/gitter-join%20chat%20→-brightgreen.svg)](https://gitter.im/physicslog/cdt-qg-2D). I want you to enjoy your stay there as much as possible. And I’m hoping that you help to maintain a welcome and pleasant atmosphere in here.

## Buy me a coffee
I'm hoping to rely on loyal readers, rather than erratic ads. Click the Donate button and support this project. Thank you!
<center>
<form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
<input type="hidden" name="cmd" value="_s-xclick">
<input type="hidden" name="encrypted" value="-----BEGIN PKCS7-----MIIHPwYJKoZIhvcNAQcEoIIHMDCCBywCAQExggEwMIIBLAIBADCBlDCBjjELMAkGA1UEBhMCVVMxCzAJBgNVBAgTAkNBMRYwFAYDVQQHEw1Nb3VudGFpbiBWaWV3MRQwEgYDVQQKEwtQYXlQYWwgSW5jLjETMBEGA1UECxQKbGl2ZV9jZXJ0czERMA8GA1UEAxQIbGl2ZV9hcGkxHDAaBgkqhkiG9w0BCQEWDXJlQHBheXBhbC5jb20CAQAwDQYJKoZIhvcNAQEBBQAEgYCZo7U809avSwRRli8uKFyeQeHbgaNIcemvxF4ZsjsBlQ6WCm9gcA0iAddP7tDFyEZV/b6TaciyOXhjFnmoG/Ar2drD0geCuiDtxW21yTorSPc+z3LbpdBddK3HD+v+OYrBtLM4OsLfKzZHAEdr6KhKDHC3dxCG8REL2NTJ47RUfDELMAkGBSsOAwIaBQAwgbwGCSqGSIb3DQEHATAUBggqhkiG9w0DBwQIg+bkXLZGa6yAgZjCeaqiKN00c/5HEDEgqVrT0lI506wNwRklhQn9jl4bQT3bi0EvWViP66Sos0xwsNx+HptZQQlxxmssFFSRBV6dLguGzUw+J/7aOqNEV+4bfdv2Rf6MHn+3SI0MS2UjsalukGPziWMCWa58n1B8HSL1VnwU2XBE+Un9gfHwct8fNwHB+PF6iykh3+Fpg14Gn2H7Xue7+A3lbaCCA4cwggODMIIC7KADAgECAgEAMA0GCSqGSIb3DQEBBQUAMIGOMQswCQYDVQQGEwJVUzELMAkGA1UECBMCQ0ExFjAUBgNVBAcTDU1vdW50YWluIFZpZXcxFDASBgNVBAoTC1BheVBhbCBJbmMuMRMwEQYDVQQLFApsaXZlX2NlcnRzMREwDwYDVQQDFAhsaXZlX2FwaTEcMBoGCSqGSIb3DQEJARYNcmVAcGF5cGFsLmNvbTAeFw0wNDAyMTMxMDEzMTVaFw0zNTAyMTMxMDEzMTVaMIGOMQswCQYDVQQGEwJVUzELMAkGA1UECBMCQ0ExFjAUBgNVBAcTDU1vdW50YWluIFZpZXcxFDASBgNVBAoTC1BheVBhbCBJbmMuMRMwEQYDVQQLFApsaXZlX2NlcnRzMREwDwYDVQQDFAhsaXZlX2FwaTEcMBoGCSqGSIb3DQEJARYNcmVAcGF5cGFsLmNvbTCBnzANBgkqhkiG9w0BAQEFAAOBjQAwgYkCgYEAwUdO3fxEzEtcnI7ZKZL412XvZPugoni7i7D7prCe0AtaHTc97CYgm7NsAtJyxNLixmhLV8pyIEaiHXWAh8fPKW+R017+EmXrr9EaquPmsVvTywAAE1PMNOKqo2kl4Gxiz9zZqIajOm1fZGWcGS0f5JQ2kBqNbvbg2/Za+GJ/qwUCAwEAAaOB7jCB6zAdBgNVHQ4EFgQUlp98u8ZvF71ZP1LXChvsENZklGswgbsGA1UdIwSBszCBsIAUlp98u8ZvF71ZP1LXChvsENZklGuhgZSkgZEwgY4xCzAJBgNVBAYTAlVTMQswCQYDVQQIEwJDQTEWMBQGA1UEBxMNTW91bnRhaW4gVmlldzEUMBIGA1UEChMLUGF5UGFsIEluYy4xEzARBgNVBAsUCmxpdmVfY2VydHMxETAPBgNVBAMUCGxpdmVfYXBpMRwwGgYJKoZIhvcNAQkBFg1yZUBwYXlwYWwuY29tggEAMAwGA1UdEwQFMAMBAf8wDQYJKoZIhvcNAQEFBQADgYEAgV86VpqAWuXvX6Oro4qJ1tYVIT5DgWpE692Ag422H7yRIr/9j/iKG4Thia/Oflx4TdL+IFJBAyPK9v6zZNZtBgPBynXb048hsP16l2vi0k5Q2JKiPDsEfBhGI+HnxLXEaUWAcVfCsQFvd2A1sxRr67ip5y2wwBelUecP3AjJ+YcxggGaMIIBlgIBATCBlDCBjjELMAkGA1UEBhMCVVMxCzAJBgNVBAgTAkNBMRYwFAYDVQQHEw1Nb3VudGFpbiBWaWV3MRQwEgYDVQQKEwtQYXlQYWwgSW5jLjETMBEGA1UECxQKbGl2ZV9jZXJ0czERMA8GA1UEAxQIbGl2ZV9hcGkxHDAaBgkqhkiG9w0BCQEWDXJlQHBheXBhbC5jb20CAQAwCQYFKw4DAhoFAKBdMBgGCSqGSIb3DQEJAzELBgkqhkiG9w0BBwEwHAYJKoZIhvcNAQkFMQ8XDTE3MTIyMTEyNTI1NFowIwYJKoZIhvcNAQkEMRYEFNkVY787Vk37yNuMw4jtXKiOE3imMA0GCSqGSIb3DQEBAQUABIGAhyPiYoFdCKXj77h+0nFndGP1nKlThI0nx7l7WlrF4EGwhR5DxRQwwiCrN7g3NZyKEdoUTU5O1PPswEV/bsLMsii0KFIeENxMhx9AGCJc34kiF28QAZi8pbUluO2pXoSlEXj8s7FdILIIGZ70fJjPhz4oUfFFl5k70J/gfbaIrfo=-----END PKCS7-----
">
<input type="image" src="https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif" border="0" name="submit" alt="PayPal - The safer, easier way to pay online!">
<img alt="" border="3" src="https://www.paypalobjects.com/en_AU/i/scr/pixel.gif" width="30" height="15">
</form>
</center>

## Last Words
If anyone wants to contribute in this project, you are welcome.

## Special Thanks
To Prof. Dr. Jerzy Jurkiewicz (Jagiellonian University, Poland), Prof. Dr. Steven Carlip (University of California, Davis, USA), Dr. Ben Ruijl (ETH Zurich, Switzerland), Dr. Joshua Cooperman (Radboud University, Netherlands) and Mr. Adam Getchell (University of California, Davis, USA), who provided invaluable advices. 

## Invitation
I invite you to ask any questions you may have via dphysicslog[at]gmail[dot]com.

##### [Click Here to go in Home page](https://projects.physicslog.com)
