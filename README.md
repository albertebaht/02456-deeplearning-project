# 02456-deeplearning-project
Deep learning project about constructing knowledge graphs (KGs) with language models. 

The data consists of scientific papers from arXiv. It has been exstracted using "arxivSTAT.ipynb". The final dataset was narrowed down to 11 papers see [1–11] in **References**. 

- "promptbased.ipynb" constructs knowledge graphs (KGs) using the Neo4j graph database platform, with the structure of the KG inspired by the work in [12].
- The "entity_resolution.ipynb" notebook performs entity resolution on an KG, following the approach outlined in [13].
- "rag_evaluation.ipynb" builds a retrieval-augmented generation (RAG) application using an KG, with the implementation based on techniques outlined in [14] and [15].

These three files are combined in "main.ipynb".


## References
1. Tatiane F. N. Melo, Silvia L. P. Ferrari, *"Adjusted likelihood inference in an elliptical multivariate errors-in-variables model"*, 2011, [https://doi.org/10.48550/arXiv.1108.1098](https://doi.org/10.48550/arXiv.1108.1098).

2. A. Ramdas, B. Poczos, A. Singh, L. Wasserman, *"An Analysis of Active Learning With Uniform Feature Noise"*, 2015, [https://doi.org/10.48550/arXiv.1505.04215](https://doi.org/10.48550/arXiv.1505.04215).

3. R. G. Patel, I. Manickam, M. Lee, M. Gulian, *"Error-in-variables modelling for operator learning"*, 2022, [https://doi.org/10.48550/arXiv.2204.10909](https://doi.org/10.48550/arXiv.2204.10909).

4. V. Dragović, B. Gajić, *"Orthogonal and Linear Regressions and Pencils of Confocal Quadrics"*, 2024, [https://doi.org/10.48550/arXiv.2209.01679](https://doi.org/10.48550/arXiv.2209.01679).

5. L. Nghiem, M. Byrd, C. Potgieter, *"Estimation in linear errors-in-variables models with unknown error distribution"*, 2018, [https://doi.org/10.48550/arXiv.1812.00492](https://doi.org/10.48550/arXiv.1812.00492).

6. H. Han, W. Zhu, *"RCR: Robust Compound Regression for Robust Estimation of Errors-in-Variables Model"*, 2015, [https://doi.org/10.48550/arXiv.1508.02925](https://doi.org/10.48550/arXiv.1508.02925).

7. M. Konstantinou, H. Dette, *"Bayesian D-optimal designs for error-in-variables models"*, 2016, [https://doi.org/10.48550/arXiv.1605.04055](https://doi.org/10.48550/arXiv.1605.04055).

8. T. Barry, K. Roeder, E. Katsevich, *"Exponential family measurement error models for single-cell CRISPR screens"*, 2024, [https://doi.org/10.48550/arXiv.2201.01879](https://doi.org/10.48550/arXiv.2201.01879).

9. E.A.K. Cohen, D. Kim, R.J. Ober, *"Cramer-Rao Lower Bound for Point Based Image Registration with Heteroscedastic Error Model for Application in Single Molecule Microscopy"*, 2015, [https://doi.org/10.48550/arXiv.1504.05781](https://doi.org/10.48550/arXiv.1504.05781).

10. M. Rudelson, S. Zhou, *"High dimensional errors-in-variables models with dependent measurements"*, 2015, [https://doi.org/10.48550/arXiv.1502.02355](https://doi.org/10.48550/arXiv.1502.02355).

11. M. Rudelson, S. Zhou, *"Errors-in-variables models with dependent measurements"*, 2017, [https://doi.org/10.48550/arXiv.1611.04701](https://doi.org/10.48550/arXiv.1611.04701).

12. T. Bratanic, *"Implementing GraphReader with Neo4j and
LangGraph"*, 2024 [https://github.com/tomasonjo/blogs/blob/master/graphreader/graphreader_langgraph.ipynb](https://github.com/tomasonjo/blogs/blob/master/graphreader/graphreader_langgraph.ipynb), Accessed Dec. 9 2024.

13. T. Bratanic, *"Implementing ‘From Local to Global’
GraphRAG with Neo4j and LangChain: Constructing the
Graph"*, 2024, [https://medium.com/neo4j/implementing-from-local-to-global-graphrag-with-neo4j-and-langchain-constructing-the-graph-73924cc5bab4](https://medium.com/neo4j/implementing-from-local-to-global-graphrag-with-neo4j-and-langchain-constructing-the-graph-73924cc5bab4),  Accessed: Dec. 7 2024.

14. T. Bratanic, *"Using a Knowledge Graph to Implement a RAG Application"*, 2024, [https://neo4j.com/developer-blog/knowledge-graph-rag-application/](https://neo4j.com/developer-blog/knowledge-graph-rag-application/),  Accessed: Dec. 18 2024.

15. P. Muthozu, *"Demystifying Natural Language to Cypher Conversion with OpenAI, Neo4j, LangChain, and LangSmit"*, 2024[https://medium.com/@muthoju.pavan/demystifying-natural-language-to-cypher-conversion-with-openai-neo4j-langchain-and-langsmith-2dbecb1e2ce9](https://medium.com/@muthoju.pavan/demystifying-natural-language-to-cypher-conversion-with-openai-neo4j-langchain-and-langsmith-2dbecb1e2ce9),  Accessed: Dec. 19 2024.

