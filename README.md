# information_extraction
### Introduction
Information extraction includes five main tasks, which including named entity recognition(NER), coreference resolution, entity disambiguation, relation extraction and event extraction. In this project, I will mainly go through the basic method used in these 5 tasks. Hopefully, it will bring new NLPers a consist view of what the magic behind Information extraction is.

### Named entity recognition
Concept: if one want to find specific items from an unstructured text, then this task probably should be Named entity recognition. Named entity recognition(NER) is to extract person's name, location name, organisation name, time, date or other numerical text like '%' from unstructured text. For example:
    In sentence "China is a great country that has a population of more than 140 billion people!", extracting "China" and "more than 140 billion" from this sentence are exactly what NER do.
