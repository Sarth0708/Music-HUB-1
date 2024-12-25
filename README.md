# Music-HUB-1

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-widt>, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css" integrity="sha512-Kc323vGBEqzTmouAECnVceyQqyqdsSiqLQISBL29aUW4U/M7pSPA/gEUZQqv1cwx4OnYxTxve5UMg5GT6L4JJg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="icon" href="./assets/logo.png">
    <title>Suniyee - Web Player: Music for everyone</title>
    <link rel="stylesheet" href="styleb1.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">
</head>
<body>
    <div class="main">
        <div class="sidebar">
            <div class="nav">
                <div class="nav-option" style="opacity: 2;">
                    <i class="fa-solid fa-house"></i>
                    <a href="#">Home</a>
                </div>
                <div class="nav-option">
                    <i class="fa-solid fa-magnifying-glass"></i>
                    <a href="#">Search</a>
                </div>
            </div>
            <div class="library">
                <div class="option">
                    <div class="lib-option nav-option">
                        <img src="./assets/library_icon.png">
                        <a href="#">Your Library</a>
                    </div>
                    <div class="icons">
                        <i class="fa-solid fa-plus"></i>
                        <i class="fa-solid fa-arrow-right"></i>
                    </div>
                </div>
                <div class="lib-box">
                    <div class="box">
                        <p class="box-p1">Create your first playlist</p>
                        <p class="box-p2">It's easy, we'll help you</p>
                        <button class="badge">Create playlist</button>
                    </div>
                    <div class="box">
                        <p class="box-p1">Let's find some podcasts to follow</p>
                        <p class="box-p2">we'll keep you updated on new episodes</p>
                        <button class="badge">Browse podcasts</button>
                    </div>
                </div>
            </div>
        </div>
        <div class="main-content">
            <div class="sticky-nav">
                <div class="sticky-nav-icons">
                    <img src="./assets/backward_icon.png">
                    <img src="./assets/forward_icon.png" class="hide">      
                </div>
                <div class="sticky-nav-options">
                <button class="badge nav-item hide">Explore Premium</button>
                <button class="badge nav-item dark-badge"><i class="fa-regular fa-circle-down" style="margin-right: 5px;"></i>Install App</button>
                <i class="fa-regular fa-user nav-item"></i>
                </div>
            </div>
            
            <h2>Recently Played</h2>
            <div class="card-container">
                <div class="card">
                    <img src="./assets/card1img.jpeg" class="card-img">
                    <p class="card-title">Top 50 - Global</p>
                    <p class="card-info">Your daily update of the most played...</p>
                </div>
            </div>


            <h2>Trending now near you</h2>
            <div class="card-container">
                <div class="card">
                    <img src="./assets/card6img.jpeg" class="card-img">
                    <p class="card-title">Top Songs - India</p>
                    <p class="card-info">Your daily update of the most played...</p>
                </div>
                <div class="card">
                    <img src="./assets/card2img.jpeg" class="card-img">
                    <p class="card-title">Love Songs</p>
                    <p class="card-info">Your daily update of the most played...</p>
                </div>
                <div class="card">
                    <img src="./assets/card3img.jpeg" class="card-img">
                    <p class="card-title">Top 50 - Ghazals</p>
                    <p class="card-info">Your daily update of the most played...</p>
                </div>
                <div class="card">
                    <img src="./assets/card4img.jpeg" class="card-img">
                    <p class="card-title">Pop Songs</p>
                    <p class="card-info">Your daily update of the most played...</p>
                </div>
                <div class="card">
                    <img src="./assets/card5img.jpeg" class="card-img">
                    <p class="card-title">Top 50 - Global</p>
                    <p class="card-info">Your daily update of the most played...</p>
                </div>
            </div>
            <h2>Featured Charts</h2>
            <div class="card-container">
                <div class="card">
                    <img src="./assets/card3img.jpeg" class="card-img">
                    <p class="card-title">Top 50 - Ghazals</p>
                    <p class="card-info">Your daily update of the most played...</p>
                </div>
                <div class="card">
                    <img src="./assets/card4img.jpeg" class="card-img">
                    <p class="card-title">Pop Songs</p>
                    <p class="card-info">Your daily update of the most played...</p>
                </div>
                <div class="card">
                    <img src="./assets/card6img.jpeg" class="card-img">
                    <p class="card-title">Top Songs - India</p>
                    <p class="card-info">Your daily update of the most played...</p>
                </div>
                <div class="card">
                    <img src="./assets/card7img.jpeg" class="card-img">
                    <p class="card-title">Devotion songs</p>
                    <p class="card-info">Your daily update of the most played...</p>
                </div>
            </div>
            <div class="footer">
                <div class="line"></div>
            </div>

        </div>
        <div class="music-player">
            <div class="album">
                <img src="./assets/bonita_icon.png" class="bonita">
                <div class="name1" style="opacity: 1;">Bonita</div>
                <div class="name2">Yo Yo Honey Singh</div>
              
            </div>
            <div class="player">
                <div class="player-controls">
                    <img src="./assets/player_icon1.png" class="player-control-icon">
                    <img src="./assets/player_icon2.png" class="player-control-icon">
                    <img src="./assets/play_musicbar1.png" class="player-control-icon" style="opacity: 1; height: 2rem;">
                    <img src="./assets/player_icon4.png" class="player-control-icon">
                    <img src="./assets/player_icon5.png" class="player-control-icon">
                </div>
                <div class="playback-bar">
                    <span class="curr-time">00:00</span>
                    <input type="range" min="0" max="100" class="progress-bar" step="1">
                    <span class="tot-time">3:33</span>
                </div>
            </div>
            <div class="controls">
                <i class="fa-solid fa-rectangle-list"></i>
                <i class="fa-solid fa-microphone"></i>
                <i class="fa-solid fa-folder-closed"></i>
                <i class="fa-solid fa-volume-low"></i>
                <input type="range" class="range1">

        </div>
    </div>
</body>
</html>
