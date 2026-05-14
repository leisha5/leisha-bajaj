---
layout: post
title: "To AI or Not To AI"
subtitle: "An analysis of AI-powered authentication"
date: 2026-03-08
permalink: /blog/to-ai-or-not-to-ai/
image: "/assets/images/hero.webp"
image_alt: "Yorick’s Skull from Shakespeare’s <em>Hamlet</em>, Act 5, Scene 1."
tags: [AI, Artificial Intelligence, Authentication, Privacy, Cybersecurity]
---

There are several problems with authentication as we know it today. Static authentication methods often lack the flexibility to respond to evolving cyber threats, especially with attackers leveraging more and more advanced techniques. 

Passwords are suspect to a host of hacking opportunities, from both automated attacks and from human deception. They can be stuffed, sprayed, phished, and surfed. Biometric authentication, on the other hand, is generally safer as it relies on unique physical characteristics which cannot be replicated easily. 


Some common methods of biometric authentication include:
- Fingerprint Recognition: Reliable and widely adopted but it’s susceptible to spoofing using fake fingerprints.
- Facial Recognition: Convenient but heavily influenced by environmental factors (e.g. lighting, positioning) and vulnerable to deepfakes.
- Voice Recognition: Provides hands-free authentication but can be compromised by replay attacks and voice cloning.
- Behavioral Biometrics: Analyses patterns like typing speed, gait, etc. which offers higher resilience to spoofing. However, this is highly context-dependent, unable to adapt to environmental changes, and has high error rates.


Adaptive authentication aims to resolve some of these limitations. That is, authentication that dynamically adjusts security measures based on contextual factors (e.g. user behavior, device type, geolocation). It offers real-time risk assessment to identify anomalies and has multi-layered security protocols that activate during high-risk scenarios.

Current adaptive authentication techniques often rely on static rules, making them less effective against advanced threats. This is where AI comes into play. Through machine learning and deep learning, models can continuously adapt to evolving threats, learning from user behavior and system interactions to enhance security. AI-powered adaptive authentication would change the playing field altogether, by providing enhanced security, an improved user experience, and widespread applicability.

A model like this would be able to incorporate real-time contextual analysis, allowing it to adjust authentication requirements based on risk levels. For example, lower-risk scenarios such as routine logins would only require single-factor authentication, while higher-risk situations like a suspicious location would trigger additional authentication layers.

This leads to the titular question: To AI or not to AI?

Using AI-powered adaptive authentication techniques would resolve the majority of limitations associated with other authentication methods, but it opens up a pandora’s box of entirely new concerns.

Take privacy, for example. Even with using federated learning and blockchain to preserve privacy, you would still be collecting and storing of individuals who, for all intents and purposes, cannot give informed consent. The majority of the world is not technologically-literate, and instituting such methods in the name of advanced security would discriminate against them by taking advantage of their data.

Currently, AI-powered authentication is being used for age verification to protect children’s safety online. A good idea in theory, but in practice is privacy infringements after privacy infringements. Take Roblox’s error-prone age verification model, which gave more problems than solutions, or Discord’s age-verification cyber attack which did nothing except decrease user trust.

The “age verification trap” is a result of mandatory age enforcement at the cost of privacy to an optional status. Not to mention the biases encoded into the models themselves; issues of racism and ableism are only exacerbated with using AI models for everything.

My thoughts? Not to AI. Not at the cost of privacy and trust.


## References

Asare, Janice. “Ai Age Checks Are Here — and They’re Not Fair to Everyone.” Forbes, 13 Aug. 2025, www.forbes.com/sites/janicegassam/2025/08/13/ai-age-checks-are-here-and-theyre-not-fair-to-everyone/

Gilbert, David. “Roblox’s AI-Powered Age Verification Is a Complete Mess.” Wired, Conde Nast, 13 Jan. 2026, www.wired.com/story/robloxs-ai-powered-age-verification-is-a-complete-mess/

Gioino, Catherina. “Social Media Companies Are Fighting the ‘age Verification Trap’ as Collecting Biometrics on Kids Violates Privacy Rights.” Fortune, Fortune, 2 Mar. 2026, fortune.com/2026/03/02/social-media-companies-age-verification-addiction-privacy-concerns/

Hays, Kali. “Discord Delays Age Verification Plans after User Outcry.” BBC News, BBC, 24 Feb. 2026, www.bbc.com/news/articles/cvgv0yg4n9lo

Liang, Yunji, and Sagar Samtani. “Behavioral Biometrics for Continuous Authentication in the Internet-of-Things Era: An Artificial Intelligence Perspective | IEEE Journals & Magazine | IEEE Xplore.” IEEE Internet of Things Journal, 22 June 2022, ieeexplore.ieee.org/document/9121981/

William, Bruce, et al. “(PDF) AI-Driven Adaptive Authentication: Revolutionizing Multi-Modal Biometric Security.” ResearchGate, June 2022, www.researchgate.net/publication/387949482_AI-Driven_Adaptive_Authentication_Revolutionizing_Multi-Modal_Biometric_Security