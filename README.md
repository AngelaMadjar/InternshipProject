# Spotify ML App & Jupyter Notebooks

![spotify](https://user-images.githubusercontent.com/74113692/116729820-edf92600-a9e7-11eb-91d7-3fb6e26468ae.png)


In this repository I have attached 6 notebooks in which I work with the 6 Spotify datasets available on
the following link: https://www.kaggle.com/yamaerenay/spotify-dataset-19212020-160k-tracks .

I developed an interactive real-time web application that displays the obtained results with different
clustering algorithms. The user is able to choose a dataset, a dimensionality reduction method,
a clustering algoritm as well as the number of clusters for some of the algorithms. 
The visualizations are shown in realtime depending on the user's choices.

The app can be run by executing the command **streamlit run 'local-project-path'** in the terminal.
(Before running the app, all of the datasets available on the kaggle link provided above should be uploaded to the sub-directory **datasets**.)

Please note that loading the visualizations might take some time because of the large size of the datasets.

I have also included files that contain all the requirements (*requirements.txt*),
imported packages (*imported_packages.txt*) as well as the virtual environment I was working in (*environment.yml*).

I deployed the app on Docker and a Network URL was generated. Unfortunately, I got the *ERR_CONNECTION_TIMED_OUT*
Error when I tried loading the link in the browser. I believe that with all the files provided, the app
can be run locally with the command **streamlit run main.py** in terminal. A Local URL should be generated and
the app should be opened in the browser.

I am pasting some screenshots from the app bellow:

![pic1](https://user-images.githubusercontent.com/74113692/116729602-a4a8d680-a9e7-11eb-9ebd-bdb070aa23bd.png)
![pic3](https://user-images.githubusercontent.com/74113692/116729648-b25e5c00-a9e7-11eb-8e07-87c3393541d3.png)
![pic4](https://user-images.githubusercontent.com/74113692/116729673-ba1e0080-a9e7-11eb-9ee1-2e58f5d03e59.png)
