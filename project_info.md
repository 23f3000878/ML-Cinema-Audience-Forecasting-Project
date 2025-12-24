In this competition, you are provided with a time-series forecasting problem centered around cinema audience attendance. The data comes from two separate booking platforms:

    BookNow: an online booking and aggregation platform where users can search theatres and book tickets in advance.

    CinePOS: a point-of-sale (POS) system installed at theaters that tracks on-site ticket sales.

Files

    cinePOS_theaters.csv – CinePOS theatre info
    booknow_theaters.csv – BookNow theatre info
    movie_theater_id_relation.csv – Mapping between BookNow and CinePOS theatres.
    cinePOS_booking.csv – CinePOS bookings
    booknow_booking.csv – BookNow bookings
    booknow_visits.csv – Daily audience counts
    date_info.csv – Calendar info
    sample_submission.csv – Submission format (ID = book_theater_id + show_date, audience_count).

Notes

    Audience counts can be influenced by holidays, weekends, theatre type, and booking trends.
    The dataset is anonymized; latitude and longitude are approximate values.
    Use both POS and online booking patterns to forecast future theatre audiences.
    Some theatres may be closed on certain days, leading to zero audiences. Such days are included in the dataset but are ignored in final scoring.

---

https://www.kaggle.com/competitions/Cinema_Audience_Forecasting_challenge/

---

Criteria to pass this project course

    Students must attempt at least three different models to address the problem, as relying on a single model will not be acceptable. Failure to meet this requirement will result in the MLP project being disqualified.
    Additionally, students are expected to:

    Conduct thorough Exploratory Data Analysis (EDA) to provide meaningful insights and support their modeling choices.
    Clearly explain their code, demonstrating a solid understanding of its functionality and purpose.

    Projects that do not meet these standards will not be considered for evaluation.

    Score cutoff in Kaggle for the final submission to be eligible for viva: 0.30

    Passing the project: Viva score >= 25/50 AND Total project score >= 50/100.

The formula for computing Total Score (out of 100) is as follows:

Final marks = NB + M + S + V

Where,

NB = score of your notebook out of 10 marks, this is assigned by the viva examiner - EDA (4 marks), Model Training and Selection (3 marks), Comparison of different models (4 marks)

M : 5 marks will be awarded to those who successfully complete all milestones.

S: Marks for the ML model, 5 marks awarded to all those who cross the cutoff + Score obtained in Kaggle scaled from 0 to 30; Total 35 marks.

 

V: Marks in Viva Voce, out of 50 marks.

Final marks = NB + M + S + V

