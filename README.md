# GPSm - Graph-Based Privacy-Preserving Representation Learning Framework for Social Media Data

Abstract: The widespread use of social media data in be-
havioral and societal studies, such as analyzing online opinion
mining, has raised critical privacy concerns. These datasets often
contain sensitive attributes, such as age, gender, and political
views, which are relevant for research but pose risks to individual
privacy and infringe human being rights. Balancing the need for
data sharing with privacy protection is a noteworthy challenge,
especially under more strict data privacy regulations. Aiming to
tackle this research and industrial gap, we introduce in this paper
a Graph-Based Privacy-Preserving for Social Media (GPSm), a
novel method developed to protect sensitive information while
preserving the utility of textual data for downstream tasks. GPSm
employs a two-stage privacy-preserving representation learning
approach: (1) Text-Level Representation, which identifies and
suppresses both explicit and implicit sensitive attributes through
privacy-aware training, and (2) Graph-Based Representation,
which preserves the relational and contextual structure of social
media posts. Besides, we propose an Implicit Feature Extraction
Method to detect features that may serve as proxies for those
directly associated with private information. Experimental results
on a Reddit dataset demonstrate that GPSm effectively reduces
the risk of privacy breaches, even in scenarios with many
implicit features. Our proposal overcome the current limita-
tions of existing anonymization strategies and privacy-preserving
representation learning techniques regarding preserving utility
without compromising individual privacy, thereby helping to
regularize systems in the light of increasingly strict regulations.
