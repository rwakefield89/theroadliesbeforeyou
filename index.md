
vid playlist

    var list = 'PL8M2BTs8T8z48E5d8IlTg9ThDoq7c23aK'
    
    
    var listID = 'PL8M2BTs8T8z48E5d8IlTg9ThDoq7c23aK';
    

    var numberOfVideos = 17;
    

    var num = Math.floor(Math.random() * 200 + 1);
    
    var randomizer = Math.floor(Math.random() * numberOfVideos + 1);
   

    document.writeln('<iframe id="random-video" src="//www.youtube.com/embed/videoseries?list=' + list + '&index=' + num + '&autoplay=1&controls=0&modestbranding=1&showinfo=0" frameborder="0" allowfullscreen></iframe>');
    
    document.writeln('<iframe id="random-video" src="//www.youtube.com/embed/videoseries?list=' + listID + '&index=' + randomizer + '&autoplay=1&controls=0&modestbranding=1&showinfo=0" frameborder="0" allowfullscreen></iframe>');






