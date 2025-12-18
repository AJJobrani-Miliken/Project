Baseline Assessment of Childhood Vaccination Delays in Washington, DC Using AI-Enhanced Data Science

This repository contains a complete, reproducible analysis of childhood vaccination delays among 383 pediatric patients receiving care at a Children’s National primary care clinic in Columbia Heights, Washington, DC. The dataset consists of de-identified electronic health record extracts indicating the number of days patients are overdue for Advisory Committee on Immunization Practices (ACIP)–recommended vaccines. Patient ages range from infancy through late adolescence. All personal identifiers have been removed in accordance with HIPAA and institutional quality-improvement standards.

The primary purpose of this project is to establish a rigorous clinic-level baseline of immunization timeliness and delay severity in an urban safety-net setting. While overall vaccination coverage metrics often obscure important patterns, this analysis treats vaccination status as a longitudinal process by quantifying the magnitude and distribution of overdue doses across vaccine series. The findings highlight substantial and frequently prolonged delays that have direct implications for outbreak risk, herd immunity, and equity in preventive care delivery.

The project is designed to support applied public health decision making rather than hypothesis testing. Descriptive epidemiology, distributional analysis, and visualization are used to identify which vaccine series contribute most to under-immunization, how delays cluster across patients, and where preventive care continuity breaks down. Loss to follow-up and care fragmentation appear to be key drivers of overdue vaccination in this population, underscoring the need for proactive, data-informed outreach strategies rather than encounter-based approaches alone.

All analyses are implemented in Python using Jupyter notebooks within Visual Studio Code. The analytic workflow emphasizes transparency and reproducibility and includes data cleaning, feature engineering, exploratory data analysis, severity stratification, and visualization. A lightweight machine-learning component is included to demonstrate how predictive analytics can be used responsibly to support case-management prioritization and quality-improvement planning, rather than high-stakes individual prediction.

The repository also includes static and interactive visualizations, as well as a prototype dashboard concept, intended to be accessible to clinicians, clinic administrators, and public health practitioners. These tools are designed to enhance situational awareness, support staffing and outreach decisions, and accelerate quality-improvement cycles aligned with clinic and district-level immunization targets.

This work illustrates the responsible integration of AI-assisted tools, including large language models and developer copilots, within a doctoral-level public health analytics workflow. Generative AI was used to support code development, documentation, and analytic iteration under human oversight, with all substantive analytic decisions grounded in public health expertise and established immunization guidelines.

Repository Contents

LiteratureReview.ipynb
Primary analysis notebook containing data preparation, exploratory analysis, visualizations, and methodological documentation.

figures_vax/
Static figures used in the Results section of the report, generated directly from the analytic pipeline.

README.md
Project overview, scope, and analytic framing.

Intended Audience

This repository is intended for public health researchers, quality-improvement teams, clinicians, health system administrators, and graduate-level students interested in applied immunization analytics, preventive care evaluation, and the responsible use of AI-supported data science in real-world healthcare settings.
