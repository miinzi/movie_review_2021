해당 파일들은 KoBERT 다중분류 모델을 이용한 감정분석 기반 영화 추천 시스템 연구(A study on the Movie Recommendation System based on Emotional Analysis using the KoBERT Multi-classification Model)에 사용되었습니다.
모든 자료는 네이버 영화 서비스로부터 수집되었습니다.

movie_data(20211120)_1_50.xlsx
movie_data(20211120)_51_100.xlsx
movie_data(20211120)_101_150.xlsx
movie_data(20211120)_151_200.xlsx
: 2021년 11월 20일 기준 네이버 영화 평점순 1위부터 200위까지의 영화 를 예외처리 한 후 선정된 영화 105개의 상세 정보입니다. 수집된 영화 상세 정보는 movie_index(수집된 영화 index), movie_code(영화의 고유코드), movie_title(영화 제목), movie_genre(영화 장르), movie_director(영화 감독), movie_actor(주연 배우), movie_story(줄거리), movie_date(개봉일), review_num(리뷰 수), movie_link(영화 상세정보 페이지 링크), date(개봉년도), moive_time(상영시간), movie_rate(평점)입니다.

review_data(20211120)_1_50.xlsx
review_data(20211120)_51_100.xlsx
review_data(20211120)_101_150.xlsx
review_data(20211120)_151_200.xlsx
: 영화 상세 정보 파일들에 포함된 영화들에 대해 수집된 한줄평 중 결측치를 제거한 644,030 문장과 평점입니다.

Naver_Movie_Review_Crawler.ipynb
: 네이버 영화 서비스 내 평점순 페이지에서 영화 상세정보와 한줄평을 수집하는 코드입니다. Google Colaboratory를 통해 생성, 실행되었습니다.

testing collaborator
