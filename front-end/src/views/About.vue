<template>
<div>
  <div class="heading">
  <h1>About Me!</h1>
  </div>
  <div class="cent">
    <h1> My name is Nathan, and I'm hosting various competitions during the COVID-19 quarantine </h1>
  </div>
  <div class="cent">
    <h4> I am enthusiastic about competing. Having been raised in a household of 4 boys, I was constantly competing with my siblings. This pushed me to reach new bounds. In high school this pushed me to perform well in sports. Due to this drive, I worked hard to excel at swimming, my sport of choice. My hard work paid off. I competed against Olympians and eventually swam in college. I have seen how competition can push us to try new things and go to new heights. This website is a place for everyone to enter new competitions and learn new things. </h4>
  </div>
  <div class="cent">
    <h3> Please send me any contest suggestion for future months and let us start talking!</h3>
  </div>
  <div class="cent">
    <form action="mailto:nathanwallace512@gmail.com" method="post" enctype="text/plain">
      Name:<br>
      <input type="text" name="name"><br>
      E-mail:<br>
      <input type="text" name="mail"><br>
      Comment:<br>
      <input type="text" name="comment" size="50"><br><br>
      <input type="submit" value="Send">
    </form>
  </div>
</div>
</template>

<style scoped>
.image h2 {
  font-style: italic;
  font-size: 1em;
}

.cent {
  display: flex;
  align-items: center;
  margin: 20px;
  justify-content: center;
}

.heading {
  display: flex;
  margin-bottom: 20px;
  margin-top: 20px;
}

.heading h2 {
  margin-top: 8px;
  margin-left: 10px;
}

.add,
.edit {
  display: flex;
}

/* Form */
input,
textarea,
select,
button {
  font-family: 'Montserrat', sans-serif;
  font-size: 1em;
}

/* Suggestions */
.suggestions {
  width: 200px;
  border: 1px solid #ccc;
}

.suggestion {
  min-height: 20px;
}

.suggestion:hover {
  background-color: #5BDEFF;
  color: #fff;
}

.form {
  margin-right: 50px;
}

/* Uploaded images */
.upload h2 {
  margin: 0px;
}

.upload img {
  max-width: 300px;
}
</style>
