<script setup lang="ts"></script>

<template>
  <div class="container">
    <!-- Profile Picture -->
    <img
      src="/src/assets/Jannah.jpg"
      alt="My Picture"
      class="profile-picture"
    />

    <!-- Personal Information Card -->
    <div class="card">
      <h1 style="font-weight: bold">Nurul Jannah Amal Insyirah</h1>
      <h2>Student</h2>
      <p>Politeknik Brunei</p>
    </div>

    <!-- Education Information -->
    <div class="card">
      <h2><b>Education</b></h2>
      <p>Diploma Level 5 in Web Development</p>
      <p>Hntec in Information Library Studies</p>
      <p>IBTE Sultan Saiful Rijal Campus</p>
      <p>Graduated: June 2020</p>
    </div>

    <!-- Project Information -->
    <div class="card">
      <h2><b>Project</b></h2>
      <p>7 Puak Jati Brunei Exhibition, 2020</p>
    </div>

    <!-- Contact Information -->
    <div class="card">
      <h2><b>Contact</b></h2>
      <p>Email: 22FTT1498@student.pb.edu.bn</p>
      <p>Phone: +673 816 1234</p>
      <p>Website: <a href="http://www.example123.com">www.example123.com</a></p>
    </div>
  </div>
</template>

<style scoped>
.container {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
}

.profile-picture {
  width: 150px;
  height: 150px;
  object-fit: cover;
  border-radius: 50%;
  display: block;
  margin: 0 auto;
  border: 2px solid white;
}

.card {
  background-color: #f9f9f9;
  padding: 20px;
  border-radius: 10px;
  margin-top: 20px;
  text-align: center;
  box-shadow: 0 4px 8px rgba(255, 255, 255, 0.3); /* White shadow effect */
}

.card h1,
.card h2,
.card p {
  color: black;
  font-size: 20px;
  margin-bottom: 10px;
}

.card h1 {
  font-weight: bold;
}
</style>
