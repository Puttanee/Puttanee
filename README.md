- 👋 Hi, I’m @Puttanee
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Puttanee/Puttanee is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
function showMean(form) {
    console.log("This ran from the js file");

    var user = form.elements["userEntry"].value;
    
    var arrayOfValue = user.split(" ");
   
    var userSum = 0;
    for (index = 0; index < arrayOfValue.length; index++) {
        userSum = userSum + parseInt(arrayOfValue[index]);
    }
    console.log(userSum / arrayOfValue.length);
    }
