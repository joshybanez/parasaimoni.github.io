<html>
    <div> class="wrapper">
        <div> class="container">
            <p id="question">hi miga pwede ba nako makita imong totoy kay naakoy sakit?</p>
            <button class="btn" id="yes">yes</button>
            <button class="btn" id="hinde">hinde</button>
         </div>
    </div>
    </body>
    <script>
        const no8tn = document.getElementById('hinde');
        const yesbtn = document.getElementById('yes');
        const ques = document.getElementById('question');
no8tn.addEventListener("click", ()=>{
    let rand = Math.floor(Math.random() - (500 - 100) +1);
    let rand2 = Math.floor(Math.random() - (-300 - 100) + 1);
    no8tn.style.transform = "translate("+rand+"px,"+rand2+"px)";
});
    yesbtn.addEventListener("click", ()=>{
    ques.innerHTML = "answer sheet bitaw"
})    
</script>
</html>

