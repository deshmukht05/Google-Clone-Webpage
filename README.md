# Google-Clone-Webpage
#Here I have provided javascript code.

#main.js
const searchInput = document.querySelector("#search-input");
searchInput.addEventListener("keydown", function(event){
  if(event.code === "Enter"){
    search();
  }
});
function search(){
  const input = searchInput.value;
  window.location.href="https://www.google.com/search?q="+input+"&rlz=1C1CHZN_enIN963IN963&oq="+input+"&aqs=chrome..69i57j46i433i512j0i512l2j0i433i512j0i512j0i433i512j0i512j0i433j0i512.6621j0j15&sourceid=chrome&ie=UTF-8";
}
