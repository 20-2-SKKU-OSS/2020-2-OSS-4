---
layout: work
title: Work
slug: /work
items:
  - title: My Interest 1
    image:
      src: /assets/img/work/water.png
      alt: water
    description: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
  - title: My Interest 2
    image:
      src: /assets/img/work/sand.png
      alt: sand
    description: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
---

This is an example of a "Work" page, displaying your work, your interests, your projects.
<br />

<br />
---
layout: work
title: Work
slug: /work
items:
  - title: 'soynlp'
    image:
      src: /assets/img/work/water.png
      alt: water
    description: 
    soynlp - 한국어 형태소 분석 기능을 제공하는 모듈입니다. 
<br />

학습데이터 없이도 단어를 찾고 품사를 구분하는 점이 특징이며 단어 추출 / 토크나이저 / 품사판별 / 전처리 기능을 제공합니다.
<br />
프로젝트 내부에 soynlp를 처음 접하는 사용자를 위한 tutorials directory가 존재합니다. .ipynb파일로 이루어진 여러 튜토리얼 파일에는 soynlp 모듈에 어떤 함수가 있고 어떻게 쓸 수 있는지 자세히 기술되어 있습니다.
<br />

이 부분에서 저희는 다수의 오타 및 오류를 발견하였고, 이를 수정함으로써 튜토리얼 파일의 정확성과 가시성을 높였습니다.
<br />
--->2020-11-29-typo-check : <https://20-2-skku-oss.github.io/2020-2-OSS-4/2020/11/29/typo-ckeck>

<br />
soynlp.normalizer 모듈은 분석하고자 하는 글의 전처리 - 특수기호 배제 또는 반복된 자,모음 제거 등의 기능을 제공합니다. 저희는 한자가 포함된 글에 대해서 normalize 과정을 진행하고 싶었으나, 기존 함수로는 한계가 있어 한글, 한자, 영어, 숫자만을 남기는 새로운 기능을 추가하고자 했습니다. 
<br />
--->2020-12-04-text-with-hanja :<https://20-2-skku-oss.github.io/2020-2-OSS-4/2020/12/04/text-with-hanja>
<br />

  - title: 'kroman'
    image:
      src: /assets/img/work/sand.png
      alt: sand
    description: kroman - 한글 문장을 로마자로 표기하는 기능을 제공합니다.
<br />
우분투(20.04.1) 환경에서 프로젝트를 직접 다운로드하여 컴파일했을 때 에러가 발생했습니다. 에러를 해결하기 위해 코드를 일부 수정하였고, 해결하지 못한 에러는 bug report를 보냈습니다.
<br />
--->2020-12-06-error-fix : <https://20-2-skku-oss.github.io/2020-2-OSS-4/2020/12/06/error-fix>
<br />
우리말에는 음운 변동 현상이 존재합니다. 예컨대, 음절의 끝소리 규칙이나 거센소리되기, 된소리되기가 있습니다. 기존 모듈이 지닌 로직으로는 위의 현상을 하나도 구현하지 못한다는 허점을 발견했습니다. 그래서 이를 반영하는 기능을 추가로 구현해 보았습니다. 
<br />
--->2020-12-04-emwoon : <https://20-2-skku-oss.github.io/2020-2-OSS-4/2020/12/04/emwoon>
<br />
---

