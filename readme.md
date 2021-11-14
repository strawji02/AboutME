![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=strawji02&count_private=true)

## ✏️ Career

|    Type   |          Name          |    Date    |    Organization   |
|:---------:|:----------------------:|:----------:|:-----------------:|
| Education | Computer Engineering | 2020.03 ~  | Hongik University |
| Education | Department of Software | 2017.03 ~ 2020.02 | Sunrin Internet Highschool |

## 👩🏻‍💻 Tech Stack

![React](https://img.shields.io/badge/React-49d6f9?style=flat-square&logo=react&logoColor=white) 
![Redux](https://img.shields.io/badge/Redux-764ABC?style=flat-square&logo=redux&logoColor=white)
![Typescript](https://img.shields.io/badge/Typescript-3178C6?style=flat-square&logo=typescript&logoColor=white) 

![Chrome](https://img.shields.io/badge/Chrome_Extension-4285F4?style=flat-square&logo=googlechrome&logoColor=white) 
![Javascript](https://img.shields.io/badge/Javascript-F7DF1E?style=flat-square&logo=javascript&logoColor=white)

## 🔖 Activate

* 신촌연합 동아리 내 소모임으로 프로젝트 진행 (2020.7)
* 홍익대학교 컴퓨터공학과 개발학회 부학회장, HTML · CSS 기초 스터디 스터디장으로 진행 (2021.2)
* 홍익대학교 자기주도학습 개발동아리 (C언어 기초 스터디) 팀 대표로 진행

## 📖 Project



### [**mazassumnida**](https://github.com/mazassumnida/mazassumnida) ![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white) ![CSS](https://img.shields.io/badge/CSS-F43059?style=flat-square&logo=csswi&logoColor=white)

> 알고리즘 문제 사이트인 백준의 문제 티어를 표시해주는 확장인 Solved.ac의 본인 프로필을 카드형식의 디자인으로 예쁘게 표시할 수 있게 만들기 위해 진행한 프로젝트
>
> 기간 : 2020.07 ~ 2020.08
>
> 사용 기술 : api용 서버를 Heroku에 django로 배포했으며 티어를 표시해주는 카드는 css에서 svg를 그린 뒤 애니메이션을 추가함

[![Solved.ac 프로필](http://mazassumnida.wtf/api/v2/generate_badge?boj=strawJI)](https://solved.ac/strawji)

### [**tierimnida**](https://github.com/mazassumnida/tierimnida) 
![Chrome](https://img.shields.io/badge/Chrome_Extension-4285F4?style=flat-square&logo=googlechrome&logoColor=white) 
![Javascript](https://img.shields.io/badge/Javascript-F7DF1E?style=flat-square&logo=javascript&logoColor=white) 
![CSS](https://img.shields.io/badge/CSS-F43059?style=flat-square&logo=csswi&logoColor=white)

> 백준에서 유저 정보에 있는 푼 문제들이 티어 정보를 볼 수 없고 숫자 기준으로만 정렬되어 있어, 이를 티어별 정렬 옵션과 함께 티어 색을 텍스트에 씌우면 좋을 것 같다는 생각으로 진행한 프로젝트
>
> 기간 : 2021.08 ~
>
> 사용 기술 : Solved.ac의 api를 이용해서 Heroku서버에 일정 시간마다 모든 문제들의 난이도 티어를 가져와 저장함. Chrome Extension에서는 백준 유저의 '맞은 문제' 페이지 접속시마다 Heroku 서버에 리퀘스트를 요청하여 문제들의 티어를 받아온 뒤, 티어별로 css로 색을 입혀 페이지에 뿌려줌. 정렬 기능을 위해 자바스크립트를 사용하였음.

### [**cocktails-recipe**](https://github.com/strawji02/cocktail-recipes) 
![React](https://img.shields.io/badge/React-49d6f9?style=flat-square&logo=react&logoColor=white) 
![Redux](https://img.shields.io/badge/Redux-764ABC?style=flat-square&logo=redux&logoColor=white)
![Typescript](https://img.shields.io/badge/Typescript-3178C6?style=flat-square&logo=typescript&logoColor=white) 
 
> 집에서 홈텐딩을 할 때, 여러 칵테일 레시피들이 각각 조금씩 달라 찾기 힘들었던 경험이 있다. 따라서 공식 칵테일 레시피들을 표시해 준 후, 재료에 따른 칵테일 리스트를 보여주고 날짜에 따른 랜덤 칵테일 추천 기능을 구현하였다. 
>
> 기간 : 2021.10 ~
> 
> 사용 기술 : npm의 json 파일을 이용해 간단한 restful api 구축. redux의 미들웨어인 saga를 이용해 api에서 정보를 받아옴. redux store에 재료와 칵테일 요청, 칵테일 리스트를 저장해놓음. 페이지의 체크리스트에 체크한 재료를 기반으로 만들수 있는 칵테일 레시피들을 보여주고, 검색시 같은 이름들의 재료나 레시피를 보여줌.
