---
layout: page
title: 통계적 사고 워크샵 
---

[싸이그래머](http://psygrammer.github.io/)와 [xwMOOC](http://www.xwmooc.net)가 함께 합니다.

> ### 기계와의 경쟁을 준비하며... {.getready}
>
> "The future is here, it's just not evenly distributed yet."  
>                                                           - William Gibson

### 학습 개요

- 일시 
    - '15년 11월 18일 ~ '16년 1월 6일 (8주간)
    - 매주 수요일 19:00 ~ 20:00
- 장소
    - 서울 강남역 근처 토즈 타워점 : [위치확인](http://www.toz.co.kr/branch/main/index.htm?id=24) 

> ### 교재 {.callout}
> 통계적 사고 (ThinkStats2) : 프로그래머를 위한 확률과 통계  
>     - (번역): [https://github.com/statkclee/ThinkStats2](https://github.com/statkclee/ThinkStats2)  
>     - (원서): [http://greenteapress.com/thinkstats2/](http://greenteapress.com/thinkstats2/)

### LaTeX 사전 공부

- LaTeX 기초
    - [LaTeX 소개 슬라이드](https://github.com/statkclee/mini-course-materials/blob/kr/LaTeX_Basics/basicsOfLatex-kr.pdf)
    - [LaTeX 소개 문서형식](https://github.com/statkclee/mini-course-materials/blob/kr/LaTeX_Basics/basicsOfLatex/latexTemp/latex-intro-kr.pdf)
- LaTeX 석박사 논문 저작
    - [LaTeX : 수학, BibTeX, 사용자 정의](https://github.com/statkclee/mini-course-materials/blob/kr/LaTeX_Math_and_BibTeX/bibtexMathInLatex-kr.pdf)

[출처: OpenIntro.org LaTeX 저작 교육과정](https://github.com/OpenIntroOrg/mini-course-materials)


### 사전 준비

1. Git과 GitHub 
    - [소프트웨어 카펜트리 Git을 이용한 버젼관리](http://swcarpentry.xwmooc.org/lessons-5-2/novice/git/index.html)
    - 리눅스와 맥 사용자: `sudo apt-get install git`
    - 윈도우 사용자: [Git Bash 설치](https://git-scm.com/downloads)
1. 파이썬 설치: **아나콘다 기반 과학컴퓨팅 개발환경을 적극추천** 
    - [아나콘다 기반](http://docs.continuum.io/anaconda/install) 설치
    - [파이썬 기반](https://www.python.org/downloads/) 설치
    - [아나콘다를 적극 추천하는 사유](http://raspberry-pi.xwmooc.org/raspberry-pi-programming-science.html)

~~~ {.shell}
# 파이썬 2 기준 우분투 14.04 64비트 버젼 설치 사례
$ wget https://3230d63b5fc54e62148e-c95ac804525aac4b6dba79b00b39d1d3.ssl.cf1.rackcdn.com/Anaconda2-2.4.0-Linux-x86_64.sh
$ bash ~/Downloads/Anaconda2-2.4.0-Linux-x86_64.sh 
~~~

#### 사전준비 검증

~~~ {.shell}
[xwmooc:~/ThinkStats2/code ] $ python nsfg.py
~~~

~~~ {.output}
nsfg.py:42: SettingWithCopyWarning: 
A value is trying to be set on a copy of a slice from a DataFrame

See the caveats in the documentation: http://pandas.pydata.org/pandas-docs/stable/indexing.html#indexing-view-versus-copy
  df.birthwgt_lb[df.birthwgt_lb > 20] = np.nan
(13593, 244)
nsfg.py: All tests passed.
~~~


### 학습 목차

 |    일시      |         학습 내용                                     |
 |--------------|------------------------------------------------------ |
 |2015. 11. 18  | 탐색적 자료 분석 & 분포                               |
 |2015. 11. 25  | 확률 질량 함수 & 누적분포함수                         |
 |2015. 12. 2	  | 분포 모형화 (Modeling distributions) & 확률밀도함수   |
 |2015. 12. 9	  | 변수간 관계                                           |
 |2015. 12. 16  | 추정 (Estimation)                                     |
 |2015. 12. 23  | 가설 검정 (Hypothesis testing                         |
 |2015. 12. 30  | 선형최소제곱 & 회귀 (Regression)                      |
 |2016. 1. 6	  | 시계열 분석 & 생존분석                                 |

### 열린 통계학 개론

- 현재 작업 중 :[열린 통계학 개론](https://github.com/statkclee/openintro-statistics/tree/kr)

### 언론 기사 

- 한국통계진흥원에서 발간 [통계의 창 (2015년 여름호)](http://sti.kostat.go.kr/)
    - 통계교육원 > 열린교육방 > e-book 게시판
    - [미래인재 데이터과학지: 교육사례중심](./xwMOOC.pdf)
    - [전체 다운로드(100MB)](http://sti.kostat.go.kr/coresti/site/board/fileDownLoad.do?file_name=1&nots_seq=2046)

- [강서양천신문](http://www.gynews.net/) '15년 9월
    - [기고, 컴퓨터 사고력과 소프트웨어 교육](http://www.gynews.net/bbs/bbs.asp?exe=view&group_name=104&section=7&category=0&idx_num=19311&page=1&search_category=&search_word=&order_c=bd_idx_num&order_da=desc)
    - [기고, 글을 쓰는 것은 소프트웨어 개발이다!](http://www.gynews.net/bbs/bbs.asp?exe=view&group_name=104&section=7&category=0&idx_num=19140&page=1&search_category=&search_word=&order_c=bd_idx_num&order_da=desc)

### 참고자료

*   [$100 달러 오픈 컴퓨터](http://computer.xwmooc.org) : [$100 달러 오픈 컴퓨터 워크샵](https://public.etherpad-mozilla.org/p/open-computer)
*   [컴퓨터과학 언플러그드](http://unplugged.xwmooc.org)
*   [러플(Rur-ple)](http://rur-ple.xwmooc.org/)
*   [정보교육을 위한 파이썬](http://python.xwmooc.org/)
*   [라즈베리 파이](http://raspberry-pi.xwmooc.org/)
*   [소프트웨어 카펜트리](http://swcarpentry.xwmooc.org)
*   [R 팩키지](http://r-pkgs.xwmooc.org/)

