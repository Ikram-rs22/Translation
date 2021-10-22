[![GitHub license](https://img.shields.io/github/license/microsoft/ML-For-Beginners.svg)](https://github.com/microsoft/ML-For-Beginners/blob/master/LICENSE)
[![GitHub contributors](https://img.shields.io/github/contributors/microsoft/ML-For-Beginners.svg)](https://GitHub.com/microsoft/ML-For-Beginners/graphs/contributors/)
[![GitHub issues](https://img.shields.io/github/issues/microsoft/ML-For-Beginners.svg)](https://GitHub.com/microsoft/ML-For-Beginners/issues/)
[![GitHub pull-requests](https://img.shields.io/github/issues-pr/microsoft/ML-For-Beginners.svg)](https://GitHub.com/microsoft/ML-For-Beginners/pulls/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/ML-For-Beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/ML-For-Beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/ML-For-Beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/ML-For-Beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/ML-For-Beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/ML-For-Beginners/stargazers/)

# নবীনদের জন্য মেশিন লার্নিং - একটি শিক্ষাক্রম (কারিকুলাম) 

> 🌍 সারাবিশ্ব ভ্রমণ করুন কারণ আমরা বিশ্বসংস্কৃতির সাহায্যে মেশিন লার্নিংকে অনুসন্ধান করছি 🌍

মাইক্রোসফটের এজ্যুর ক্লাউড এডভোকেটগণ আনন্দিত একটি ১২ সপ্তাহব্যাপী , ২৪টি পাঠযুক্ত (প্লাস ১টি!) শিক্ষাক্রম উপস্থাপন করতে পেরে যা শুধুমাত্র **মেশিন লার্নিং** এর উপর তৈরি। এই শিক্ষাক্রমে, আপনি শিখবেন এমন একটি বিষয় যেটিকে অনেক সময় অভিহিত করা হয় **ক্লাসিক মেশিন লার্নিং** বলে, প্রধানত Scikit-learn কে একটি library আকারে ব্যবহার করে এবং ডিপ লার্নিংকে বর্জন করে, যা আমাদের  আসন্ন 'AI For Beginners (নবীনদের জন্য AI)' শিক্ষাক্রমে আলোচনা করা হবে। এই অধ্যায়ের পাঠগুলোকে  ['Data Science for Beginners' curriculum](https://aka.ms/datascience-beginners) - এই পাঠ্যক্রমের সাথে মিলিয়েও পড়তে পারেন !

আমাদের সাথে বিশ্ব ঘুরে আসুন যখন আমরা এসব ক্লাসিক কৌশল পৃথিবীর বিভিন্ন অংশের ডেটার ওপর প্রয়োগ করছি। প্রত্যেকটি পাঠ্য অধ্যায়ের রয়েছে প্রি(পূর্ব) ও পোস্ট (পরবর্তী) কুইজ, পাঠ সম্পন্ন করার জন্য লিখিত নির্দেশনা , একটি সমাধান, একটি এসাইনমেন্ট এবং আরো অনেক কিছু। আমাদের প্রজেক্ট ভিত্তিক(বেইজড) পেডাগজি আপনাকে প্রজেক্ট তৈরির সাথে সাথে শিখারও সুযোগ দেয়, এটি আপনার নতুন দক্ষতার  'stick (মনে থাকা)' থাকার একটি পরীক্ষিত পদ্ধতি । 

**✍️ আন্তরিক অভিনন্দন আমাদের লেখকবৃন্দকে ** Jen Looper, Stephen Howell, Francesca Lazzeri, Tomomi Imura, Cassie Breviu, Dmitry Soshnikov, Chris Noring, Anirban Mukherjee, Ornella Altunyan, and Amy Boyd

**🎨 আমাদের ইলাস্ট্রেটরদেরকেও ধন্যবাদ ** Tomomi Imura, Dasani Madipalli, and Jen Looper

**🙏 বিশেষ ধন্যবাদ 🙏 মাইক্রোসফট স্টুডেন্ট এম্ব্যাসেডরের লেখক, নিরীক্ষক এবং কন্টেন্টে অবদানকারী সকলের প্রতি **, বিশেষভাবে Rishit Dagli, Muhammad Sakib Khan Inan, Rohan Raj, Alexandru Petrescu, Abhishek Jaiswal, Nawrin Tabassum, Ioan Samuila, and Snigdha Agarwal

**🤩 বিশেষ কৃতজ্ঞতা মাইক্রোসফট স্টুডেন্ট এম্ব্যাসেডর Eric Wanjau এর প্রতি আমাদের R এর উপর পাঠ(লেসন) এর জন্য!** 

---

# শুরু করার প্রস্তুতি

**শিক্ষার্থীবৃন্দ**, এই শিক্ষাক্রমকে অনুসরণ করার জন্য, সম্পূর্ণ রিপোসিটরি (repo) কে আপনার নিজের github একাউন্টে fork করুন এবং অনুশীলনগুলি নিজে নিজে অথবা একটি গ্রুপের সাথে সম্পন্ন করুন:

- একটি প্রি(পূর্ব)-লেকচার কুইজের সাথে শুরু করুন।
- লেকচারটি পড়ুন এবং কাজগুলো সম্পন্ন করুন, প্রতিটি নলেজ চেকে থামুন এবং ভাবুন।
- চেষ্টা করবেন প্রজেক্টগুলো সলিউশন কোড না রান করে পাঠসমূহ বুঝে বুঝে পড়ে সম্পন্ন করতে; তবুও সলিউশন কোড প্রতিটি প্রজেক্ট সম্বন্ধীয় পাঠের `/solution` ফোল্ডারে পাওয়া যাবে।
- পোস্ট-লেকচার কুইজটি গ্রহণ করুন।
- চ্যালেঞ্জটি কমপ্লিট করুন।
- এসাইনমেন্টটি সম্পন্ন করুন।
- একটি পাঠ গ্রুপ সম্পন্ন করার পর, ভিজিট করুন [Discussion Board](https://github.com/microsoft/ML-For-Beginners/discussions) এবং যথাযথ PAT বিধিনিষেধ পূরণ করার মাধ্যমে "learn out loud (লার্ন আউট লাউড)" শিখুন . একটি 'PAT' হচ্ছে Progress Assessment Tool। এটি একটী নিয়ম যেটি পরবর্তী পাঠ শিখার জন্য আপনাকে পূরণ করতে হবে। আপনি অন্যদের PATs এ রিয়েক্টও করতে পারবেন যাতে করে আমরা সবাই একসাথে শিখতে পারি।

> ভবিষ্যত শিক্ষার জন্য, আমরা রেকমেন্ড করছি এই [Microsoft Learn](https://docs.microsoft.com/en-us/users/jenlooper-2911/collections/k7o7tg1gp306q4?WT.mc_id=academic-15963-cxa) মডিউল এবং লার্নিং পাথসমূহ ।

**শিক্ষকগণ**, আমরা [কিছু সাজেশন অন্তর্ভুক্ত](for-teachers.md) করেছি এই শিক্ষাক্রমটি ব্যবহার করার জন্য।

---

## দলের সাথে পরিচিত হোন

[![Promo video](ml-for-beginners.png)](https://youtu.be/Tj1XWrDSYJU "Promo video")

> 🎥 উপরের ছবিটি ক্লিক করুন এই প্রজেক্ট এবং এটির নির্মাতাদের উপর একটি ভিডিওচিত্র দেখার জন্য!

---

## পেডাগজি

We have chosen two pedagogical tenets while building this curriculum: ensuring that it is hands-on **project-based** and that it includes **frequent quizzes**. In addition, this curriculum has a common **theme** to give it cohesion.

By ensuring that the content aligns with projects, the process is made more engaging for students and retention of concepts will be augmented. In addition, a low-stakes quiz before a class sets the intention of the student towards learning a topic, while a second quiz after class ensures further retention. This curriculum was designed to be flexible and fun and can be taken in whole or in part. The projects start small and become increasingly complex by the end of the 12-week cycle. This curriculum also includes a postscript on real-world applications of ML, which can be used as extra credit or as a basis for discussion.

> আমাদের নীতিমালা পাওয়া যাবে [Code of Conduct](CODE_OF_CONDUCT.md), [Contributing](CONTRIBUTING.md) এবং  [Translation](TRANSLATIONS.md) এখানে । আমরা গঠনমুলক মতামতকে আমন্ত্রণ জানাই!

## প্রত্যেকটি পাঠে অন্তর্ভুক্ত রয়েছে:

- ঐচ্ছিক স্কেচনোট
- ঐচ্ছিক পরিপূরক ভিডিও
- প্রি-লেকচার প্রস্তুতিমূলক কুইজ
- লিখিত পাঠসমূহ
- প্রজেক্ট ভিত্তিক শিক্ষার জন্য, প্রজেক্ট বানানোর উপর ধাপে-ধাপে (step by step) নির্দেশনা
- জ্ঞান যাচাইকরণ ( নলেজ চেক )
- একটি চ্যালেঞ্জ
- পরিপূরক রিডিং বা পড়া
- এসাইনমেন্ট
- পোস্ট-লেকচার বা লেকচার পরবর্তী কুইজ

> **প্রোগ্রামিং ল্যাংগুয়েজ সম্বন্ধে কিছু কথা **: এই পাঠসমূহ প্রধানত লিখা হয়েছে Python এ , তবে অনেকগুলো পাঠ R ভাষাতেও পাওয়া যাবে। একটি R lesson সম্পন্ন করার জন্য, `/solution` ফোল্ডারে যান এবং R ভাষার পাঠ খুঁজুন . সেখানে একটি .rmd এক্সটেনশোন রয়েছে যেটি নির্দেশ করে একটি **R Markdown** ফাইল যা সহজে চিহ্নিত করা যাবে  `code chunks` ( R এবং অন্যান্য ভাষার জন্য) একটি এম্বেডিং হিসাবে এবং একটি `YAML header` (যা নির্দেশ করে কিভাবে আউটপুট ফরম্যাট করতে হবে)  একটি `Markdown document` এর মধ্যে। এরক্মভাবে, it serves as an exemplary authoring framework for data science since it allows you to combine your code, its output, and your thoughts by allowing you to write them down in Markdown. Moreover, R Markdown documents can be rendered to output formats such as PDF, HTML, or Word.

> **A note about quizzes**: All quizzes are contained [in this app](https://white-water-09ec41f0f.azurestaticapps.net/), for 50 total quizzes of three questions each. They are linked from within the lessons but the quiz app can be run locally; follow the instruction in the `quiz-app` folder.

| পাঠ নম্বর       |                            বিষয়                            |                   পাঠ গ্রুপিং                   | শিখনফল                                                                                                            |                        সংযুক্ত পাঠসমুহ ( লিংকড লেসনস)           |     লেখক     |
|:-------------:|:----------------------------------------------------------:|:---------------------------------------------------:|---------------------------------------------------------------------------------------------------------------------------------|:-------------------------------------------------------------:|:--------------:|
|       ০১      |              মেশিন লার্নিং এর পরিচিতি               |       [Introduction](1-Introduction/README.md)      | মেশিন লার্নিং এর পিছনের প্রাথমিক ধারনা এবং বিষয়গুলো শিখুন                                                                                 |    [Lesson](1-Introduction/1-intro-to-ML/README.md)           |    Muhammad ( মুহাম্মাদ)    |
|       ০২      |              মেশিন লার্নিং এর ইতিহাস             |       [Introduction](1-Introduction/README.md)      | মেশিন লার্নিং এর অজানা ইতিহাস জানুন                                                                                         |   [Lesson](1-Introduction/2-history-of-ML/README.md)          |   Jen and Amy  |
|       ০৩      |              সততা এবং মেশিন লার্নিং                |       [Introduction](1-Introduction/README.md)      |  |     [Lesson](1-Introduction/3-fairness/README.md)             |     Tomomi     |
|       ০৪     |               মেশিন লার্নিং এর কৌশলসমূহ             |       [Introduction](1-Introduction/README.md)      | What techniques do ML researchers use to build ML models?                                                                       | [Lesson](1-Introduction/4-techniques-of-ML/README.md)          |  Chris and Jen |
|       ০৫      |              রিগ্রেশন(Regression) এর পরিচিতি                |         [Regression](2-Regression/README.md)        | Get started with Python and Scikit-learn for regression models                                                                  |       <ul><li>[Python](2-Regression/1-Tools/README.md)</li><li>[R](2-Regression/1-Tools/solution/R/lesson_1-R.ipynb)</li></ul>       |       <ul><li>Jen</li><li>Eric Wanjau</li></ul>    |
|       ০৬      |               উত্তর আমেরিকার কুমড়োর দাম 🎃              |         [Regression](2-Regression/README.md)        | Visualize and clean data in preparation for ML                                                                                  |     <ul><li>[Python](2-Regression/2-Data/README.md)</li><li>[R](2-Regression/2-Data/solution/R/lesson_2-R.ipynb)</li></ul>         |        <ul><li>Jen</li><li>Eric Wanjau</li></ul>     |
|       ০৭      |               উত্তর আমেরিকার কুমড়োর দাম 🎃              |         [Regression](2-Regression/README.md)        | Build linear and polynomial regression models                                                                                   |     <ul><li>[Python](2-Regression/3-Linear/README.md)</li><li>[R](2-Regression/3-Linear/solution/R/lesson_3-R.ipynb)</li></ul>       |       <ul><li>Jen</li><li>Eric Wanjau</li></ul>     |
|       ০৮      |               উত্তর আমেরিকার কুমড়োর দাম 🎃              |         [Regression](2-Regression/README.md)        | Build a logistic regression model                                                                                               |     <ul><li>[Python](2-Regression/4-Logistic/README.md)  </li><li>[R](2-Regression/4-Logistic/solution/R/lesson_4-R.ipynb)</li></ul>     |       <ul><li>Jen</li><li>Eric Wanjau</li></ul>     |
|       ০৯      |                         একটি ওয়েব অ্যাপ 🔌                        |            [Web App](3-Web-App/README.md)           | Build a web app to use your trained model                                                                                       |        [Python](3-Web-App/1-Web-App/README.md)       |       Jen      |
|       ১০     |               ক্লাসিফিকেশন (classification) এর পরিচিতি                |     [Classification](4-Classification/README.md)    | Clean, prep, and visualize your data; introduction to classification                                                            |<ul><li>  [Python](4-Classification/1-Introduction/README.md) </li><li>[R](4-Classification/1-Introduction/solution/R/lesson_10-R.ipynb)  | <ul><li>Jen and Cassie</li><li>Eric Wanjau</li></ul> |
|       ১১      |            সুস্বাদু এশীয় এবং ভারতীয় রন্ধনপ্রণালী (কুইসিন) 🍜           |     [Classification](4-Classification/README.md)    | Introduction to classifiers                                                                                                     |<ul><li> [Python](4-Classification/2-Classifiers-1/README.md)</li><li>[R](4-Classification/2-Classifiers-1/solution/R/lesson_11-R.ipynb) | <ul><li>Jen and Cassie</li><li>Eric Wanjau</li></ul> |
|       ১২      |              সুস্বাদু এশীয় এবং ভারতীয় রন্ধনপ্রণালী (কুইসিন) 🍜           |     [Classification](4-Classification/README.md)    | More classifiers                                                                                                                |<ul><li>  [Python](4-Classification/3-Classifiers-2/README.md)</li><li>[R](4-Classification/3-Classifiers-2/solution/R/lesson_12-R.ipynb)  | <ul><li>Jen and Cassie</li><li>Eric Wanjau</li></ul> |
|       ১৩      |              সুস্বাদু এশীয় এবং ভারতীয় রন্ধনপ্রণালী (কুইসিন) 🍜           |     [Classification](4-Classification/README.md)    | Build a recommender web app using your model                                                                                    |     [Python](4-Classification/4-Applied/README.md)     |       Jen      |
|       ১৪      |                 ক্লাস্টারিং (clustering) এর পরিচিতি                  |         [Clustering](5-Clustering/README.md)        | Clean, prep, and visualize your data; Introduction to clustering                                                                |     <ul><li> [Python](5-Clustering/1-Visualize/README.md)</li><li>[R](5-Clustering/1-Visualize/solution/R/lesson_14-R.ipynb)    |       <ul><li>Jen</li><li>Eric Wanjau</li></ul>    |
|       ১৫      |             নাইজেরিয়ান সংগীতের স্বাদ 🎧            |         [Clustering](5-Clustering/README.md)        | Explore the K-Means clustering method                                                                                           |      <ul><li> [Python](5-Clustering/2-K-Means/README.md)</li><li>[R](5-Clustering/2-K-Means/solution/R/lesson_15-R.ipynb)       |       <ul><li>Jen</li><li>Eric Wanjau</li></ul>      |
|       ১৬      |        ন্যাচারল ল্যাংগুয়েজ প্রসেসিং (natural language processing) এর পরিচিতি ☕️       |    [Natural language processing](6-NLP/README.md)   | Learn the basics about NLP by building a simple bot                                                                             |    [Python](6-NLP/1-Introduction-to-NLP/README.md)  |     Stephen    |
|       ১৭      |                     সাধারণ NLP কাজসমূহ   ☕️                     |    [Natural language processing](6-NLP/README.md)   | Deepen your NLP knowledge by understanding common tasks required when dealing with language structures                          |           [Python](6-NLP/2-Tasks/README.md)     |     Stephen    |
|       ১৮      |            অনুবাদ এবং মনোভাব ( সেন্টিমেন্ট) পর্যবেক্ষণ ♥️            |    [Natural language processing](6-NLP/README.md)   | Translation and sentiment analysis with Jane Austen                                                                             |   [Python](6-NLP/3-Translation-Sentiment/README.md) |     Stephen    |
|       ১৯      |                 ইউরোপের রোমান্টিক হোটেলগুলো ♥️                |    [Natural language processing](6-NLP/README.md)   | Sentiment analysis with hotel reviews 1                                                                                         |      [Python](6-NLP/4-Hotel-Reviews-1/README.md)    |     Stephen    |
|       ২০      |                 ইউরোপের রোমান্টিক হোটেলগুলো ♥️                |    [Natural language processing](6-NLP/README.md)   | Sentiment analysis with hotel reviews 2                                                                                         |      [Python](6-NLP/5-Hotel-Reviews-2/README.md)   |     Stephen    |
|       ২১      |           টাইম সিরিজ ফোরকাস্টিং (time series forecasting) এর পরিচিতি          |        [Time series](7-TimeSeries/README.md)        | Introduction to time series forecasting                                                                                         |    [Python](7-TimeSeries/1-Introduction/README.md)    |    Francesca   |
|       ২২     | ⚡️ বৈশ্বিক ক্ষমতা(পাওয়ার) ব্যবহার ⚡️ - ARIMA এর সাথে টাইম সিরিজ ফোরকাস্টিং |        [Time series](7-TimeSeries/README.md)        | Time series forecasting with ARIMA                                                                                              |        [Python](7-TimeSeries/2-ARIMA/README.md)        |    Francesca   |
|       ২৩      | ⚡️  বৈশ্বিক ক্ষমতা(পাওয়ার) ব্যবহার ⚡️ - SVR এর সাথে টাইম সিরিজ ফোরকাস্ |        [Time series](7-TimeSeries/README.md)        | Time series forecasting with Support Vector Regressor                                                                                              |        [Python](7-TimeSeries/3-SVR/README.md)        |    Anirban   |
|       ২৪      |           রিইনফোর্সমেন্ট লার্নিং (reinforcement learning) এর পরিচিতি           | [Reinforcement learning](8-Reinforcement/README.md) | Introduction to reinforcement learning with Q-Learning                                                                          |    [Python](8-Reinforcement/1-QLearning/README.md)  |     Dmitry     |
|       ২৫      |                পিটারকে নেকড়ের হাত থেকে বাঁচতে সাহায্য করুন! 🐺                | [Reinforcement learning](8-Reinforcement/README.md) | Reinforcement learning Gym                                                                                                      |       [Python](8-Reinforcement/2-Gym/README.md)      |     Dmitry     |
|   Postscript  |          বাস্তবজীবনে ML এবং তার প্রয়োগ           |       [ML in the Wild](9-Real-World/README.md)      | Interesting and revealing real-world applications of classical ML                                                               |    [Lesson](9-Real-World/1-Applications/README.md)    |      Team      |

## অফলাইন অ্যাক্সেস

আপনি এই ডকুমেন্টেশন অফলাইনেও রান করতে পারবেন এটি - [Docsify](https://docsify.js.org/#/) ব্যবহার করে ।  এই রিপজিটরিটি Fork করুন , [install Docsify](https://docsify.js.org/#/quickstart) আপনার লোকাল বা নিজস্ব মেশিনে এবং এরপরে in the root folder of this repo, type `docsify serve`. The website will be served on port 3000 on your localhost: `localhost:3000`.

## পিডিএফসমূহ (PDFs)

শিক্ষাক্রমের একটি পিডিএফ ফাইল পাবেন [এখানে](https://microsoft.github.io/ML-For-Beginners/pdf/readme.pdf).

## সাহায্যের প্রয়োজন!

Would you like to contribute a translation? Please read our [translation guidelines](TRANSLATIONS.md) and add input [here](https://github.com/microsoft/ML-For-Beginners/issues/71).

## অন্যান্য শিক্ষাক্রমসমূহ (কারিকুলা)

আমাদের দল অন্যান্য শিক্ষাক্রমও প্রস্তুত করি! চেক করে দেখুন:

- [Web Dev for Beginners](https://aka.ms/webdev-beginners)
- [IoT for Beginners](https://aka.ms/iot-beginners)
- [Data Science for Beginners](https://aka.ms/datascience-beginners)
