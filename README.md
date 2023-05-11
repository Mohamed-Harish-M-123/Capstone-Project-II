# Capstone-Project-II
# ML Regression Project - TED Talks Views Prediction

**TED (Technology, Entertainment, Design) Talks** are a series of influential and inspiring talks given by experts and thought leaders from a wide range of fields. The talks are typically 18 minutes or less and are designed to share innovative ideas, spark conversation, and foster learning.

TED Talks began in 1984 as a conference where experts from the fields of technology, entertainment, and design could come together to share their ideas. Since then, the TED conference has expanded to cover a wide range of topics, including science, business, education, and more.

In addition to the main TED conference, there are also independently organized TEDx events around the world, which are designed to showcase local voices and ideas. TEDx events are organized by volunteers and can cover any topic, as long as it aligns with TED's mission of "ideas worth spreading."

TED Talks have become an incredibly popular platform for sharing ideas and sparking conversation around the world. They are widely available online, with millions of people watching and sharing the talks on various platforms such as YouTube and the TED website.

## Objective:

The main objective is to build a predictive model, which could help in predicting views of the video uploaded on the TEDx website.

## Dataset Information:

- Number of records: 4005
- Number of features: 19

### Feature description:
- talk_id: Talk identification number provided by TED
- title: Title of the talk
- speaker_1: First speaker in TED's speaker list
- all_speakers: Speakers in the talk
- occupations: Occupations of the speakers
- about_speakers: Blurb about each speaker
- recorded_date: Date the talk was recorded
- published_date: Date the talk was published to TED.com
- event: Event or medium in which the talk was given
- native_lang: Language the talk was given in
- available_lang: All available languages (lang_code) for a talk
- comments: Count of comments
- duration: Duration in seconds
- topics: Related tags or topics for the talk
- related_talks: Related talks (key='talk_id',value='title')
- url: URL of the talk
- description: Description of the talk
- transcript: Full transcript of the talk

### Dependent variable: 'views'

## Libraries used:
1. Pandas for data manipulation and aggregation.
2. Matplotlib and seaborn for visualization and behaviour with respect to target variable.
3. NumPy for computationally efficient operations.
4. Scikit Learn for model training, model optimization, and metrics calculation.
