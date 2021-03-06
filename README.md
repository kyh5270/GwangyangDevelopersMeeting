# KaggleStudy

## Colab 사용 Tip
 1. Google Colab 환경설정 및 사용법
  - https://theorydb.github.io/dev/2019/08/23/dev-ml-colab/
  - https://gumu.kr/blog/353/%EA%B5%AC%EA%B8%80-colab-%EC%82%AC%EC%9A%A9%ED%95%98%EA%B8%B0/
  - https://ndb796.tistory.com/312
  - https://zzsza.github.io/data/2018/08/30/google-colab/
  
 2. Colab에서 Tensorflow 2.0 이상으로 실행하는 방법(현재는 1.15버전으로 실행됨)
  - !pip install --upgrade tensorflow      맨 앞에 추가하기
  - 예) 
    ~~~
    !pip install --upgrade tensorflow
    import tensorflow as tf
    import numpy as np

    print(tf.__version__)
    ~~~
  - 설치 후에 다시 런타임 재시작 하고
    ~~~
    #!pip install --upgrade tensorflow (재시작 후 주석으로 변경)
    import tensorflow as tf
    import numpy as np

    print(tf.__version__)
    ~~~
  
 3. Colab에서 Kaggle 데이터 연결하여 사용하기
  - https://medium.com/hyunjulie/%EC%BA%90%EA%B8%80%EA%B3%BC-%EA%B5%AC%EA%B8%80-colab-%EC%97%B0%EA%B2%B0%ED%95%B4%EC%A3%BC%EA%B8%B0-6a274f6de81d

## Kabble관련 정보
 1. Kaggle 설명
  - GwangyangDevelopersMeeting/Kaggle 소개.pptx 참고
  
 2. 기타 정보
  - https://tykimos.github.io/2019/07/04/ISS_2nd_Deep_Learning_Conference_All_Together_yhlee/
  
  
## Jupyter Notebook 사용 팁
 1. Notebook 사용 팁
  - http://blog.naver.com/PostView.nhn?blogId=is_king&logNo=221527516004&parentCategoryNo=&categoryNo=77&viewDate=&isShowPopularPosts=true&from=search
 2. Markdown 사용 팁
  - https://post.naver.com/viewer/postView.nhn?volumeNo=24627214&memberNo=42458017
