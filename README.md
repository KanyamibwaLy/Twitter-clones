<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Twitter Clone</title>
  <link rel="stylesheet" href="twitter.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">
</head>
<body>
  <div class="container">
    
    <!-- Sidebar -->
    <aside class="sidebar">
      <h2 class="logo"><i class="fa-brands fa-x-twitter"></i></h2>
      <nav>
        <a href="#" class="active"><i class="fa-solid fa-house"></i> Home</a>
        <a href="#"><i class="fa-solid fa-hashtag"></i> Explore</a>
        <a href="#"><i class="fa-regular fa-bell"></i> Notifications</a>
        <a href="#"><i class="fa-regular fa-envelope"></i> Messages</a>
      </nav>
      <button class="tweet-btn">Post</button>
    </aside>
    
    <!-- Feed -->
    <main class="feed">
      <header>
        <h2>Home</h2>
      </header>
      
      <div class="post-box">
        <img src="Image/My photo.jpg.jpg" alt="Profile">
        <input type="text" placeholder="What is happening?!">
      </div>
      
      <div class="tweet">
        <img src="Image/My photo.jpg.jpg" alt="Profile">
        <div>
          <h4>Lydia <span>@lydia · 2h</span></h4>
          <p>This is a sample tweet from my clone project 🚀</p>
          <img src="Image/twitter.jpg" class="post-img" alt="Tweet image">
        </div>
      </div>
    </main>
    
    <!-- Right Sidebar -->
    <aside class="rightbar">
      <h3>Trends for you</h3>
      <ul>
        <li>#HTML</li>
        <li>#CSS</li>
        <li>#Frontend</li>
      </ul>
    </aside>
    
  </div>
</body>
</html>
