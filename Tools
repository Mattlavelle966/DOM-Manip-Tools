
//time looper that starts at a selected time and allows you to wait till a specific time param is met and it re loops for the specified iterations.
async () => {
  const sleep = ms => new Promise(resolve => setTimeout(resolve, ms));
   document.querySelector('video').currentTime = 0;  
  for (let count = 0; count < 100; count++) {
    console.log("waiting...");
    await sleep(61800); // wait 108 seconds
    document.querySelector('video').currentTime = 0; 
  }
})();
