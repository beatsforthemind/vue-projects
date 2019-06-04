<template>
  <section>
    <header class="hero-image">
      <div class="hero-text">
        <h1>Merlin Movie House</h1>
      </div>
    </header>
    <main>
      <h2>A Cinematic Experience</h2>
      <p>Merlin Movie House is a place where all your film dreams come true. Ride a dragon, fight a jedi, kiss a toad...</p>
      <hr />
      <h2>Now Playing</h2>
      
      <!--
      <div class="card" style="width: 18rem;">
        <img class="card-img-top" :alt="movie.Title" :src="movie.Poster">
        <div class="card-body">
          <h5 class="card-title">Card title</h5>
          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
          <a href="#" class="btn btn-primary">Go somewhere</a>
          <div v-if="movie">
            {{ movie.Title }}<br />
            {{ movie.Year }}<br />
            {{ movie.Rated }}<br />
            {{ movie.Released }}<br />
            {{ movie.Runtime }}<br />
            {{ movie.Genre }}<br />
            {{ movie.Director }}<br />
            {{ movie.Writer }}<br />
            {{ movie.Actors }}<br />
            {{ movie.Plot }}<br />
            {{ movie.Language }}<br />
            {{ movie.Country }}<br />
            {{ movie.Awards }}<br />
            {{ movie.Poster }}<br />
            {{ movie.Ratings }} ARRAY<br />
            {{ movie.Metascore }}<br />
            {{ movie.imdbRating }}<br />
            {{ movie.imdbVotes }}<br />
            {{ movie.imdbVotes }}<br />
          </div>

        </div>
      </div>
      --> 
      
      <!--
      <div v-if="movies">
        <div style="display: block;">
          {{ movies }}
        </div>        
        <div v-for="item in movies.Search">
          <div style="display: none;">
            {{ item }}
          </div>
          <div class="card" style="width: 18rem;">
            <img class="card-img-top" :alt="item.Title" :src="item.Poster">
            <div class="card-body">
              <h5 class="card-title">{{ item.Title }}</h5>
              <p class="card-text">{{ item.Plot }}</p>
              <a href="#" class="btn btn-primary">Visit on OMDB</a>
            </div>
          </div>
        </div>
      </div>
      -->
      
      <div v-if="movie1">
        <!-- {{ movie1 }} -->
        <div class="card" style="width: 18rem;">
          <img class="card-img-top" :alt="movie1.Title" :src="movie1.Poster">
          <div class="card-body">
            <h5 class="card-title">{{ movie1.Title }}</h5>
            <p class="card-text">{{ movie1.Plot }}</p>
            <a :href="movie1.Website" class="btn btn-primary">Visit website</a>
            
            <!--
            <div v-if="movie1">
              {{ movie1.Title }}<br />
              {{ movie1.Year }}<br />
              {{ movie1.Rated }}<br />
              {{ movie1.Released }}<br />
              {{ movie1.Runtime }}<br />
              {{ movie1.Genre }}<br />
              {{ movie1.Director }}<br />
              {{ movie1.Writer }}<br />
              {{ movie1.Actors }}<br />
              {{ movie1.Plot }}<br />
              {{ movie1.Language }}<br />
              {{ movie1.Country }}<br />
              {{ movie1.Awards }}<br />
              {{ movie1.Poster }}<br />
              {{ movie1.Ratings }}<br />
              {{ movie1.Metascore }}<br />
              {{ movie1.imdbRating }}<br />
              {{ movie1.imdbVotes }}<br />
              {{ movie1.imdbVotes }}<br />
              {{ movie1.imdbID }}<br />
              {{ movie1.DVD }}<br />
              {{ movie1.BoxOffice }}<br />
              {{ movie1.Production }}<br />
              {{ movie1.Website }}<br />
            </div>
            -->
  
          </div>
        </div>
      </div>
      
      <div v-if="movie2">
        <!-- {{ movie2 }} -->
        <div class="card" style="width: 18rem;">
          <img class="card-img-top" :alt="movie2.Title" :src="movie2.Poster">
          <div class="card-body">
            <h5 class="card-title">{{ movie2.Title }}</h5>
            <p class="card-text">{{ movie2.Plot }}</p>
            
            <a :href="movie2.Website" class="btn btn-primary">Visit website</a>
            
            <!--
            <div v-if="movie2">
              {{ movie2.Title }}<br />
              {{ movie2.Year }}<br />
              {{ movie2.Rated }}<br />
              {{ movie2.Released }}<br />
              {{ movie2.Runtime }}<br />
              {{ movie2.Genre }}<br />
              {{ movie2.Director }}<br />
              {{ movie2.Writer }}<br />
              {{ movie2.Actors }}<br />
              {{ movie2.Plot }}<br />
              {{ movie2.Language }}<br />
              {{ movie2.Country }}<br />
              {{ movie2.Awards }}<br />
              {{ movie2.Poster }}<br />
              {{ movie2.Ratings }}<br />
              {{ movie2.Metascore }}<br />
              {{ movie2.imdbRating }}<br />
              {{ movie2.imdbVotes }}<br />
              {{ movie2.imdbVotes }}<br />
              {{ movie2.imdbID }}<br />
              {{ movie2.DVD }}<br />
              {{ movie2.BoxOffice }}<br />
              {{ movie2.Production }}<br />
              {{ movie2.Website }}<br />
            </div>
            -->
  
          </div>
        </div>
      </div>

      <div v-if="movie3">
        <!-- {{ movie3 }} -->
        <div class="card" style="width: 18rem;">
          <img class="card-img-top" :alt="movie3.Title" :src="movie3.Poster">
          <div class="card-body">
            <h5 class="card-title">{{ movie3.Title }}</h5>
            <p class="card-text">{{ movie3.Plot }}</p>
            <a :href="movie3.Website" class="btn btn-primary">Visit website</a>
            
            <!--
            <div v-if="movie3">
              {{ movie3.Title }}<br />
              {{ movie3.Year }}<br />
              {{ movie3.Rated }}<br />
              {{ movie3.Released }}<br />
              {{ movie3.Runtime }}<br />
              {{ movie3.Genre }}<br />
              {{ movie3.Director }}<br />
              {{ movie3.Writer }}<br />
              {{ movie3.Actors }}<br />
              {{ movie3.Plot }}<br />
              {{ movie3.Language }}<br />
              {{ movie3.Country }}<br />
              {{ movie3.Awards }}<br />
              {{ movie3.Poster }}<br />
              {{ movie3.Ratings }}<br />
              {{ movie3.Metascore }}<br />
              {{ movie3.imdbRating }}<br />
              {{ movie3.imdbVotes }}<br />
              {{ movie3.imdbVotes }}<br />
              {{ movie3.imdbID }}<br />
              {{ movie3.DVD }}<br />
              {{ movie3.BoxOffice }}<br />
              {{ movie3.Production }}<br />
              {{ movie3.Website }}<br />
            </div>
            -->
  
          </div>
        </div>
      </div>

    </main>
  </section>
</template>

<script>
import axios from 'axios';

export default {
  data() {
    return {
      loading: true,
      movie: null,
      movieTitle: null,
      movies: null,
      movie1: null,
      movie2: null,
      movie3: null,
      errored: false,
    };
  },
  mounted () {
    
    /*
    // SINGLE REQUEST FOR ONE MOVIE
    axios.get('http://www.omdbapi.com/?t=her&apikey=29917929')
      .then(response => (
        this.movie = response.data,
        this.movieTitle = response.data.Title
      ))
      .catch(error => {
        console.log(error)
        this.errored = true
      })
      .finally(() => this.loading = false);
    */
    /*
    // SEARCH REQUEST FOR MULTIPLE MOVIES -> ARRAY OF MOVIES IN 'SEARCH' PROPERTY
    axios.get('http://www.omdbapi.com/?s=wars&apikey=29917929')
      .then(response => (
        this.movies = response.data
      ))
      .catch(error => {
        console.log(error)
        this.errored = true
      })
      .finally(() => this.loading = false)
    */
    
    // REQUESTS FOR MULTIPLE SINGLE MOVIES
    axios.all([
      axios.get('http://www.omdbapi.com/?t=her&apikey=29917929'),
      axios.get('http://www.omdbapi.com/?t=gigli&apikey=29917929'),
      axios.get('http://www.omdbapi.com/?t=citizen_kane&apikey=29917929'),
    ])
    .catch(error => {
      console.log(error)
      this.errored = true
    })
    .then(axios.spread((res1, res2, res3) => {
      this.movie1 = res1.data
      this.movie2 = res2.data
      this.movie3 = res3.data
    }))
    .finally(() => this.loading = false)
    
  }
}
</script>

<style>
/* Styling for main hero image */
.hero-image {
  background-image: url('../assets/header.jpg');
  background-repeat: no-repeat;
  background-size: cover;
  background-position: bottom;
  position: relative;
  height: 600px;
  width: 100%;
}

/* Text laying over hero image */
.hero-text {
    text-align: center;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: white;
}
header h1 {
  font-family: Limelight, sans-serif;
  font-size: 5em;
  font-weight: bold;
  text-transform: uppercase;
  text-shadow: 2px 2px black;
}

main {
  margin: 2rem 3rem;
  font-family: Merriweather;
}

nav {
  font-family: Merriweather;
}

/* ### */
.card {
  float: left;
}
/* ### */
</style>
