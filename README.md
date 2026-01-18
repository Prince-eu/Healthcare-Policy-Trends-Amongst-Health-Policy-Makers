#Healthcare Policy Trends Amongst Health Policy Makers (Center of Medicaid & Medicare Services)

##Description
This project applies text mining and natural language processing techniques to analyze CMS Open Door Forum (ODF) transcripts, a key communication channel between policymakers, healthcare providers, and stakeholders. Using a mix of exploratory and advanced NLP methods—including TF, TF-IDF, topic modeling (LDA), n-grams, dictionary-based classification, and sentiment analysis—the study uncovers dominant healthcare themes and policy concerns. The analysis focuses on three critical domains: Rural Health, Hospital Services, and Skilled Nursing & Long-Term Care. By transforming unstructured healthcare discussions into structured insights, the project provides evidence-based perspectives to support policymaking, operational decision-making, and healthcare system improvement.

##Project Goals
1. Identify the most frequently discussed healthcare topics across CMS Open Door Forum categories using text mining techniques
2. Compare and contrast thematic priorities across Rural Health, Hospital Services, and Skilled Nursing/Long-Term Care forums
3. Extract actionable insights for policymakers and healthcare providers by analyzing language patterns and sentiment trends


##Data Description
The dataset consists of 56 publicly available CMS Open Door Forum transcripts spanning 2020–2024, sourced from CMS podcast recordings and transcribed into text. The transcripts capture structured discussions among CMS officials, legislators, healthcare providers, and stakeholders. Each document follows a standardized format including opening remarks, policy discussions, regulatory clarifications, and stakeholder Q&A.

The analysis focuses on three randomly selected healthcare domains:
1. Rural Health
2. Hospital Services
3. Skilled Nursing Facilities/Long-Term Care

##Files in this Repository
- `data/` - The data used in this project comes from the Centers for Medicare & Medicaid Services (CMS) Open Door Forum (ODF). Specifically, it consists of publicly available podcast recordings and their official transcripts, published by CMS to facilitate dialogue between policymakers, healthcare providers, and other stakeholders.
	-Source:CMS Open Door Forum (ODF) transcripts and podcasts
	-Publisher: Centers for Medicare & Medicaid Services (CMS)
	-Format: Audio recordings transcribed into structured text documents
	-Time span: 2020–2024
	-Access: Publicly available via the CMS website
- `code/` - The analysis code for this project is implemented using both Python and R, reflecting a hybrid NLP workflow:
	-Python source files/notebooks: Used for TF-IDF, topic modeling (LDA), and n-gram analysis, leveraging libraries such as scikit-learn, Gensim, and NLTK.
	-R source file/scripts: Used for text preprocessing, term frequency analysis, dictionary-based classification, and sentiment analysis using tidytext and related R packages.

The code operates on preprocessed CMS Open Door Forum transcript text files and transforms unstructured text into structured analytical outputs (topic distributions, term weights, and sentiment scores).


##Key Findings
-The code operates on preprocessed CMS Open Door Forum transcript text files and transforms unstructured text into structured analytical outputs (topic distributions, term weights, and sentiment scores).
-Hospital forums were heavily focused on payment systems, reimbursement models, and regulatory proposals, accounting for over 60% of discussion topics.
-Rural Health forums emphasized care delivery challenges, access, and infrastructure limitations, reflecting equity and accessibility concerns.
-Skilled Nursing & Long-Term Care forums showed a strong focus on policy reviews, compliance, documentation, and information sharing, highlighting administrative complexity.
-Sentiment analysis revealed recurring negative language around regulation and compliance (e.g., “impose,” “penalty,” “risk”) and positive language emphasizing clarity, appreciation, and accuracy, suggesting both frustration with policy burden and appreciation for transparent communication.


