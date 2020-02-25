Sierpinski Triangle
==================

The Sierpinski Triangle is a fractal. According to [Wikipedia](http://en.wikipedia.org/wiki/Sierpinski_triangle) it was named after "mathematician Waclaw Sierpinski who described it in 1915. However, similar patterns appear already in the 13th-century Cosmati mosaics in the cathedral of Anagni, Italy." You can create the Sierpinski Triangle (and very similar fractals) with surprisingly little code. The following picture and instructions are also from Wikipedia.

![Alt text](http://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Sierpinski_triangle_evolution.svg/512px-Sierpinski_triangle_evolution.svg.png)

Start with any triangle, though the usual Sierpinski triangle uses an equilateral triangle. Shrink the triangle to ½ height and ½ width, make three copies, and position the three shrunken triangles so that each triangle touches the two other triangles at a corner (image 2). Note the emergence of the central hole - because the three shrunken triangles can between them cover only 3/4 of the area of the original. (Holes are an important feature of Sierpinski's triangle.) Repeat step 2 with each of the smaller triangles (image 3 and so on).

Suggested steps to complete this assignment:
----------------------------------------------
1. You may find slides #1 - 39 of the [Recursion presentation](https://docs.google.com/presentation/d/18S0EB1FL7U0c7BobGplV5LJfJ7WHh5eJoJwVK_8yhyc/edit?usp=sharing) and  the [Recursion 1 worksheet](https://drive.google.com/open?id=0Bz2ZkT6qWPYTN2U4M2E5ZTQtMGFhMC00ZDY0LThiMGItODMwYzBiMGFiODdi) helpful.
2. Fork and clone down this repository (Optional: Create your own repository from scratch. Look at the bottom of this page for instructions)
2. Write the `sierpinski` function:

    * If `len` is less than or equal to 20 (or some variable) 
        * Draw a triangle with the left corner at (`x`,`y`) and a base and height equal to `len`.
    * else
        * recursively call the `sierpinksi` function to draw a triangle with the left corner at (`x`,`y`) and a base and height equal to `len/2`..
        
        * Again, call the `sierpinksi` function a second time to draw another triangle a distance of `len/2` to the right of the first triangle.
        * Now, call the `sierpinksi` function a third time to draw a triangle a distance of `len/4` to the right and `len/2` up from the first triangle. This triangle should "sit on top" of the first two.
3. Once you have the `sierpinksi` function completed, call it once in `draw()` to start the process. You can change the number and size of the triangles by changing the base case limit in the `if` from 20 to some variable and adjusting the value of the variable. Some ways to make the program interactive include using `mousePressed()`, `keyPressed()`, `mouseDragged()` or `mouseMoved()` to change the base case limit.
4. Feel free to create your own individual variation of the Sierpinski triangle. [Your recursive triangle doesn't have to look like any other](http://www.google.com/search?q=variations+on+a+theme+of+sierpinski&safe=active&es_sm=122&source=lnms&tbm=isch&sa=X&ei=Ku-uVP7vEJecoQSvwoCADg&ved=0CAoQ_AUoAw&biw=1280&bih=856&surl=1#safe=active&tbm=isch&q=variations+on+sierpinski+triangle&imgdii=_). It doesn't even need to use triangles. The mathematically adventurous might want to check out [the sierpinski triangle page to end most sierpinski triangle pages ™](http://www.oftenpaper.net/sierpinski.htm).
5. You could also create a [Sierpinski carpet](http://en.wikipedia.org/wiki/Sierpinski_carpet), Wallis sieve, [Hawaiian earring](https://en.wikipedia.org/wiki/Hawaiian_earring), Menger sponge or similiar as an alternative to the Sierpinski Triangle.

Optional: Create your own repository from scratch
-------------------------------------------------
It's not hard to create your own repostiory.    
1. Create a folder called SierpinskiTriangle in your apjava folder.    
2. Copy `processing.js` from a previous assignment and move it to the SierpinskiTriangle folder (Or, better practice, [download](http://processingjs.org/download/) the latest development version)    
3. Use Sublime to create the following 3 files, all of which are stored in the SierpinskiTriangle folder. Choose New File and then Save As and give the file the correct name    
    * `SierpinskiTriangle.pde`    
    * `index.html` (can be copied from a previous assignment, you will just need to change the canvas id tag in the body to match the name `SierpinskiTriangle`)    
    * `styles.css` (can be copied from a previous assignment)    
4. Now, go to GitHub and create a new empty SierpinskiTriangle repository. GitHub will provide the commands that you use to link your local SierpinskiTriangle folder to the GitHub repository    
5. To display your program on the web, you will want to enable GitHub pages. Go to the settings for your repository, scroll down to the GitHub pages section, choose `Master branch` and click *Save*.   

Samples of Student Work
-----------------------
[Mia](https://chenmia.github.io/SierpinskiTriangle/)   
[David](https://dactualchung.github.io/SierpinskiTriangle/)    
[Brandon](https://btlsandwich.github.io/SierpinskiTriangle/)   
[David](https://dachen18.github.io/SierpinskiTriangle/)   
[Henry](https://henryjack12.github.io/SierpinskiTriangle/)    
[Chris](https://whizardxd.github.io/APCS/Processing/SierpinskiTriangle/SierpinskiTriangle.html)   
[Nathan](https://natran951.github.io/SierpinskiTriangle/)   
[Lawrence](https://lawrencelowell.github.io/SierpinskiTriangle/)   
[Andy](https://anli28.github.io/SierpinskiTriangle/)   
[Anson](https://anyip4.github.io/SierpinskiTriangle/)   
[Raymond](https://luzray56.github.io/SierpinskiTriangle/)   
[Eric](https://3ricyu.github.io/SierpinskiTriangle/)   
[Andy](https://anwu1.github.io/SierpinskiTriangle/)   
[Gee](https://trtran8.github.io/SierpinskiTriangle/)   
[Timmy](https://tidang.github.io/SierpinskiTriangle/)   
[Sean](https://seanzep.github.io/SierpinskiTriangle/)   
[Richard](https://riprivalov.github.io/SierpinskiTriangle/)   
[Joshua](https://jowong1.github.io/SierpinskiTriangle/)   
[Jason](https://everyusernameitrywentwrong-jason-ye.github.io/SierpinskiTriangle/)    
[Frida](https://frida-calvo.github.io/SierpinskiTriangle/)    
[Amy](https://amychang415.github.io/SierpinskiTriangle/)   
[Ruixin](https://ruixinsun.github.io/SierpinskiTriangle/)   
[Christine](https://chmai3.github.io/SierpinskiTriangle/)   
[Ian](https://iatang21.github.io/SierpinskiTriangle/)   
[Andy](https://anwu1.github.io/SierpinskiTriangle/)   
[Kam](https://katam8.github.io/SierpinskiTriangle/)   
[Lucian](https://lucianli.github.io/SierpinskiTriangle/)   
[Jalen](https://jalenng.github.io/SierpinskiTriangle/)   
[Dalton](https://daltonnham.github.io/SierpinskiTriangle/)   
[Jessica](https://jessical26.github.io/SierpinskiTriangle/)   
[Diego](https://diegoleong.github.io/SierpinskiTriangle/)   
[Lauren](https://lauren-tran.github.io/SierpinskiTriangle/)   
[Emma](https://emmab3.github.io/SierpinskiTriangle/)   
[Lily](https://cailcali.github.io/SierpinskiTriangle/)   
[Jayde](https://jaydewong.github.io/SierpinskiTriangle/)   
[Gordon](https://goyee.github.io/SierpinskiTriangle/)   
[Calvin](https://callmecalvin808.github.io/SierpinskiTriangle/)   
[Alex](https://apcsalex.github.io/SierpinskiTriangle/)   
[Norton](https://nomvus.github.io/SierpinskiTriangle/)    
[Marc](https://alltheusernamesdontworkexceptmine.github.io/SierpinskiTriangle/)   
[Esme](https://esmedpk.github.io/SierpinskiTriangle/)   
[Daniel](https://danieldoan101.github.io/SierpinskiTriangle/)   
[Jessie](https://ie-jess.github.io/SierpinskiTriangle/)   
[Alvin](https://alvin4ever.github.io/SierpinskiTriangle/)   
[Carmen](https://carmenli14.github.io/SierpinskiTriangle/)   
[Jennifer](https://jp4099.github.io/SierpinskiTriangle/)   
[Michelle](https://michellet1682.github.io/SierpinskiTriangle/)   
[Freesia](https://freesiaf.github.io/SierpinskiTriangle/)   
[Iryne](https://irynechu.github.io/SierpinskiTriangle/)   
[Esther](https://estherchung83.github.io/SierpinskiTriangle/)   
[Vicky](https://vickyguan3.github.io/SierpinskiTriangle/)   
[Eloy](https://eloyeluo.github.io/SierpinskiTriangle/)   
[Angela](https://angelaapcsa.github.io/SierpinskiTriangle/)   
[Adam](https://norwegianwoods.github.io/SierpinskiTriangle/)   
[Brendan](https://brleunga.github.io/SierpinskiTriangle/)   
[Andy](https://kimbx.github.io/SierpinskiTriangle/)   
[Lianne](https://liwong10.github.io/SierpinskiTriangle/)   
[Melinda](https://melindali255.github.io/SierpinskiTriangle/)   
[Ryan](https://someguy13.github.io/SierpinskiTriangle/)   
[Ravi](https://ravik0.github.io/SierpinskiTriangle/)   
[Slavik](https://21slavik.github.io/SierpinskiTriangle/)   
[Chris](https://chrisc641.github.io/SierpinskiTriangle/)   
[Emily](https://emchen1.github.io/SierpinskiTriangle/)   
[Joey](https://eggcarton.github.io/SierpinskiTriangle/)   
[Jonathan](https://jonathan109.github.io/SierpinskiTriangle/)   
[Alex](http://alexruiz.me/SierpinskiTriangle/)     
[Ryan](https://rylee12.github.io/SierpinskiTriangle/)   
[Emma](https://emblenkinsop.github.io/SierpinskiTriangle/)   
[Gordon](https://milkteadailo.github.io/SierpinskiTriangle/)   
[Andrew](https://drewren25.github.io/SierpinskiTriangle/)   
[Joe](https://joehuang1108.github.io/SierpinskiTriangle/)   
[Albert](https://albertma222.github.io/SierpinskiTriangle/)   
[Mike](https://mimonokandilos.github.io/SierpinskiTriangle/)   
[Kenny](https://kennyyu168.github.io/SierpinskiTriangle/)   
[Victor](https://kingvictor.github.io/SierpinskiTriangle/)   
[Desmond](https://djmond.github.io/SierpinskiTriangle/)   
[Farya](https://darya-ver.github.io/SierpinskiTriangle/)   
[Garvin](https://garvingit.github.io/SierpinskiTriangle/)   
[Preston](https://prestonttt.github.io/SierpinskiTriangle/)   
[Jayden](https://jaydenlee1229.github.io/SierpinskiTriangle/)   
[Makoi](https://magacula1.github.io/SierpinskiTriangle/)   
[Thanawat](https://thiskappaisgrey.github.io/SierpinskiTriangle/index.html)   
[Lydia](https://aqua28.github.io/SierpinskiTriangle/)   
[Heath](https://heathexer.github.io/SierpinskiTriangle/)   
[Kennety](https://kenpaso.github.io/SierpinskiTriangle/)  
[Kirby](https://krbyktl.github.io/SierpinskiTriangle/)   
[Andrea](https://chenandrea29.github.io/SierpinskiTriangle/)   
[Aaron](https://aahuangithub.github.io/SierpinskiTriangle/)   
[Erica](https://ericamalia.github.io/SierpinskiTriangle/)   
[Vivian](https://viviaann.github.io/SierpinskiTriangle/)   
[Sophie](https://sohuang.github.io/SierpinskiTriangle/)   
[Otto](https://otschmidt.github.io/SierpinskiTriangle/)   
[Joshua](https://joshualchan.github.io/SierpinskiTriangle/)   
[Michael](https://mipsim.github.io/SierpinskiTriangle/)   
[Eric](https://jellybeanmill.github.io/SierpinskiTriangle/)   
[Karen](https://sonokjw.github.io/SierpinskiTriangle/)   
[Hannah](https://hadecastro.github.io/SierpinskiTriangle/)   
[Erica](https://ekwkk.github.io/SierpinskiTriangle/)   
[Yolanda](https://yofeng.github.io/SierpinskiTriangle/)   
[Janet](https://birded.github.io/SierpinskiTriangle/)   
[Nathan](https://nathansng.github.io/SierpinskiTriangle/)   
[Felix](https://felixzhuk.github.io/SierpinskiTriangle/)   
[Mi-Kaela](https://mikamarciales.github.io/SierpinskiTriangle/)   
[Kervin](https://kekuang2.github.io/SierpinskiTriangle/)   
[Joanna](https://j0annalu.github.io/SierpinskiTriangle/)   
[Emma](https://emmackenzie.github.io/SierpinskiTriangle/)   
[Andrew](https://andrewmai123.github.io/SierpinskiTriangle/)   
[Schuyler](https://skschur1.github.io/SierpinskiTriangle/)   
[Ryan](https://avath.github.io/SierpinskiTriangle/)   
[Steven](https://sjkchang.github.io/SierpinskiTriangle/)   
[Katie](https://kachow4.github.io/SierpinskiTriangle/)   
[Elton](https://elel123.github.io/SierpinskiTriangle/)   
[Colin](https://licolin4.github.io/SierpinskiTriangle/)   
[Raymond](https://ngoraymond.github.io/SierpinskiTriangle/)   
[Preston](https://prestonttt.github.io/SierpinskiTriangle/)   
[Eric](https://ersun1224.github.io/SierpinskiTriangle/)   
[Anya](http://anyacakes.github.io/SierpinskiTriangle/)  
[Nathan](http://nalam1.github.io/SierpinskiTriangle/)   
[Sasha](http://sashagonzalez.github.io/SierpinskiTriangle/)  
[Oliver](http://olivernoss.github.io/SierpinskiTriangle/)  



