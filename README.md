# Transformer-Text-Summarization

This file contains evaluates the Facebook transformer (BART) and Google Transformer (PEGASUS) on its summarization capabilities. I first download and evaluate the transformers on the CNN/DailyMail dataset which consists of articles and their corresponding summaries. Pegasus (which was trained on the CNN/DailyMail Dataset) performed much closer to the ground truth, while it seems BART has a slightly different summarization style. BART summarizes text with complete sentences as opposed to PEGASUS's bullet point style.

After running this test, I downloaded the SAMSUNG dialog dataset to fine tuned PEGASUS and evaluate its abilities on a dataset it was not trained on. After training for over 40 minutes it performed will with coherent summarization and did not just extract single sentences.
