# Bena's Poetry Generation Repo
This repo provides a blog-like discussion of my summer REU project on emotion-eliciting and creative poetry generation.

In this project we attempt two approaches of influencing Natural Langauge Generation in the form of poetry:

The first, we leverage a word-level emotion lexicon created by the NRC (National Research Council of Canada), __EmoLex__, for the use of classifying poetry based on the emotions each poem elicits. We then use this fabricated ground-truth to seperate our data and train multiple emotion category language models. Currently the emotions of _anger_, _anticipation_, _joy_, _sadness_, and _trust_ have data that is well represented, while _disgust_, _fear_, and _surprise_ do not.

Second, we gather data from the UC-Santa Cruz Psychology Deparment's __DreamBank__. This dataset contains a collection of dreams that we scrape to include only English reports. The __DreamBank__ will allow us model the language of dreams. Then, in a transfer learning manner, further finetune on poems in the hopes of creating dream like poetry.

## Samples
Listed below are a few handpicked samples from each of the models we currently have trained. 

#### An anger poem:
_Amidst the chaos throng'd, with angry voices each<br/>
His rival's mockery; loud their scorn was fill'd;<br/>
So fierce their rage, and in their eager power<br/>
Met on the walls of Troy, were fill'd with dismay._

#### An anticipation poem:
_We have reached the peak of the highest mountain in the world<br/>
The mountain of dreams.<br/>
This is the view<br/>
Across the valley,<br/>
One hour's journey back,<br/>
We crossed it on the way between<br/>
A band of beautiful young women.<br/>
There was_

#### A joy poem:
_Heard I a song of joy,<br/>
A song of happy sound,<br/>
Fills all the air I breathe,<br/>
To him I sing, to him<br/>
I sing the happy song.<br/>
All night long on the steep green grass<br/>
I ride and sing_

#### A sadness poem:
_A long trail of falling mist<br/>
Had made its way here, and now<br/>
Aerily it seemed, as if to drown<br/>
The discordant thunder clang.<br/>
It seemed to drown the music of the rain;<br/>
In this lost place of sorrow<br/>
Far off_

#### A trust poem:
_The other, who with one accord<br/>
Wrote my essay, in that he was dear<br/>
And good, and knew well, how we ought to treat<br/>
A man of such renown, and such love?<br/>
He's a good honest man, no doubt_

**Future versions of this repo will include code, steps for reproduction, and a more in depth analysis on project subtleties.
