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

function showVar(form) {
    console.log("This ran from the js file");
    
        var sum = form.elements["userEntry"].value;
    
        var arrayOfVal = sum.split(" ");
        console.log(arrayOfVal);
    
        var mean = 0;
        var sum = 0;
        for (index = 0; index < arrayOfVal.length; index++) {
            mean = mean + parseInt(arrayOfVal[index]);
            sum = sum + parseInt(arrayOfVal[index]);
        }
    
        //console.log(mean / arrayOfVal.length);
    
        mean = mean / arrayOfVal.length;
        sumMinusMean = userEntry - mean;
        console.log(sumMinusMean - mean);
    
        while (userEntry = 0)
            console.log(sumMinusMean ** 2);

            var totalSquaredDiff = 0;
            for (index = 0; index < arrayOfVal.length; index++) {
                squaredDiff = (arrayOfVal[index] ** 2) - mean
                totalSquaredDiff = totalSquaredDiff + squaredDiff
    
            }
        

        var arrayMiOne = arrayOfVal.length - 1;
        console.log(totalSquaredDiff / arrayMiOne);
}
![Screenshot 2022-11-29 182412](https://user-images.githubusercontent.com/119460519/204670433-2d6d930a-b2ae-4811-87c7-2849b7c83071.png)
