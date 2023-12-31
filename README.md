<h1>Titanic data analysis </h1>
<pre>
This file is an analysis of the Titanic dataset.

아버지의 존재 여부가 생존에 영향을 미치는지 또는 나이가 어릴 수록 생존률이 높은지 그리고 Pclass와 생존률의 관계, 마지막으로 16세 이하인 승객이 가족여행으로 타이타닉을 탔는지를 분석했습니다.

  
PassengerId: 승객의 고유 번호입니다.
Survived: 승객의 생존 여부를 나타냅니다. 0은 사망, 1은 생존을 의미합니다.
Pclass: 승객의 티켓 등급을 나타냅니다. 1은 1등급(가장 높음), 2는 2등급, 3은 3등급(가장 낮음)을 의미합니다.
Name: 승객의 이름입니다.
Sex: 승객의 성별을 나타냅니다. 'male'은 남성, 'female'은 여성을 의미합니다.
Age: 승객의 나이입니다.
SibSp: 함께 탑승한 형제자매 또는 배우자의 수를 나타냅니다.
Parch: 함께 탑승한 부모 또는 자녀의 수를 나타냅니다.
Ticket: 티켓 번호입니다.
Fare: 승객이 지불한 요금입니다.
Cabin: 승객이 배정받은 객실 번호입니다.
Embarked: 승객이 탑승한 항구를 나타냅니다. C는 Cherbourg, Q는 Queenstown, S는 Southampton을 의미합니다.
FamilySize:가족 구성원 수를 나타냅니다.
Father: 아버지의 존재 유무를 나타냅니다.
</pre>
<h2>설치 방법</h2>
<pre>
해당 분석은 conda 가상환경에서 jupyter notebook을 이용했기에 miniconda와 jupyter notebook을 필요로 합니다
사용한 라이브러리는 
numpy 
pandas
matplotlib.pyplot
seaborn
입니다.
각 라이브러리는 conda install을 이용하여 설치 할 수 있습니다.
  
사망자와 생존자 예측에는 scklearn을 이용했으며
conda install scikit-learn

명령어를 통해 설치 가능합니다

</pre>
