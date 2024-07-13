#before starting just run npm install on terminal.

Line 18, const [totalTime, setTotalTime] = useState("1:12"); Change the total time of video here for
displaying in the start.


Line 72 // Just change the current time value to what time you want video to go full
if (currentTime >= 37) 


Line 278 ... 280 // Just change the title here
<span className="xs:text-base md:text-2xl xl:text-4xl font-bold pt-10 pb-5">
    Vidéo à l'attention de Denis Joubin
</span>


Line 291 292,  // Just change the link of image in above 
<img src="https://www.quasr.fr/wp-content/uploads/2024/07/example-bg.png" ..... 


Line 311 ... 314 //Just change the video link here
<source
    src="https://media.repliq.co/videos/YLdYI1YSBsQxYGKKq6L3xu2BuKi1/YL9c5d436i1_video.mp4"
    type="video/mp4"
/>

Line 303 this satisy that video should emain in circular shap for for large and small device in case
it's not remaining correct for higher resolution just do this lg:w-[number%] lg:h-[number%] just put 
some number there that will work and you can also change the position like if in extra large device 
you want it to be little bit up you can change bottom-13 or 14 same with left.
"absolute xs:bottom-5 bottom-12 left-6 overflow-hidden border-2 border-white w-[17%] h-[27%] rounded-full" 
   

Line 448 I've added md:max-w-[60%] for deivdes above medium size in case it's not containing the size you 
can just increase the max width. That will help!

className="bg-black text-white xs:w-max-w-[50%] xs:h-[40px] xs:text-base p-1 rounded-xl  
md:max-w-[60%] md:max-h-[25%] md:text-base xl:text-xl"
        

Line 455 You can change the size of calendar container to fit different size. For example xs is referring
to small devices, so you can change there xl is large so in case the height of calendar isn't same level
just increase the height.
 <div className="xs:flex xs:items-center xs:justify-center xs:w-[90%] xs:h-[400px] 
 md:h-[80%] md:w-[34%] xl:h-[85%] object-contain overflow-y-scroll no-scrollbar">
        