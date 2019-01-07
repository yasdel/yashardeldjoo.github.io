---
title: "Movie Genome: Alleviating New Item Cold Start in Movie Recommendation"
collection: publications
permalink: /publication/UMUAI19
date: 2019-01-01
venue: 'User Modeling and User-Adapted Interaction (UMUAI) - The Journal of Personalization Research'
citation: '<b>Yashar Deldjoo</b>, Maurizio Ferrari Dacrema, Mihai Gabriel Constantin, Hamid Eghbal-Zadeh, Stefano Cereda, Markus Schedl, Bogdan Ionescu, Paolo Cremonesi <i>User Modeling and User-Adapted Interaction (UMUAI), 2019</i>.'

---


## Abstract

As of today, most movie recommendation services base their recommendations on collaborative filtering (CF) and/or content-based filtering (CBF) models that use metadata (e.g., genre or cast). In most video-on-demand and streaming services, however, new movies and TV series are continuously added. CF models are unable to make predictions in such a scenario, since the newly added videos lack interactions -- a problem technically known as new item cold start (CS). Currently, the most common approach to this problem is to switch to a purely CBF method, usually by exploiting textual metadata. This approach is known to have lower accuracy than CF because it ignores useful collaborative information and relies on human-generated textual metadata, which are expensive to collect and often prone to errors. User-generated content, such as tags, can also be rare or absent in CS situations. In this paper, we introduce a new movie recommender system that addresses the new item problem in the movie domain by (i) integrating state-of-the-art audio and visual descriptors, which can be automatically extracted from video content and constitute what we call the <i>movie genome</i>; (ii) exploiting an effective data fusion method named <i>canonical correlation analysis</i> (CCA), which was successfully tested in our previous works, to better exploit complementary information between different modalities; (iii) proposing a two-step hybrid approach which trains a CF model on warm items (items with interactions) and leverages the learned model on the movie genome to recommend cold items (items without interactions). Experimental validation is carried out using a system-centric study on a large-scale, real-world movie recommendation dataset both in an absolute cold start and in a cold to warm transition; and a user-centric online experiment measuring different subjective aspects, such as satisfaction and diversity. Results show the benefits of this approach compared to existing approaches.
