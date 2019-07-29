# Bena's Poetry Generation Repo
This repo provides a blog-like discussion of my summer REU project on emotion-eliciting and creative poetry generation.

In this project we attempt two approaches of influencing Natural Langauge Generation in the form of poetry:

The first, we leverage a word-level emotion lexicon created by the NRC (National Research Council of Canada), __EmoLex__, for the use of classifying poetry based on the emotions each poem elicits. We then use this fabricated ground-truth to seperate our data and train multiple emotion category language models. Currently the emotions of _anger_, _anticipation_, _joy_, _sadness_, and _trust_ have data that is well represented, while _disgust_, _fear_, and _surprise_ do not.

Second, we gather data from the UC-Santa Cruz Psychology Deparment's __DreamBank__. This dataset contains a collection of dreams that we scrape to include only English reports. The __DreamBank__ will allow us model the language of dreams. Then, in a transfer learning manner, further finetune on poems in the hopes of creating dream like poetry.

## Samples
Listed below are a few handpicked samples from each of the models we currently have trained. 

A joy poem|
----------|

**Future versions of this repo will include code, steps for reproduction, and a more in depth analysis on project subtleties.
