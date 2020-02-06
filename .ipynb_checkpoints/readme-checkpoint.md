# Oscar Bait code and data

Here you can download all the data and code we used to count Oscar Bait value <br>

Dataset we used in project called main_data.csv. You can freely use it as you want <br>

The fields:<br>
*id* — Film id on IMDb <br>
*box* — Film box worldwide <br>
*budget* — Film budget <br>
*votes* — Number of votes on IMDb <br>
*rusian_title* — Russian name <br>
*original_title* — English name <br>
*year* — Release year <br>
*all_oscars_nom* — Number of Oscar nominations <br>
*oscars_wins* — Number of Oscar wins <br>
*genres* — Film genres <br>
*n_oscars_wins* — Number of main Oscar wins (Best Picture, Actors', Director's and Writers' nominations)<br>
*genres_tau*, *keywords_tau* — ML Features for genres and keywords <br>
*actors_nomineed* — Has any actor been nomineed for Oscar in last five years? <br>
*directors_nomineed* — Has any director been nomineed for Oscar in last five years? <br>
*writers_nomineed* — Has any writer been nomineed for Oscar in last five years? <br>
*major* — Was the film distributed by any of major studios? <br>
*indimajor* — Was the film distributed by any division of major studios? <br>
*days_from_year_start* — Film release date (days from year start)<br>
*mpaa_r* — Is the film have MPAA R rating? <br>
*best_pic_winner* — Has the film Oscar for Best Picture?<br>
*best_pic_nominee* — Has the film Best Picture nomination? <br>
*n_oscars_nom* — Number of main Oscar nominations  <br>
*dy_1*, *dy_2*, *dy_3*, *gr_low*, *gr_high*, *kw_low*, *kw_high* —  ML Features for release date, genres and keywords <br>
*problems* — Film's topics <br>
*(any_topic)_kwds* — Topic's special keywords <br>
*oscar appeal* — Oscar Appeal value (based on "Close, But No Cigar: The Bimodal Rewards to Prize-Seeking") <br>
*rating* — Oscar Bait Rating we used in publication (0-100 ranked for every year)<br>

We also share some of the data we downloaded from IMDb — it contains only titles that released in USA after 1990 and have genre, creators' info and at least 10 plot keywords. We can't share full dataset because its size is 2Gb.