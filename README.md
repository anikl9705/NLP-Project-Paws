# NLP-Project-Paws

Paraphrase Adversaries from Word Scrambling

group project for CSE 576 Topics/Natural Language Processing


## The Team

1.Anirudh Krishna Lakshmanan (alaksh19@asu.edu)

2.Sagar Seth (sseth9@asu.edu)

3.Yuanyuan Tian (ytian72@asu.edu)

4.Zhemin Zhang (zzhan215@asu.edu)

5.Xinyu Zhao (Xzhao119@asu.edu)


## Getting Started

The datasets are provided in data_qqp and data_PAWS_qqp folders. The model code is present in HuggingFace/HuggingFace.ipynb.

Note: The code has been set up to be executed in colab. The file paths will need to be changed to accomodate running it in other systems.

### Setting run parameters

- The model used can be changed by changing the following block:

```
MODEL_CLASS, TOKENIZER_CLASS, PRETRAINED = (BertForSequenceClassification, BertTokenizer, 'bert-base-cased')
```

- If PAWS dataset is to be included, change the value of `PAWS_QQP` as `True`

- The other model parameters such as learning rate can be changed by specifying them in the model details.

## TA

Pratyay Banerjee <pbanerj6@asu.edu>

regular meeting with TA: 4:30-5:30pm Wed every week

location: BYENG221 TA Lab   https://www.google.com/maps/place/Brickyard+Engineering,+699+S+Mill+Ave,+Tempe,+AZ+85281/@33.4235981,-111.9417253,17z/data=!3m1!4b1!4m5!3m4!1s0x872b08d8329334d3:0x4fe12bf6b8cf1757!8m2!3d33.4235981!4d-111.9395366

<b>Online Meeting: availability M-F 430-530pm </b>

Hi there,

Pratyay Banerjee is inviting you to a scheduled Zoom meeting.

Topic: Pratyay Banerjee's Personal Meeting Room

Join from PC, Mac, Linux, iOS or Android: https://asu.zoom.us/j/4650534000

Or Telephone:
    Dial(for higher quality, dial a number based on your current location):
        US: +1 669 900 6833  or +1 346 248 7799  or +1 253 215 8782  or +1 301 715 8592  or +1 312 626 6799  or +1 646 876 9923
    Meeting ID: 465 053 4000
    International numbers available: https://asu.zoom.us/u/abNSg7g964

Or iPhone one-tap (US Toll):  +16699006833,,4650534000# or +13462487799,,4650534000#
