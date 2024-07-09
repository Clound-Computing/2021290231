# Do Androids Laugh at Electric Sheep? Humor "Understanding" Benchmarks from The New Yorker Caption Contest

关于Matching任务的例子展示:
```
{'caption_choices': ['Tell me about your childhood very quickly.',
                     "Believe me . . . it's what's UNDER the ground that's "
                     'most interesting.',
                     "Stop me if you've heard this one.",
                     'I have trouble saying no.',
                     'Yes, I see the train but I think we can beat it.'],
 'contest_number': 49,
 'entities': ['https://en.wikipedia.org/wiki/Rule_of_three_(writing)',
              'https://en.wikipedia.org/wiki/Bar_joke',
              'https://en.wikipedia.org/wiki/Religious_institute'],
 'from_description': 'scene: a bar description: Two priests and a rabbi are '
                     'walking into a bar, as the bartender and another patron '
                     'look on. The bartender talks on the phone while looking '
                     'skeptically at the incoming crew. uncanny: The scene '
                     'depicts a very stereotypical "bar joke" that would be '
                     'unlikely to be encountered in real life; the skepticism '
                     'of the bartender suggests that he is aware he is seeing '
                     'this trope, and is explaining it to someone on the '
                     'phone. entities: Rule_of_three_(writing), Bar_joke, '
                     'Religious_institute. choices A: Tell me about your '
                     "childhood very quickly. B: Believe me . . . it's what's "
                     "UNDER the ground that's most interesting. C: Stop me if "
                     "you've heard this one. D: I have trouble saying no. E: "
                     'Yes, I see the train but I think we can beat it.',
 'image': <PIL.JpegImagePlugin.JpegImageFile image mode=L size=323x231 at 0x7F34F283E9D0>,
 'image_description': 'Two priests and a rabbi are walking into a bar, as the '
                      'bartender and another patron look on. The bartender '
                      'talks on the phone while looking skeptically at the '
                      'incoming crew.',
 'image_location': 'a bar',
 'image_uncanny_description': 'The scene depicts a very stereotypical "bar '
                              'joke" that would be unlikely to be encountered '
                              'in real life; the skepticism of the bartender '
                              'suggests that he is aware he is seeing this '
                              'trope, and is explaining it to someone on the '
                              'phone.',
 'instance_id': '21125bb8787b4e7e82aa3b0a1cba1571',
 'label': 'C',
 'n_tokens_label': 1,
 'questions': ['What is the bartender saying on the phone in response to the '
               'living, breathing, stereotypical bar joke that is unfolding?']}
```



## 实验结果

<p align="center">
  <img src="https://github.com/jmhessel/caption_contest_corpus/assets/178075/585cee7f-7f06-4be4-bda5-c17be5e6b014" width=512>
</p>

在匹配任务中，研究期间最好的多模态模型（64%）的性能比人类（94%）低30个精度点；即使提供了真实的视觉场景描述，人类撰写的解释在超过2/3的任务表现中也要优于机器（基于GPT-4模型的few-shot多样本模板）。换言之，就本次研究表明，即使已经有像ChatGPT这类先进的人工智能模型不断进步并逐渐缩小差距，但在理解幽默这一方面，就目前来说，人类明显要优于人工智能。





