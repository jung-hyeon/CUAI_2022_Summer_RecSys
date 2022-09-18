## CUAI Summer Conference Recommendation System Team 10 🚀


__📍 Topic:__ 차애캐와 애니메이션 추천 (Recommender for secondary-favorite characater and anime)

__📍 Background:__ 애니메이션 시청에 긍정적 경험을 확장하기 위해 사용자가 선호할 확률이 높은 캐릭터와 애니메이션을 추천

__📍 Link:__ Short Paper | Codes | Presentation

---

### Members 🏃
👨‍💻 김병준 (_College of Computer Science, Chung-ang Univ._)

🧑‍💻 김정우 (_College of Business Administration, Chung-ang Univ._)

👨‍💻 김찬호 (_College of Applied Statistics, Chung-ang Univ._)

👩‍💻 박정현 (_College of Applied Statistics, Chung-ang Univ._)

---

### Datasets 📁

[myanimelist](https://www.kaggle.com/datasets/hernan4444/anime-recommendation-database-2020?select=anime.csv)
- anime data
- synopsis
- ratings

[anime-planet](https://www.kaggle.com/datasets/hernan4444/animeplanet-character-recommendation)
- characters metadata (_including descriptions_)

---

### Model Training 🖥️
#### Contents-based filtering

* Feature based recommender
  * One-hot vector
  * Cosine similarity

<img width="96" alt="image" src="https://user-images.githubusercontent.com/93517343/184798724-daabd3b7-18e8-4a4b-83cc-9e50898ee60a.png"><img width="162" alt="image" src="https://user-images.githubusercontent.com/93517343/184798773-96cbf95b-b909-4c2d-b196-290b566c4c44.png">


* Description/Synopsis based recommender
  * TF-IDF
  * Cosine similarity

<img width="87" alt="image" src="https://user-images.githubusercontent.com/93517343/184798758-43f0b8a7-b529-4b98-bd5b-814bac3121b7.png"><img width="161" alt="image" src="https://user-images.githubusercontent.com/93517343/184798793-73890d7d-3bb0-40d9-a95d-a3fb93349f00.png">


#### Collaborative filtering

* 'surprise' library
  * Best algorithm: SVD (Singular Value Decomposition)
<img width="158" alt="image" src="https://user-images.githubusercontent.com/93517343/184798812-5f4adfb4-c1b8-4e58-bf11-5b25270f97b9.png">
<img width="215" alt="image" src="https://user-images.githubusercontent.com/93517343/184798834-2d4a241d-90f4-4875-a94e-85ac2bcad90a.png">


---

### References 📚

* Aggarwal, Charu C. Recommender systems. Vol. 1. Cham: Springer International Publishing, 2016.
* Zhang, Yin, Rong Jin, and Zhi-Hua Zhou. "Understanding bag-of-words model: a statistical framework." International journal of machine learning and cybernetics 1.1 (2010): 43-52.
* Ramos, Juan. "Using tf-idf to determine word relevance in document queries." Proceedings of the first instructional conference on machine learning. Vol. 242. No. 1. 2003.
* Schafer, J. Ben, et al. "Collaborative filtering recommender systems." The adaptive web. Springer, Berlin, Heidelberg, 2007. 291-324.

