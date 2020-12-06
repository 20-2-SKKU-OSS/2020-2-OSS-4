---
layout: post
title:  "text with hanja"
date:   2020-12-04 10:00:40
blurb: "A look at an example post using Bay Jekyll theme."

---
<br />
제목: soynlp 한자 포함 전처리
<br />
![text with hanja](assets/img/text with hanja.jpg)
<br />
<br />

normalizer 모듈은 only_hangle, emoticon_normalizer 등의 함수를 제공합니다. 
<br />
이는 분석하고자 하는 텍스트를 가공하기 위한 것으로, only_hangle은 텍스트에 오직 한글만 포함되게 만드는 것이고
emoticon_normalizer는 반복되는 자음,모음을 줄이고 겹친 자음,모음을 분해합니다.
<br />
저희는 한자가 포함된 텍스트를 가공하는데에 필요성을 느꼈습니다. 
<br />
예컨대, 한자가 포함된 뉴스 기사나 논문에서 전처리과정을 거치면 한자가 제거되는데, 한자가 제거되지 않는 전처리 함수를 만드는 것입니다.
<br />
추가된 코드 설명은 wiki : <https://github.com/20-2-SKKU-OSS/soynlp/wiki>를 참고해주세요.
