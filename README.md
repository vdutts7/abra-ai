<div align="center">

  <img src="https://raw.githubusercontent.com/vdutts7/dump/main/assets/ace-ai-logo.png" alt="Logo" width="80" height="80">

 <h1 align="center">
        Abra AI: AI-Powered Interviews 
    </h1>
    <p align="center"> 
        <i><b>The new era of recruiting. Instant feedback with detailed analytics.</b></i>
        <br /> 
    </p>

[![Website][website]][website-url]
[![Github][github]][github-url]

 </div>

<br/>

## Table of Contents

  <ol>
    <a href="#about">📝 About</a><br/>
    <a href="#how-i-built">💻 How I Built</a><br/>
    <a href="#my-next-steps">🚀 My Next Steps</a><br/>
    <a href="#tools-used">🔧 Tools Used</a>
        <ul>
        </ul>
    <a href="#contact">👤 Contact</a>
  </ol>

<br/>

## 📝About

Abra is a powerful tool designed to enhance your interview skills by offering valuable insights into your performance during mock interviews.

<b>1. No Judgment</b>

  <p>
  Receive unbiased feedback and support from our community of experts and peers.
  </p>

<b>2. Customization</b>

  <p>
  Input your own interview questions and create dynamic interview scenarios to practice for your big day.
  </p>

<b>3. Instant Insights</b>

  <p>
  Get instant feedback analytics from our AI and hone your interviewing skills.
  </p>

## 💻How I Built

- The base ML model is powered by TensorFlow
- NLP was done with spaCy
- Keras Speech Recognition was used to build the speech models
- FFMPEG was used to process the audio recordings
- OpenAI to process text responses and feed lvie user data to FFMPEG, then send response back in avatar persona style to mimic interview process
- AWS Lambda infrastructure used for scalable deployment
- Redis as DB backend and the cache layer. Helpful for hosting company data and question sets.
- GraphQL for API
- AWS SageMaker serves the AI/ML models
- Frontend website built on NextJs and styled with Tailwind CSS

## 🚀My Next Steps

Expecting to launch this soon and add user authentication and waitlist forms. Stay tuned 👀.

## 🔧Tools Used

[![TensorFlow][tensorflow]][tensorflow-url]
[![spaCy][spacy]][spacy-url]
[![Keras][keras]][keras-url]
[![OpenAI][openai]][openai-url]
[![FFMPEG][ffmpeg]][ffmpeg-url]
[![Redis][redis]][redis-url]
[![AWSLambda][awslambda]][awslambda-url]
[![GraphQL][graphql]][graphql-url]
[![AWSSagemaker][awssagemaker]][awssagemaker-url]
[![Next][next]][next-url]

## 👤Contact

[![Email][email]][email-url]
[![Twitter][twitter]][twitter-url]

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[openai]: https://img.shields.io/badge/OpenAI_GPT--3.5/4-0058A0?style=for-the-badge&logo=openai&logoColor=white&color=4aa481
[openai-url]: https://openai.com/
[ffmpeg]: https://img.shields.io/badge/🎥FFPMPEG-DD0031?style=for-the-badge&color=gray
[ffmpeg-url]: https://ffmpeg.org/
[tensorflow]: https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=fff&color=FF6F00
[tensorflow-url]: https://www.tensorflow.org/
[keras]: https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=D00000&color=white
[keras-url]: https://keras.io/
[spacy]: https://img.shields.io/badge/spaCy-000000?style=for-the-badge&logo=spacy&logoColor=000000&color=00d5ff
[spacy-url]: https://spacy.io/
[graphql]: https://img.shields.io/badge/Graphql-E10098?style=for-the-badge&logo=graphql&logoColor=white&color=E10098
[graphql-url]: https://graphql.org/
[redis]: https://img.shields.io/badge/redis-CC0000.svg?&style=for-the-badge&logo=redis&logoColor=red&color=0A192F
[redis-url]: https://graphql.org/
[awslambda]: https://img.shields.io/badge/AWS_Lambda-FF9900?style=for-the-badge&logo=aws-lambda&logoColor=ff9900&color=0A192F
[awslambda-url]: https://aws.amazon.com/lambda/
[awssagemaker]: https://img.shields.io/badge/AWS_SageMaker-FF9900.svg?style=for-the-badge&logo=aws-sagemaker&logoColor=FF9900&color=0A192F
[awssagemaker-url]: https://aws.amazon.com/sagemaker/
[next]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[next-url]: https://nextjs.org/
[tailwindcss]: https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=skyblue&color=0A192F
[tailwindcss-url]: https://tailwindcss.com/
[website]: https://img.shields.io/badge/🔗Website-7f18ff?style=for-the-badge
[website-url]: https://ace-ai.vercel.app/
[github]: https://img.shields.io/badge/💻Github-000000?style=for-the-badge
[github-url]: https://github.com/vdutts7/ace-ai
[email]: https://img.shields.io/badge/me@vdutts7.com-FFCA28?style=for-the-badge&logo=Gmail&logoColor=00bbff&color=black
[email-url]: #
[twitter]: https://img.shields.io/badge/Twitter-FFCA28?style=for-the-badge&logo=Twitter&logoColor=00bbff&color=black
[twitter-url]: https://twitter.com/vdutts7/
