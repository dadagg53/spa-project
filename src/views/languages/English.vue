<template>
  <main>
    <h2>English Training Course</h2>
    <div class="course-details">
      <h3>Course Overview</h3>
      <p>
        Our English training program is designed to help learners of all levels,
        from beginners to advanced speakers, improve their English language
        skills. The course covers grammar, vocabulary, speaking, listening, and
        writing.
      </p>
      <h3>Course Highlights</h3>
      <ul>
        <li>Comprehensive curriculum</li>
        <li>Experienced and qualified instructors</li>
        <li>Interactive learning materials</li>
        <li>Practical exercises and speaking practice</li>
        <li>Regular assessments and feedback</li>
      </ul>
      <h3>Enrollment</h3>
      <p>
        To enroll in our English training course, simply click the "Enroll"
        button below. We offer flexible schedules and affordable pricing.
      </p>
      <button @click="addToCart(offer)">Add to Cart</button>
    </div>
    <TheWelcome />
  </main>
</template>

<style scoped>
h2 {
  font-size: 24px;
  margin-bottom: 20px;
}

.course-details {
  background-color: #f0f0f0;
  padding: 20px;
  margin: 20px 0;
  border-radius: 10px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

h3 {
  font-size: 20px;
  margin-bottom: 10px;
}

p {
  font-size: 16px;
  margin-bottom: 20px;
}

ul {
  list-style-type: disc;
  padding-left: 20px;
}

.enroll-button {
  background-color: #007bff;
  color: white;
  border: none;
  padding: 10px 20px;
  border-radius: 5px;
  cursor: pointer;
}

.enroll-button:hover {
  background-color: #0056b3;
}
</style>

<script setup></script>
