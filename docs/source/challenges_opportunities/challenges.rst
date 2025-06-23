=================================
Challenges
=================================

Proprietary Multimodal Financial Data
=================================

Proprietary data is important for financial analysis and decision-making because it provides unique insights (BloombergGPT - Proprietary data):

- **Internal trading data:** The financial institutions have the capability to track and analyze their transaction data, offering insights into behavioral patterns and market trends.
- **Credit scoring data:** Financial entities possess data regarding the credit histories of individuals and corporations, which is essential for risk management.
- **Market research data:** Data gathered through specialized market research or customer feedback can aid financial firms in understanding consumer demands and market dynamics.
- **Real-time streaming data:** Certain institutions have access to real-time transaction flow data, which significantly facilitates algorithmic trading.
- **Private financial reports:** Some companies may have access to confidential financial information about partners or potential investment targets.
- **Proprietary economic indicators:** Large institutions may develop their own macroeconomic or microeconomic indicators based on exclusive datasets and analyses.
- **Alternative data:** This includes satellite imagery, mobile app data, and social media activities, which can provide additional perspectives and information for investment decisions.


Ethical Challenges
=================================

There are intensified ethical concerns with MFFMs. Mishandling sensitive information and thus making unfair, biased judgments can be disastrous to financial institutions. Analysts who trust flawed MFFMs will make bad investment decisions and improper risk assessments. Small missteps can cause significant client dissatisfaction and negative media attention. 

**Persistent ethical issues include:**
- **Security and privacy:** It is vital that FinLLMs have airtight security to prevent leakage of sensitive information. Example: Samsung employees accidentally leaked company secrets when prompting ChatGPT for help.
- **Copyright infringement:** FinLLMs trained on Internet data are not allowed to output copyrighted data to end users. Example: The New York Times sued OpenAI and Microsoft for using millions of its articles; Perplexity was accused of using articles from The Wall Street Journal or The New York Post to populate its RAG database and generate responses to user queries.
- **Systematic bias:** In decision-making processes, FinLLMs’ systematic bias may lead to unfair discrimination towards certain racial groups. According to Zillow and Consumer Reports, LLMs may quote African Americans at higher prices in home mortgages and car insurance due to historical segregation towards disaster-prone areas.
- **Transparency, explainability, and accountability:** It is important to ensure that FinLLMs are transparent, explainable, and accountable, providing clear responses, especially in finance where every decision has significant implications. J.P. Morgan Chase established its firmwide Explainable AI Center of Excellence (XAI COE) for research on explainability and fairness in finance.

**Newly-emerging ethical issues include:**
- **Truthfulness:** LLMs consistently hallucinate, creating false statements. In business and finance, hallucinations are problematic because LLMs’ output must exactly match information extracted from earnings reports when queried. Microsoft faced backlash when Bing AI hallucinated when analyzing Gap and Lululemon’s earnings reports during a demo.
- **Sycophancy:** LLMs demonstrate sycophancy, catering their outputs to match user beliefs rather than being truthful. Sycophancy is problematic when it causes inaccurate confirmation of financial analysts' and accountants’ math.
- **Compliance with professional norms:** LLM responses must follow professional norms to avoid implicit toxicity in training data. This is vital to preserve company culture and public relations.
- **Law and regulatory compliance:** FinLLMs must comply with current financial laws and regulations when making decisions and chatting with end users. According to the Consumer Financial Protection Bureau, FinLLMs must comply with regulations in operations like fraud detection, citing concerns like discrimination against minority racial groups.

Misinformation and Hallucination
=================================
In the financial domain, the accuracy of information is important for the integrity of market operations, risk management, compliance, and financial decisions. There are two sources of inaccurate financial information: dissemination of misinformation and hallucination from the model's output. 

Misinformation is from various media channels and the misuse of LLMs to generate misinformation. Detecting financial misinformation is a challenge. To address this issue, FMDLlama fine-tuned the LLaMA-3 model on the Fin-Fact dataset to detect financial misinformation. This case presents a feasible solution. By leveraging LLMs, an agentic framework can be developed to detect dynamically evolving financial misinformation.

Hallucination is factually incorrect output from LLMs due to their training on vast and diverse datasets. Ensuring the accuracy and reliability of LLM-generated outputs is crucial for their application in the financial industry. FMDLlama quantified financial hallucinations and explored several potential solutions to mitigate them, including few-shot learning, decoding by contrasting layers, and RAG.