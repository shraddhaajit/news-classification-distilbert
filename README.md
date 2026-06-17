# News Topic Classification with DistilBERT

Fine-tuning DistilBERT on the AG News benchmark for 4-class news topic classification.

**Model:** distilbert-base-uncased  
**Dataset:** AG News (120,000 train / 7,600 test)  
**Result:** ~94.7% accuracy · 0.947 macro F1  

Full pipeline: EDA → tokenization → fine-tuning → evaluation → attention interpretability.
