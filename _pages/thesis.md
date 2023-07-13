---
layout: archive
title: "Thesis"
permalink: /thesis/
author_profile: true
redirect_from:
  - /thesis
  - /thesis
---

{% include base_path %}

## A Method for Adapting Large Language Models for Communication Card Prediction in Augmentative and Alternative Communication Systems

Defesa de Doutorado - Jayr A. Pereira<br>
Terça-feira, 18 de julho · 1:00 até 5:00pm<br>
Fuso horário: America/Fortaleza<br>
Como participar do Google Meet<br>
Link da videochamada: [https://meet.google.com/zuf-ujui-pbh](https://meet.google.com/zuf-ujui-pbh)

[Add to Google Calendar](https://www.google.com/calendar/render?action=TEMPLATE&text=Defesa+de+Doutorado+-+Jayr+A.+Pereira&details=Defesa+de+Doutorado+-+Jayr+A.+Pereira%0ATer%C3%A7a-feira%2C+18+de+julho+%C2%B7+1%3A00+at%C3%A9+5%3A00pm%0AFuso+hor%C3%A1rio%3A+America%2FFortaleza%0AComo+participar+do+Google+Meet%0ALink+da+videochamada%3A+https%3A%2F%2Fmeet.google.com%2Fzuf-ujui-pbh&location=https%3A%2F%2Fmeet.google.com%2Fzuf-ujui-pbh&dates=20230718T160000Z%2F20230718T200000Z)


### Abstract

Augmentative and Alternative Communication (AAC) systems assist individuals with complex communication needs to express themselves. Communication cards are a popular method used in AAC, where users select cards and arrange them in sequence to form a sentence. However, the limited number of cards displayed and the need to navigate multiple pages or folders can hinder users' communication ability. To overcome these barriers, various methods, such as vocabulary organization, color coding systems, motor planning, and predictive models, have been proposed to aid message authoring. Recent advancements in Artificial Intelligence (AI) and Machine Learning (ML) have shown potential for improving the accessibility and customization of AAC systems. This study proposes adapting large language models to communication card prediction in AAC systems to facilitate message authoring. The proposed method involves three main steps: 1) adapting a text corpus to the AAC domain by either converting it into a corpus of telegraphic sentences or incorporating features that enable the exploration of visual cues; 2) fine-tuning a transformer-based language model using the adapted corpus; and 3) replacing the language model decoder weights with an encoded representation of the user's vocabulary to generate a probability distribution over the user's vocabulary items during inference. The proposed method leverages that transformers-based language models, such as Bidirectional Encoder Representations from Transformers (BERT), share the weights of the input embeddings layer with the decoder in the language modeling head. Therefore, the plug-and-play method can be used without additional training for zero-shot communication card prediction. The method was evaluated in English and Brazilian Portuguese using a zero-shot setting and a few-shot setting, where a small text corpus was used for fine-tuning. Additionally, the impact of incorporating additional features into the training sentences by labeling them with the Colourful Semantics structure was assessed. The results demonstrate that the proposed method's models outperform models pre-trained for the task. Moreover, the results indicate that incorporating Colourful Semantics improves the accuracy of communication card prediction. Thus, the proposed method utilizes the transfer learning ability of transformers-based language models to facilitate message authoring in AAC systems in a low-effort setting. 


### Keywords
ugmentative and Alternative Communication. Message authoring. Sentence construction. Pictogram prediction. Colourful Semantics