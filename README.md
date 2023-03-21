# ia368v_dd_class_04
IA368V DD 4th class: zero-shot and few-shot learning with Large Language Models.

For this task we used the [Conversational Question Answering Challenge (CoQA) dataset](https://stanfordnlp.github.io/coqa/) as the basis.

Some setups (few-shot/zero-shot, with/without prompt) were experimented applying the prompt engineering for both the LLaMA and OpenAI "text-davinci-003" LLMs. Here are the results:

|    | EM   | F1 | Selected queries |
|----|:---: |:---: |:---: |
| LLaMA zero shot<br />no prompt | 37.5 | 60.6 | 219, 352, 272, 132, 82 |
| LLaMA zero shot<br />and prompt | 26.2 | 47.3 | 219, 352, 272, 132, 82 |
| LLaMA few shot<br />no prompt | 41.2 | 63.6 | 219, 352, 272, 132, 82 |
| LLaMA few shot<br />and prompt | 45.9 | 64.3 | 219, 352, 272, 132, 82 |
| text-davinci-003<br />few sho and prompt | 15.0 | 48.7 | 219, 352, 272, 132, 82 |
| Human | 78.4 | 88.0 | 219, 352, 272, 132, 82 |
