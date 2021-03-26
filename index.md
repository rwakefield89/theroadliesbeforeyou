
Vidisteo playl


// Playlist ID
    var listID = 'PL8M2BTs8T8z48E5d8IlTg9ThDoq7c23aK';
// Number of videos in playlist    
    var numberOfVideos = 17;
// Random number generator 
    var randomizer = Math.floor(Math.random() * numberOfVideos + 1);
// Embed video code
    document.writeln('<iframe id="random-video" src="//www.youtube.com/embed/videoseries?list=' + listID + '&index=' + randomizer + '&autoplay=1&controls=0&modestbranding=1&showinfo=0" frameborder="0" allowfullscreen></iframe>');




