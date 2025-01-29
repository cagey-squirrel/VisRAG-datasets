<h1>VisRAG Datasets</h1>
This repo contains data used for testing in the [VisRAG Paper](https://arxiv.org/pdf/2410.10594). <br>
Datasets used in the paper are publicly available, however actually getting them can be tricky. <br>
On top of that, authors of VisRAG paper applied filtering to both corpus (images used from the test/validation set) and queries (questions from test/validation set). <br>
<br>
Furthermore, this repo will also contain text extracted from each image in the corpus, mainly using GPT4o-mini on images or by extracting text from metadata if dataset contains it. <br>
Initial plan is to cover smaller datasets: ChartQA, InfographicsVQA, SlideQA and MP-Doc-VQA. For each dataset a corpus of images will be provided together with text extracted from each image. For quetions, a list will be provided of (question, answer, docid) tuples, where docid is the id of the image(s) where answer can be found. 

