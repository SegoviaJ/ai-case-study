# Case Study: Robust Intelligence

## Overview and Origin

**Name of the Company:** Robust Intelligence

**Incorporation Date:** 2019

**Founders:**

- **Yaron Singer** – Co-founder and CEO, Professor of Computer Science at Harvard University.
- **Kojin Oshiba** – Co-founder and Chief Scientist.

**Origin of the Idea:**
> **"Security leaders need purpose-built solutions they can trust to keep up with the new paradigm of AI risk."**
> — Yaron Singer, Co-founder and CEO of Robust Intelligence (Gills, 2024)

Robust Intelligence was co-founded by Professor Yaron Singer and Kojin Oshiba in 2019 after years of machine learning research at Harvard University. The pair realized a significant gap between the state of AI and its practical use by data scientists. Determined to solve the chronic problem of AI security, they developed the industry's first AI Firewall (Robust Intelligence, n.d.-a).

Since its inception, the company has attracted exceptional talent working at the forefront of AI and cybersecurity from leading tech companies such as Amazon, Google, Meta, Microsoft, and more. This diverse and experienced team has created the industry's first end-to-end platform for AI application security, trusted by security and data science leaders worldwide (Robust Intelligence, n.d.-a).

**Acquisition by Cisco:**

On **September 24, 2024**, Cisco Systems announced the completion of its acquisition of Robust Intelligence for an estimated **$350 million**. This acquisition aims to enhance Cisco's Security Cloud capabilities by integrating Robust Intelligence's AI model validation and protection solutions into Cisco's networking and security products. With the integration, Cisco hopes to have "unparalleled visibility into all of a customer’s AI traffic" that will allow customers to secure their network, AI applications, and users while adhering to industry and regulatory standards like OWASP and MITRE ATLAS (Gills, 2024; Crawford, 2024).

**Funding:**

Prior to the acquisition, Robust Intelligence had raised approximately **$44 million** including a **$30 million Series B** round led by Tiger Global Management, with participation from Sequoia Capital, Harpoon Ventures, and Engineering Capital (Lardinois, 2022).

## Business Activities

**Problem Addressed:**

AI models are susceptible to failures when exposed to adversarial inputs, data corruption, or shifts in data distribution. These vulnerabilities can lead to incorrect predictions and pose significant risks in critical applications. Robust Intelligence aimed to proactively identify and mitigate these issues, ensuring that AI models are secure and reliable before deployment.

**Intended Customers and Market Size:**

Robust Intelligence targeted enterprises deploying AI models in critical and sensitive applications, including:

- **Technology:** Protecting models used to build AI applications.
- **Financial Services:** Fraud detection, risk projection, algorithmic trading, and customer service.
- **Insurance:** Predictive risk modeling and claims processing.
- **Government & Defense:** Numerous use cases from education and healthcare to military and defense. (Robust Intelligence, n.d.-e)

According to Fortune Business Insights (2024), the global AI market size was valued at **$515.31 billion in 2023** and is projected to reach **$2740.46 billion by 2032**, growing at a CAGR of 20.4%. The global AI in cybersecurity market is also expanding, expected to reach **$60.60 billion by 2028** (MarketsandMarkets, 2024), indicating a substantial market for AI security solutions in networking applications.

**Unique Solution Offered:**

> **"Our approach to detecting vulnerabilities and protecting AI applications is based on proprietary technology developed over the past decade by our founding team."**
> — Robust Intelligence (Robust Intelligence, n.d.-a)

Robust Intelligence provided an **end-to-end AI model validation and protection platform** that integrated into the AI development workflow. Key technologies and innovations include:

- **AI Risk Database:** A comprehensive repository of known AI vulnerabilities and risks, allowing organizations to anticipate and mitigate potential issues.
- **Algorithmic Red Teaming:** Systematic stress testing to uncover model vulnerabilities using proprietary technology developed over a decade.
- **Threat Intelligence Feed:** Prompt injection, jailbreaks, in-the-wild and adversarial techniques gathered from open and closed sources.
- **AI Firewall:** Provides guardrails against issues identified during validation, ensuring models remain secure during production. (Robust Intelligence, n.d.-c)
- **RIME:** The RI Model Engine (RIME) performs stress-testing on models before they go into production in order to see if any errors or biases exist within the model. Once deployed, RIME continuously tests the model to ensure none arise. (Robust Intelligence, n.d.-d)


## Landscape

**Field of the Company:**

Robust Intelligence operates in the **AI security and reliability** space. The company focuses on improving the dependability and security of AI models against adversarial threats and data anomalies, crucial in industries where data integrity and security are of the utmost importance.

## Trends and Innovations in AI Security:
1. **Advancements in Adversarial Defenses:**
   Improved techniques like adversarial training to protect AI models from adversarial attacks. (Akhtar et al., 2021)

2. **Federated Learning:**
   Implementation of decentralized learning structure to enhance data privacy and security during AI model training. (Prieto, 2023)

3. **Differential Privacy:**
   Protects sensitive personal data by differentiating it from general information in AI systems. (Nguyen, 2023)

4. **Explainable AI (XAI):**
   Work to create human-interpretable models with meaningful output that can be understood and trusted. (Ali et al., 2023)

5. **AI Model Watermarking:**
   Maintaining content authenticity and reliability by embedding watermarks into AI content. (Luccioni et al, 2024)


**Major Competitors in the Field:**

Robust Intelligence faced competition from several startups and established companies specializing in AI security and reliability. Notable competitors include:

- **Protect AI:** https://protectai.com/
- **HiddenLayer:** https://hiddenlayer.com/
- **Aporia:** https://www.aporia.com/
- **Arthur AI:** https://www.arthur.ai/product/shield
- **AIShield:** https://www.boschaishield.com/

While major technology vendors like IBM, Microsoft, and Google are heavily investing in AI, their focus has primarily been on "AI for security," using AI to enhance their security products. In contrast, Robust Intelligence and its competitors are centered on "security for AI," providing solutions to protect AI models themselves (Crawford, 2024).


## Results

**Business Impact:**

- **Client Success:** Assisted enterprises in enhancing the security of their AI models, leading to reduced failure rates.
- **Industry Recognition:** Recognized for innovative solutions in AI security, contributing to Cisco's decision to acquire the company.
- **Strategic Acquisition:** The acquisition by Cisco is set to strengthen Cisco's security portfolio, embedding Robust Intelligence's technology into Cisco's products to enhance AI trustworthiness in enterprise contexts (Gills, 2024).

**Performance Relative to Competitors:**

Robust Intelligence's comprehensive, proactive approach to enhancing AI security positioned them favorably against competitors. Their focus on pre-deployment validation and continuous protection provided a unique value proposition, especially for companies seeking to secure their AI-driven systems.

## Recommendations

**Suggested Products/Services:**

1. **Provide a Vendor Agnostic Product:**

   - **Description:** Alow the Cisco Security Cloud / Robust Intelligence's AI security to be implemented across hardware from any network equipment vendor via containerization/translation, similar to Cisco NSO.
   - **Benefits:** This would increase adoption rates by making the product appealing to multi-vendor enterprises.

2. **Continue Development of Industry-Specific AI Security Solutions:**

   - **Description:** Continue offering specialized AI security solutions tailored for industries like finance, healthcare, and manufacturing.
   - **Benefits:** Addresses the unique challenges of securing AI models in various sectors, expanding market reach.

**Technologies to Utilize:**

- **Industry-specific Adversarial Testing:** Develop testing processes unique to different industries.
- **Integration APIs and SDKs:** Create interfaces for seamless integration with Cisco's existing platforms.
- **Standard Networking Protocols:** Ensure compatibility across vendors via NETCONF, SNMP, etc.
- **Edge Computing Security:** Secure AI models deployed on edge devices and IoT networks.

**Why These Technologies Are Appropriate:**

They align with Cisco's focus on networking and enterprise solutions, improving the security of AI models within their product ecosystem. Utilizing these technologies can help ensure AI models across various applications are secure, reliable, and protected against threats.

---

**References**

Gills, T. (2024, September 24). *Fortifying the Future of Security for AI: Cisco Announces Intent to Acquire Robust Intelligence*. Retrieved from [https://blogs.cisco.com/security/fortifying-the-future-of-security-for-ai](https://blogs.cisco.com/security/fortifying-the-future-of-security-for-ai)

Crawford, S. (2024, August 27). *Securing the AI-driven enterprise: Cisco acquires security for AI with Robust Intelligence*. 451 Research. Retrieved from [https://newsroom.cisco.com/c/dam/r/newsroom/en/us/assets/a/y2024/m08/Cisco-Acquires-Robust-Intelligence.pdf](https://newsroom.cisco.com/c/dam/r/newsroom/en/us/assets/a/y2024/m08/Cisco-Acquires-Robust-Intelligence.pdf)

Fortune Business Insights. (2021). *Artificial Intelligence Market Size, Share, Growth*. Retrieved from [https://www.fortunebusinessinsights.com/industry-reports/artificial-intelligence-market-100114](https://www.fortunebusinessinsights.com/industry-reports/artificial-intelligence-market-100114)

Lardinois, F. (2021, December 9). *Robust Intelligence raises $30M Series B to stress test AI models*. *TechCrunch*. Retrieved from [https://techcrunch.com/2021/12/09/robust-intelligence-raises-30m-series-b-to-stress-test-ai-models/](https://techcrunch.com/2021/12/09/robust-intelligence-raises-30m-series-b-to-stress-test-ai-models/)

MarketsandMarkets. (2021). *Artificial Intelligence in Cybersecurity Market by Security Type - Global Forecast to 2028*. Retrieved from [https://www.marketsandmarkets.com/Market-Reports/artificial-intelligence-ai-cyber-security-market-220634996.html](https://www.marketsandmarkets.com/Market-Reports/artificial-intelligence-ai-cyber-security-market-220634996.html)

Robust Intelligence. (n.d.-a). *About Us*. Retrieved from [https://www.robustintelligence.com/company/about](https://www.robustintelligence.com/company/about)

Robust Intelligence. (n.d.-b). *AI Risk Management*. Retrieved from [https://www.robustintelligence.com/ai-risk-management](https://www.robustintelligence.com/ai-risk-management)

Robust Intelligence. (n.d.-c). *AI Firewall*. Retrieved from [https://www.robustintelligence.com/platform/ai-firewall-guardrails](https://www.robustintelligence.com/platform/ai-firewall-guardrails)

Robust Intelligence. (n.d.-d). *Why Model Validation Can End the AI “Explainability Crisis"*. Retrieved from [https://www.robustintelligence.com/blog-posts/why-model-validation-can-end-the-ai-explainability-crisis](https://www.robustintelligence.com/blog-posts/why-model-validation-can-end-the-ai-explainability-crisis)

Robust Intelligence. (n.d.-e). *Solutions By Industry*. Retrieved from [https://www.robustintelligence.com/solutions/by-industry](https://www.robustintelligence.com/solutions/by-industry)

SecurityWeek. (2024, August 29). *Cisco to Acquire AI Security Firm Robust Intelligence*. Retrieved from [https://www.securityweek.com/cisco-to-acquire-ai-security-firm-robust-intelligence/](https://www.securityweek.com/cisco-to-acquire-ai-security-firm-robust-intelligence/)

Akhtar, N., Mian, A., Kardan, N., & Shah, M. (2021). *Advances in Adversarial Attacks and Defenses in Computer Vision: A Survey*. *IEEE Access*. Retrieved from [https://ieeexplore.ieee.org/document/9462466](https://ieeexplore.ieee.org/document/9462466)

Prieto, J.-T. (2023). *Federated learning trends: From academic insights to industry applications*. *Apheris Blog*. Retrieved from [https://www.apheris.com/resources/blog/federated-learning-from-academic-insights-to-industry-applications](https://www.apheris.com/resources/blog/federated-learning-from-academic-insights-to-industry-applications)

Nguyen, A. (2023). **Understanding Differential Privacy**. *Towards Data Science*. Retrieved from [https://towardsdatascience.com/understanding-differential-privacy-85ce191e198a](https://towardsdatascience.com/understanding-differential-privacy-85ce191e198a)

Ali, S., Abuhmed, T., El-Sappagh, S., Muhammad, K., Alonso-Moral, J. M., Confalonieri, R., Guidotti, R., Del Ser, J., Díaz-Rodríguez, N., & Herrera, F. (2023). **Explainable Artificial Intelligence (XAI): What we know and what is left to attain Trustworthy Artificial Intelligence**. *Information Fusion, 99*, 101805. [https://www.sciencedirect.com/science/article/pii/S1566253523001148](https://www.sciencedirect.com/science/article/pii/S1566253523001148)

Luccioni, S., Jernite, Y., Thomas, D., Witko, E., Ozoani, E., Fukano, J., Srivastav, V., Tousignant, B., & Mitchell, M. (2024, February 26). **AI Watermarking 101: Tools and Techniques**. *Hugging Face Blog*. Retrieved from [https://huggingface.co/blog/watermarking](https://huggingface.co/blog/watermarking)

