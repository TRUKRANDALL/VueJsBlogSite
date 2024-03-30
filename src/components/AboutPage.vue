<template>
  <div class="about-page">
    <div class="about-content">
      <h1>About Me</h1>
      <div class="profile-details">
        <div class="profile-image"></div>
        <div class="profile-info">
          <h2>Kurt Randall S. Oviedo</h2>
          <p>Passionate Creator & Blogger</p>
          <p>Studied at Jose Maria College</p>
          <p>3rd year college BSIT student</p>
          <p>Age: 21</p>
          <p>Address: Purok 8 Communal, Buhangin, Davao City</p>
          <p>Follow me on social media:</p>
          <div class="social-icons">
            <a href="#"><img src="@/assets/fb.webp" alt="Facebook Icon"></a>
            <a href="#"><img src="@/assets/insta.png" alt="Instagram Icon"></a>
            <a href="#"><img src="@/assets/twitter.png" alt="Twitter Icon"></a>
            <a href="#"><img src="@/assets/linkin.webp" alt="LinkedIn Icon"></a>
            <a href="#"><img src="@/assets/tiktok.webp" alt="TikTok Icon"></a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'AboutPage',
}
</script>

<style scoped>
.about-page {
  padding: 50px;
  text-align: center;
  cursor: default;
}

.about-content {
  max-width: 800px;
  margin: 0 auto;
  cursor: default;
}

.profile-details {
  background-color: rgba(0, 0, 0, 0.9); /* Semi-transparent white background */
  border-radius: 10px;
  padding: 20px;
  margin-bottom: 30px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.profile-image {
  width: 200px;
  height: 200px;
  background-image: url('@/assets/profile.jpg');
  background-size: cover;
  border-radius: 50%;
  margin-right: 20px;
}

.profile-info {
  text-align: left;
}

.profile-info h2 {
  font-size: 2.5rem;
  margin-bottom: 10px;
}

.profile-info p {
  font-size: 1.2rem;
  margin-bottom: 15px;
}

.social-icons {
  display: flex;
  align-items: center;
  margin-top: 20px;
}

.social-icons a {
  margin-right: 10px;
}

.social-icons img {
  width: 30px;
  height: auto;
}

.social-icons a:last-child {
  margin-right: 0;
}
</style>
