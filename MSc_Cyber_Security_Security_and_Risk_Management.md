# MSc Cyber Security — Security & Risk Management   
**Student:** Ketan Dileep Mone   
**Programme:** University of Essex Online — MSc Cyber Security   
**Module:** Security & Risk Management     
**Live URL:** [https://ketanmone.github.io/MSc_Cyber_Security_Security_and_Risk_Management](https://ketanmone.github.io/MSc_Cyber_Security_Security_and_Risk_Management)

---

This e-portfolio summarises learning and artefacts from **Units 1–12**, links outcomes to assessments, and closes with a **module-wide reflective synthesis** (aligned to Rolfe et al.’s What? / So What? / Now What?). I attended **two live seminars** and—given time zones and schedule—**engaged with recordings for the rest**, supplementing them with extended readings and detailed write-ups to maintain continuity and depth.

---

## 🧩 Unit 1 — An Introduction to Security and Risk Management

**Focus.** Foundations: definitions, concepts, and processes.  
**Overview.** The unit established core terminology—threats, vulnerabilities, likelihood, impact, and residual risk—and contrasted qualitative vs. quantitative assessment, framed by **ISO 31000**, **NIST SP 800-30**, and **FAIR**.  
**Key learnings.** (1) Risk combines likelihood and impact and must be revisited continuously; (2) qualitative rankings vs. quantitative estimates each have a place; (3) the five-step RMP (Identify → Assess → Evaluate → Treat → Monitor) underpins later work.  
**Activities.** Lecturecast (1 hr), ~7 hrs guided reading, cohort/team formation for **Pampered Pets**, e-portfolio setup. I reviewed the **seminar recording** to capture assessment expectations.  
**Reflection.** Establishing a shared vocabulary prevented later confusion when mixing qualitative registers with numeric models. It also set the tone that **security is a continuous improvement process**, not a one-off audit.

---

## 🧩 Unit 2 — Users, Assessments and the Risk Management Process

**Focus.** The RMP, assessment types, and user participation.  
**Overview.** Compared **qualitative** and **quantitative** approaches and examined how **stakeholder participation** improves accuracy and adoption. *Spears & Barki (2010)* highlighted how participation increases shared ownership and reduces project risk.  
**Key learnings.** (1) No single method is superior in all contexts; (2) RMP is iterative; (3) user involvement surfaces tacit knowledge and realistic mitigations.  
**Activities.** ~4 hrs reading incl. Spears & Barki; contributed to **Collaborative Discussion 1**; updated e-portfolio. I used the **seminar recording** to capture facilitation techniques for inclusive workshops.  
**Reflection.** I shifted from a “top-down controls” mindset to a **socio-technical perspective**. Involving users early made subsequent modelling and mitigation more grounded and ethically responsible.

---

## 🧩 Unit 3 — Introduction to Threat Modelling and Management

**Focus.** Threat vs. vulnerability; applying and combining models.  
**Overview.** Surveyed **STRIDE**, **DREAD**, **Attack Trees**, and **PASTA**. STRIDE categorises attacker goals; DREAD offers risk scoring; Attack Trees map paths; PASTA integrates business impact with technical analysis.  
**Key learnings.** (1) Threats exploit vulnerabilities; (2) models are lenses—choose intentionally; (3) hybridisation can reconcile business and technical needs; (4) threat modelling is iterative as systems evolve.  
**Activities.** Lecturecast (1 hr), ~5 hrs reading, contributed to wiki on STRIDE vs. PASTA; documented how threat modelling complements RMP.  
**Reflection.** Using multiple frames sharpened my ability to anticipate attacker behaviour **and** relate it to business appetite—skills I reused in quantitative modelling.

---

## 🧩 Unit 4 — Application of Threat Modelling and Management Techniques

**Focus.** Practical application with community resources.  
**Overview.** Worked with the **Threat Modelling Manifesto**, **OWASP Threat Modelling Cookbook**, and **MITRE ATT&CK**. Emphasis on choosing tools based on system architecture, data, and maturity; validated scenarios with **CVSS** scoring.  
**Key learnings.** Where to find and how to apply modern practices; when to use STRIDE/DREAD/Attack Trees; how hybrid models integrate technical attack simulation and business impact.  
**Activities.** ~8 hrs tool-based reading; **seminar recording**: hands-on exercises; captured diagrams, comparisons, and peer feedback.  
**Reflection.** ATT&CK’s TTPs anchored abstract risks to concrete behaviours. I learned to balance thoroughness with usability so that the model informs decisions rather than becoming shelfware.

---

## 🧩 Unit 5 — Security and Risk Standards in Industry and the Enterprise

**Focus.** Standards as governance baselines.  
**Overview.** Positioned **ISO/IEC 27001**, **ISO 31000**, **NIST SP 800-53**, **PCI DSS**, **GDPR**, and **COBIT** as a shared language for policy, process, and controls. Compliance ≠ maturity, but standards **structure** maturity journeys.  
**Key learnings.** Matching frameworks to domain (e.g., GDPR for privacy, PCI DSS for payments); embedding controls within threat models; understanding how standards influence cloud/supply-chain designs.  
**Activities.** Lecturecast (1 hr); ~2 hrs readings; **GDPR case studies** (Articles 32/33); wiki contribution comparing ISO 31000 vs. NIST 800-30.  
**Reflection.** The case studies clarified the **ethical dimension** of compliance: it protects people. Mapping controls to models improved later quantification fidelity.

---

## 🧩 Unit 6 — Practical Implications of Security and Risk Standards

**Focus.** Putting GDPR / PCI-DSS / ISO 27000 to work.  
**Overview.** Translated regulatory language into operational practices, clarifying which clauses apply where and how to design feasible mitigations.  
**Key learnings.** GDPR **Art. 32 & 33** in breach management; PCI-DSS minimums (encryption, logging, key rotation); ISO 27000 alignment with enterprise risk.  
**Activities.** ~2 hrs readings; continued reflections; **seminar recording** on overlaps/conflicts; submitted **Development Team Project: Risk Identification Report** (score **65%**). A peer-review submission was missed due to a platform glitch and discussed with the tutor.  
**Reflection.** Standards become **enablers** when operationalised. The team report reinforced structured documentation and crisp communication—vital for executive audiences—and primed my later quantitative work (linking compliance metrics to performance like RTO/RPO).

---

## 🧩 Unit 7 — Concepts of Quantitative Risk Modelling

**Focus.** Monte Carlo, Bayesian inference, and MCDA (TOPSIS, AHP, ANP).  
**Overview.** Introduced **QRM** foundations: probability distributions, sensitivity analysis, and expected loss. Positioned **Monte Carlo** for stochastic simulation, **Bayesian** methods for belief updating, and **MCDA** for ranking trade-offs.  
**Key learnings.** The goal is **decision quality**, not spurious precision; recognise method anti-patterns (e.g., unstable priors, misread simulations).  
**Activities.** Lecturecast (1 hr); ~8 hrs reading (Olsen & Desheng, 2020); risk-modelling activities; consolidated equations/notes for the individual project.  
**Reflection.** I moved from description to **data-driven reasoning**. Monte Carlo made uncertainty visible; Bayesian updating aligned with continuous monitoring; MCDA showed why numbers still require expert judgement.

---

## 🧩 Unit 8 — Implementing Quantitative Risk Models

**Focus.** Hands-on QRM for real-world decisions.  
**Overview.** Built small Monte Carlo simulations and applied **Bayes’ theorem** to update priors. Used outputs (intervals, thresholds) to inform management choices and stress-tested assumptions to avoid overfitting.  
**Key learnings.** Translate simulations into executive-ready insights; document assumptions; tie QRM to governance cycles.  
**Activities.** ~8 hrs case-study reading; **seminar recording**: guided simulation exercises; Discussion 2 (Week 2) peer responses; e-portfolio updates; refined model approach for **Unit 11**.  
**Reflection.** Implementing models honed the balance between **mathematical rigour and interpretive judgement** and improved my ability to defend mitigation priorities with evidence.

---

## 🧩 Unit 9 — Risk, Business Continuity and Disaster Recovery

**Focus.** BC/DR as operational resilience.  
**Overview.** Defined **BIA**, **RTO** (time to restore), and **RPO** (acceptable data loss) and linked them to layered recovery strategies. Readings covered DR evaluation and probabilistic prediction.  
**Key learnings.** Conducting a BIA; setting realistic RTO/RPO; appreciating cloud BC/DR, geo-redundancy, and AI-assisted recovery; aligning to **ISO 22301**.  
**Activities.** Lecturecast (1 hr); ~2 hrs readings (Alhazmi & Malaiya; Andrade et al.; Olsen & Desheng); drafted RTO/RPO scenarios for my final submission; expanded reflections.  
**Reflection.** I reframed risk management as **continuity management**: resilience spans technology, people, process, and communications. DR metrics are strategic **trade-offs**, not absolutes.

---

## 🧩 Unit 10 — Practical Applications and Issues in DR Implementations

**Focus.** Designing DR to targets; DRaaS trade-offs; vendor risk.  
**Overview.** Showed how RTO/RPO directly shape standby topologies (cold/warm/hot), automation, and cost; critiqued **DRaaS** for SLA dependency, lock-in, and network exposure.  
**Key learnings.** Map RTO/RPO to replication frequency/distance; avoid single-vendor fragility; consider latency, sovereignty, and security.  
**Activities.** ~2 hrs readings; ~8 hrs formative design work; **seminar recording** on DR solutions; vendor comparisons; reflected on hot cloud replication vs. hybrid on-prem.  
**Reflection.** DR design is systems thinking: align engineering with budgets and governance. Outsourcing resilience ≠ guaranteed resilience—multi-region/multi-vendor strategies reduce correlated failures.

---

## 🧩 Unit 11 — Future Trends in Security and Risk Management

**Focus.** Trends: AI/automation, zero trust, quantum-resistant crypto, regulatory evolution, and economic modelling.  
**Overview.** Positioned SRM’s shift from static frameworks to **adaptive, data-driven resilience**. Balanced automation’s efficiency with ethics and accountability.  
**Key learnings.** AI-driven risk scoring and automated compliance; economics for resource allocation; ML for detection with guardrails; convergence of cybersecurity, data governance, and sustainability.  
**Activities.** Lecturecast (1 hr); ~6 hrs readings (Aven; others); updated synthesis notes; wiki contributions; **submitted Individual Project: Executive Summary — “Quantitative Risk Modelling and Business Continuity Strategy for Pampered Pets Ltd.”**  
**Reflection.** My project integrated Monte Carlo, BC/DR, and governance—consistent with a future of **predictive, continuous controls**. The human role shifts from operator to **validator**, ensuring transparency and responsibility.

---

## 🧩 Unit 12 — The Great Debate: Most Influential Trend in the Next 5 Years

**Focus.** Synthesising evidence and making a defended prediction.  
**Overview.** Debated which trend will most shape SRM. We weighed AI-driven automation, zero trust, quantum-resilient security, data-driven modelling, and regulatory harmonisation.  
**Key learnings.** Evidence-based debate skills; articulating ethical and operational trade-offs; recognising cross-domain impacts on continuity and governance.  
**Activities.** ~2 hrs targeted readings; **seminar participation via recording**, plus wiki consolidation; finalised e-portfolio; end-of-module survey planned post-submission.  
**Reflection.** I argued that **AI-driven risk intelligence**—paired with human oversight—will be most influential, because it connects detection, response, and governance into a continuous feedback loop.

---
---

# 📄 Appendix: Module Assignments and Artefacts  

## 🧠 Development Team Project — Risk Identification Report  
**Title:** *Pampered Pets: Risk Assessment and Recommendations*  
**Type:** Group Submission — Team Cipher    
**Grade Achieved:** 65 %    
**Date Submitted:** 8 September 2025    

**Overview:**  
This collaborative report assessed the operational, cyber, and strategic risks facing *Pampered Pets Ltd.* during its early digitalisation phase. Using the **ISO 31000 Risk Management Framework**, the team compared the existing physical-store model with the proposed e-commerce expansion. The report identified insecure Wi-Fi, staff dependency, and outdated systems as the highest-impact risks, recommending phased digitalisation with layered mitigations such as multi-factor authentication, training, and vendor SLAs:contentReference[oaicite:0]{index=0}.  

**Key Outcomes:**  
- Established a structured, ISO-aligned risk register.  
- Proposed a four-phase digital-transformation roadmap balancing opportunity and resilience.  
- Developed team collaboration skills across distributed environments.  

**Reference Link:** [📘 Risk Assessment — Pampered Pets (Team Cipher)](https://ketanmone.github.io/Risk_Assessment_Pampered_Pets_Team_Cipher.pdf)

---

## 🧩 Individual Project — Executive Summary  
**Title:** *Quantitative Risk Modelling and Business Continuity Strategy for Pampered Pets Ltd.*  
**Type:** Individual Submission    
**Grade:** Pending    
**Date Submitted:** 13 October 2025  

**Overview:**  
This individual assignment extended the team project through **quantitative risk modelling** using *Monte Carlo Simulation* and *Failure Mode and Effects Analysis (FMEA)*. It quantified disruption probabilities from automation errors, supplier delays, and IoT cyber-attacks, and integrated a **Business Continuity & Disaster Recovery (BC/DR)** architecture meeting RTO/RPO ≤ 60 seconds.  
Results indicated a 21 % baseline disruption probability, reduced below 10 % with proposed controls. The multi-cloud BC/DR design (AWS + Azure) achieved compliance with ISO 22301, 27001, and GDPR Art. 32:contentReference[oaicite:1]{index=1}.  

**Key Outcomes:**  
- Demonstrated proficiency in quantitative-risk simulation and Bayesian updating.  
- Delivered an enterprise-grade continuity framework aligned with international standards.  
- Illustrated ethical digitalisation principles and sustainability alignment with UN SDGs 9 & 12.  

**Reference Link:** [📗 Executive Summary — Quantitative Risk Modelling and Business Continuity Strategy](https://ketanmone.github.io/Executive_Summary_Quantitative_Risk_Modelling.pdf)

---

### 🧾 Reflection on Artefacts  
Together, these artefacts evidence my progression from **qualitative risk identification** (Unit 6 team report) to **quantitative modelling and continuity design** (Unit 11 individual submission).  
The journey improved my technical literacy in **Monte Carlo simulations**, deepened my appreciation of **regulatory compliance**, and honed my ability to translate academic frameworks into actionable enterprise recommendations.  
These deliverables collectively demonstrate the learning outcomes of the *Security and Risk Management* module — critical analysis, methodological selection, ethical consideration, and the application of integrated risk strategies for real-world resilience.

## Module-wide Reflective Synthesis

### What? — Journey, artefacts, and capability growth  
Across twelve units, my trajectory moved from **shared definitions** and **process literacy** (Units 1–2) to **practical threat modelling** (Units 3–4), **standards-driven governance** (Units 5–6), **quantitative modelling** (Units 7–8), and **operational resilience** (Units 9–10), ending with **future trends and debate** (Units 11–12). Two artefacts anchor this journey:

* **Team Cipher — Risk Identification Report (Unit 6)**: a structured, ISO-aligned baseline of risks and mitigations for Pampered Pets’ digitalisation.  
* **Individual Executive Summary (Unit 11)**: quantitative prioritisation (Monte Carlo + FMEA) and a **multi-cloud BC/DR** strategy with tight RTO/RPO targets.

While I attended only **two live seminars**, I deliberately compensated by **systematically engaging with seminar recordings**, extending the set readings, and documenting my takeaways with screenshots, notes, and self-set exercises. This approach ensured continuity without overstating live attendance and, in practice, suited deep, reflective work.

### So What? — Critical insights and turning points  
Three moments changed my practice:

1) **From controls to culture.** Early on, I equated “more controls” with “more security.” The user-participation focus (Unit 2) and standards case studies (Unit 5–6) reframed security as **a social system** where adoption determines effectiveness. In later modelling, I explicitly considered training fatigue, process friction, and ownership—variables that often make or break controls.

2) **From scores to distributions.** Threat modelling gave structure, but **Monte Carlo** (Unit 7–8) changed my mental model of risk. Instead of single numbers, I now think in **ranges and likelihoods**, supported by sensitivity analysis. This helped me argue credibly for investing in high-leverage controls (identity, segmentation, detection) rather than spreading budget thinly.

3) **From continuity plans to resilience practice.** Units 9–10 connected risk to **recoverability**. Setting RTO/RPO targets and designing to them forced trade-offs between cost and speed. I learned that outsourcing to DRaaS reduces toil but may **increase systemic dependency**, so multi-region/multi-vendor approaches are preferable.

Ethically, Unit 11’s trend analysis made clear that **automation** can improve coverage yet amplify harm if ungoverned. My stance is **human-in-the-loop**: use AI to scale detection/response, but retain oversight, auditability, and clear accountability.

### Now What? — Applying lessons professionally and academically  
**Operational habits.** I will begin initiatives with a one-page **Risk Charter** that names assets, failure modes, owners, and RTO/RPO tolerances. I’ll embed **table-top exercises** and **post-incident learning reviews** each quarter, aligning with ISO/IEC and NIST guidance.

**Modelling roadmap.** Beyond Monte Carlo and FMEA, I plan to prototype **Bayesian networks** and **attack–defence trees** to capture dependencies and countermeasures. I’ll also experiment with **chaos engineering** to safely validate BC/DR assumptions in staging.

**Governance and ethics.** When proposing AI-enabled controls, I’ll include **model-risk** discussion (drift, bias, false positives) and safeguards (explanations, human approval points). This aligns privacy and fairness with security outcomes.

**Communication.** I will continue translating complex analysis into **plain-language narratives** with visual intervals, not just point estimates. Executives buy clarity; teams need actionable granularity. My Unit 6 feedback (65%) was a reminder to balance depth with succinct delivery.

**Personal stance on attendance.** I learned that live discussion accelerates nuance. While time-zones limited live participation, recordings plus systematic note-taking and extended reading sustained my momentum. In future modules, I’ll aim to **increase live engagement** while keeping my documentation discipline.

**Conclusion.** The module shifted my identity from documenting risk to **operationalising resilience**: designing controls that work, testing them, measuring them, and improving them continuously. That mindset—curious, quantitative, and ethically aware—is the through-line of this e-portfolio.

---

## References  

Aven, T. and Thekdi, S. (2025) *Risk Science* (2nd edn). Routledge.  
AWS (2023) *AWS Well-Architected Framework: Reliability Pillar*. Amazon Web Services.  
ENISA (2024) *ENISA Threat Landscape 2024*. European Union Agency for Cybersecurity.  
European Commission (2022) *Proposal for a Cyber Resilience Act*. Brussels: EU Publications.  
Fenton, N. and Neil, M. (2021) *Risk Assessment and Decision Analysis with Bayesian Networks* (2nd edn). CRC Press.  
Fraser, J.R.S., Quail, R. and Simkins, B. (2021) *Enterprise Risk Management*. Springer.  
Gartner (2024) *Hype Cycle for Cyber and IT Risk Management 2024*. Stamford: Gartner Inc.  
IBM Security (2024) *Cost of a Data Breach Report 2024*. Armonk, NY: IBM.  
ISO (2022) *ISO/IEC 27001:2022 — Information Security, Cybersecurity and Privacy Protection*. Geneva: ISO.  
ISO (2019, reaffirmed 2023) *ISO 22301:2019 — Security and Resilience: Business Continuity Management Systems* (with 2023 guidance). Geneva: ISO.  
Microsoft (2022) *Zero Trust Maturity Model 2.0*. Redmond, WA: Microsoft.  
NIST (2020) *SP 800-53 Rev. 5 — Security and Privacy Controls for Information Systems and Organizations*. Gaithersburg, MD: NIST.  
NIST (2023) *SP 800-34 Rev. 2 — Contingency Planning Guide for Federal Information Systems*. Gaithersburg, MD: NIST.  
NIST (2024) *AI Risk Management Framework 1.0 (2024 updates)*. Gaithersburg, MD: NIST.  
Olsen, T.L. and Desheng, D.W. (2020) *Research Methods and Applications in Quantitative Risk Management*. Springer.  
Popov, G., Lyon, B. and Hollcroft, B. (2022) *Risk Assessment*. CRC Press.  
Renn, O., Beier, G. and Schweizer, P.-J. (2021) ‘Opportunities and risks of digitalisation for sustainable development’, *GAIA*, 30(1), pp. 23–28.  
Verizon (2025) *Data Breach Investigations Report*. New York: Verizon Business.  
Wang, J., Neil, M. and Fenton, N. (2020) ‘A Bayesian network approach for cybersecurity risk assessment’, *Computers & Security*, 89, p. 101659.  
Zografopoulos, I. et al. (2021) ‘Cyber-physical energy systems security: threat modelling and metrics’, *IEEE Access*, 9, pp. 29775–29818.

---

[🏠 Home](./) | [📘 E-Portfolio](./e-portfolio) | [🔗 GitHub Repository](https://github.com/ketanmone/ketanmone.github.io)
