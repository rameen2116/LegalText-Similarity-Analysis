# LegalText-Similarity-Analysis
The task of Legal Clause Similarity involves determining whether two legal clauses convey the same or closely related legal meaning, even if phrased differently. This is a crucial problem in legal NLP, enabling applications such as contract analysis, case law retrieval, and legal document comparison. The complexity arises from the formal and nuanced language used in legal documents, requiring models to capture not only lexical similarity but also contextual and semantic equivalence.
 we explore two baseline NLP architectures for the task:
BiLSTM Model: A bidirectional LSTM network that captures sequential dependencies between words in clauses.
Attention-based Encoder: Enhances the BiLSTM by applying an attention mechanism, allowing the model to focus on important words in each clause and better capture semantic relationships.

