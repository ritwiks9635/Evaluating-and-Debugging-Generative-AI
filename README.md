# Evaluating-and-Debugging-Generative-AI

[Complete](https://learn.deeplearning.ai/accomplishments/30f3a630-4ca8-4386-9ffe-e6453f770a98?usp=sharing)

![](https://d3f1iyfxxz8i1e.cloudfront.net/courses/course_image/0504682be405.png)

In the generative AI evaluation service, you can use computation-based metrics through the Pipeline and rapid evaluation Python SDK. The computation-based evaluation might be performed in only pointwise use cases. However, you can directly compare the metrics scores of two models for a pairwise comparison.

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTQfb_tj3hk5NI1ySZ1iI4YZFJEKsNqe_Pfqw&usqp=CAU)

Generative AI evaluation can be used to assess the performance of a model in a variety of scenarios, such as selecting a pretrained model or optimizing model generation settings. Here are some ways to evaluate generative AI:
Create an evaluation dataset
Create a dataset that contains prompt and ground truth pairs, where the prompt is the input and the ground truth is the ideal response. During evaluation, pass each prompt to the model to produce an output, and then compare the output to the ground truth to compute evaluation metrics.
Use evaluation notebooks
Use a rapid evaluation service to evaluate models in real time. For example, you can use the rapid evaluation SDK to evaluate the effect of prompt engineering by examining statistics for each prompt template.
Consider relevant metrics
When evaluating text generation, you can use metrics like BLEU, perplexity, and human evaluation. BLEU compares the generated text to human references and scores it from 1 to 100, with higher scores indicating better performance. Perplexity measures the model's uncertainty, with lower scores indicating better fluency. Human evaluation involves people assessing the quality, accuracy, and usefulness of the model's outputs.
