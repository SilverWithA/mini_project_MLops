<h1>mini_porject_MLOps_2023</h1>
<h2>프로젝트 개요</h2>

<img src="https://github.com/SilverWithA/mini_project_MLops/assets/92441328/9defd77a-47bb-4539-a6d7-9f9d4af31460" alt="project overview">

<p><a href="https://github.com/SilverWithA/mini_project_MLops/blob/main/documentation/confluence_%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%EA%B0%9C%EC%9A%941.pdf">https://github.com/SilverWithA/mini_project_MLops/blob/main/documentation/confluence_%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%EA%B0%9C%EC%9A%941.pdf</a></p>

<h2>기여자 (Contributors) ✨</h2>
<table>
  <tr>
    <td align="center">
      <a href="https://github.com/beomki-kim">
        <img src="https://avatars.githubusercontent.com/u/37844020?v=4"width="100px;" alt=""/>
        <br />
        <sub>
          <b>Beomki Kim</b>
        </sub>
      </a>
      <br />
      <a href="https://github.com/beomki-kim" title="Code">🏠</a>
    </td>
    <td align="center">
      <a href="https://github.com/SilverWithA">
        <img src="https://avatars.githubusercontent.com/u/92441328?v=4"width="100px;" alt=""/>
        <br />
        <sub>
          <b>silver a</b>
        </sub>
      </a>
      <br />
      <a href="https://github.com/SilverWithA" title="Code">🏠</a>
    </td>
    <td align="center">
      <a href="https://github.com/kjjh714">
        <img src="https://avatars.githubusercontent.com/u/59947483?v=4" width="100px;" alt=""/>
        <br />
        <sub>
          <b>kjjh714</b>
        </sub>
      </a>
      <br/>
      <a href="https://github.com/kjjh714" title="Code">🏠</a>
    </td>
    <td align="center">
      <a href="https://github.com/Hoonscucci">
        <img src="https://avatars.githubusercontent.com/u/132039559?v=4"width="100px;" alt=""/>
        <br />
        <sub>
          <b>Hoonscucci</b>
        </sub>
      </a>
      <br />
      <a href="https://github.com/Hoonscucci" title="Code">🏠</a>
    </td>
    <td align="center">
      <a href="https://github.com/lee-young-jik">
        <img src="https://avatars.githubusercontent.com/u/91588673?v=4"width="100px;" alt=""/>
        <br />
        <sub>
          <b>Young JIk LEE</b>
        </sub>
      </a>
      <br />
      <a href="https://github.com/lee-young-jik" title="Code">🏠</a>
    </td>
  </tr>
</table>

<h2>프로젝트 기간</h2>
<p>2023.06.12-2023.06.23</p>

<img src="https://github.com/SilverWithA/mini_project_MLops/assets/92441328/21d2fc21-bc00-4477-b289-ead8eaf29c1b" alt="project diagram">

<h2>협업 툴</h2>
<p>Google docs, Confluence, Slack</p>

<h2>기술 스택</h2>
<p>개발언어: Python</p>
<p>워크벤치: Google Colab, jupyter notebook</p>
<p>스토리지 : Google Cloud Storage, BigQuery</p>
<p>데이터 웨어하우스 : BigQuery, Vertex AI_Dataset</p>
<p>ML 플랫폼 : Vertex AI</p>

<h2>프로젝트 데이터</h2>

![image](https://github.com/SilverWithA/mini_project_MLops/assets/37844020/14e31d79-b38d-485f-aeed-131a3e039d1b)

<h2>Coupon Purchase Prediction 파일 설명</h2>
<ul>
  <li>데이터 세트는 각 엔터티에 대해 해시된 ID 열이 있는 관계형 형식을 가집니다.</li>
  <li>user_list.csv: 데이터 세트의 사용자 마스터 목록</li>
  <li>coupon_list_train.csv: 훈련 세트에 포함되는 쿠폰의 마스터 목록</li>
  <li>coupon_list_test.csv: 테스트 세트에 포함되는 쿠폰의 마스터 목록입니다. 대회 예측은 이 310개 쿠폰에서만 가져와야 합니다. 테스트 세트 기간 동안 훈련 세트에서 구매된 쿠폰을 예측하면 점수를 받을 수 없습니다.</li>
  <li>coupon_visit_train.csv: 훈련 세트 시간 동안 사용자가 쿠폰을 둘러보는 로그입니다. 테스트 세트 기간에는 이 테이블이 제공되지 않습니다.</li>
  <li>coupon_detail_train.csv: 훈련 세트 시간 동안 사용자가 쿠폰을 구매하는 로그입니다. 테스트 세트 기간에는 이 테이블이 제공되지 않습니다.</li>
  <li>coupon_area_train.csv: 훈련 세트 쿠폰의 상품 광고 지역</li>
  <li>coupon_area_test.csv: 테스트 세트 쿠폰의 상품 광고 지역</li>
  <li>sample_submission.csv: 예측 결과의 올바른 형식을 보여주는 샘플 파일</li>
  <li>documentation.zip: 엔터티 관계 다이어그램과 영어 번역이 포함된 엑셀 파일 아카이브</li>
</ul>
<p><a href="https://www.kaggle.com/competitions/coupon-purchase-prediction/data">https://www.kaggle.com/competitions/coupon-purchase-prediction/data</a></p>

<h2>프로젝트 내용</h2>

<h3>1. MLOps</h3>

<h4>데이터 베이스 및 파이프라인 구성</h4>
<p>담당: 김범기</p>
<img src="https://github.com/SilverWithA/mini_project_MLops/assets/37844020/99520411-4cdf-4d0a-a15d-9bd6a21a421e" alt="database and pipeline">
<p>소비 패턴 변화가 상대적으로 예민한 쇼핑 플랫폼 특성 상, 상대적으로 모델의 수명 주기가 짧을 것으로 판단했습니다.</p>
<p>반복 모델 학습 및 배포가 용이한 파이프 라인을 만들기로 하고, 첫 구축 과정으로 MLOps : 0 단계로 설계하게 되었습니다.</p>
<p>자세한 내용은 첨부한 아래 링크에서 확인 가능합니다.</p>
<p>링크 : <a href="https://beomki-kim.tistory.com/13">https://beomki-kim.tistory.com/13</a></p>
  
<h3>2. 분류 모델</h3>

<h4>로지스틱 회귀</h4>
<p>담당: 이상훈</p>
<img src ="https://github.com/SilverWithA/mini_project_MLops/assets/132039559/c3e0efe6-314e-4985-81b9-9db97b5b6ca4">

<h5>1. 데이터 전처리</h5>
<ul>
  <li>LabelEncode</li>
  <li>StandardScaler</li>
  <li>OverSampling</li>
</ul>

링크 : https://url.kr/o2pzfi

  
<h3>3. 랜덤 포레스트</h3>
<p>담당: 이영직</p>


<img src = "https://github.com/SilverWithA/mini_project_MLops/assets/91588673/9cda8f10-c460-4d35-99b8-079c4d47e667"> 

<br>

<h3>4. Xgboost 및 LightGBM</h3>
<p>담당: 김지현</p>
<img src = "https://github.com/SilverWithA/mini_project_MLops/assets/59947483/5802f596-709a-4278-a4d3-9cfb4dfcf65f"> 

<h5>1. 데이터 전처리</h5>
<ul>
  <li>LabelEncoder</li>
  <li>StandardScaler</li>
  <li>OverSampling(SMOTE 방법)</li>
</ul>

<h5> 2. 모델 학습 및 정확도, 변수 중요도 확인</h5>
<ul>
  <li>xgboost / 오버샘플링 후 xgboost</li>
  <li>lightgbm / 오버샘플링 후 lightgbm</li>
</ul>


링크 : https://url.kr/kf6xj5
<br>

<h3>5. ANN(인공신경망)</h3>

<img src="https://github.com/SilverWithA/mini_project_MLops/assets/92441328/bad9cbe3-11f5-4cef-aec9-011df669b242" alt="ANN diagram">

<p><a href="https://zrr.kr/U4nP">https://zrr.kr/U4nP</a></p>
<p>담당: 정은아</p>
<h5>1. 데이터 전처리</h5>
<ul>
  <li>LabelEncode()</li>
  <li>StandardScaler()</li>
  <li>Embedding Layer</li>
</ul>
<h5>2. 모델 구성 및 학습, 하이퍼 파라미터 튜닝</h5>
<ul>
  <li>모델의 구성</li>
  <p>input - Embedding Layer - Dense Layer_hidden1 - Dense Layer_hidden2 - output</p>
</ul>

<h2>프로젝트 정리</h2>

<p><a href="https://zrr.kr/fteH">https://zrr.kr/fteH</a></p>

<h2>프로젝트 회고</h2>


<ul>
  <li>정은아: <a href="https://re-decor5213.tistory.com/39">https://re-decor5213.tistory.com/39</a></li>
  <li>이상훈: <a href="https://zrr.kr/yLSB">https://zrr.kr/yLSB</a></li>
  <li>이영직: <a href="https://zrr.kr/ePlf">https://zrr.kr/ePlf</a></li>
  <li>김범기: <a href="https://url.kr/jiwqsz">https://url.kr/jiwqsz</a></li>
  <li>김지현: <a href="https://kiiimji96.tistory.com/53">https://kiiimji96.tistory.com/53</a></li>
</ul>

<h2>참고문헌</h2>
<li>[1] kairos03,"GCP AI-Platform에서 딥러닝 학습하기", https://gist.github.com/kairos03/d40d5d9a3fc97e3ee83c4d4f863434db</li>

