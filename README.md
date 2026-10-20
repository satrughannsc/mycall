# mycall
Web RTC ka use kare ek web application repository for all audio and video for free open 
(PeerJS ka istemal karne par aapko koi bhi server setup karne ya terminal me commands chalane ki bilkul zaroorat nahi hai. PeerJS ka khud ka server free me aapki call ko connect karwa deta hai.
Aapko bas apne computer me ek simple HTML file banani hai. Chaliye ise step-by-step karte hain:

Step 1: Ek simple file banayein

Apne computer par ek naya document banayein aur uska naam index.html rakhein.

Step 2: Niche diye gaye code ko copy-paste karein

Is code ko poora copy karke apni index.html file me daal dein aur save kar lein:

Use code with caution.

Step 3: Isko test kaise karein?

1. Apne computer me is index.html file par double-click karke ise open karein. Browser aapko camera aur mic ki Permission mangega, use Allow kar dein.
2. Aapko screen par ek Call ID dikhegi (jaise: a8b2c3d4...). PAR YE NAHI DIKHN  RAHA THA KIYU KI IS KE LIYE
LIVE SERVER CHAHIYE THA
PHIR IS KE LIYE EK 
4. Is video call ko test karne ke liye, isi file ko ek doosre tab ya doosre browser window me open karein (ya kisi doosre computer par kholein).
5. Doosre tab me ek alag Call ID dikhegi. Pehle tab ki Call ID ko copy karein, doosre tab ke input box me dalein, aur "Call Karein" button par click kar dein!
Dono screens par video chalu ho jayegi bina kisi server setup ke jhanjhat ke.
Kya aapne is file ko banakar browser me chalu karke dekha? Agar isme koi bhi step samajh na aaya ho ya koi error dikhe, toh mujhe batayein!

index.html
file open to ho gaya par na to mic ka permission maga  nahi code genret ho raha hai abh kiya karu

Aapki file isliye kaam nahi kar rahi hai kyunki browsers (jaise Chrome ya Edge) security ke kaaran kisi bhi direct file (file:///...) ko camera aur mic ka access nahi dete hain jab tak wo kisi server par live na ho.
Is samasya ko door karne ke liye aapko koi coding nahi karni hai. Niche diye gaye dono me se koi bhi 1 aasan tarika chunlein, aapka code turant chal jayega:

Tarika 1: Live Server Extension (Sabse best aur aasan)

Agar aap VS Code (Visual Studio Code) editor ka istemal kar rahe hain:
1. VS Code ke left side me Extensions icon (chaar chhote squares) par click karein.
2. Search box me likhein: Live Server.
3. Install button par click karein.
4. Install hone ke baad, apni index.html file par right-click karein aur "Open with Live Server" par click kar dein.
5. Yeh automatic aapke browser me ek temporary live link open kar dega jahan camera permission bhi mangega aur ID bhi generate ho jayegi!

Tarika 2: Web Server for Chrome (Agar aap Chrome use karte hain)

Agar aap sirf Notepad use kar rahe hain aur browser me Chrome hai:
1. Google Chrome par Chrome Web Store kholein aur search karein: "Web Server for Chrome".
2. Is extension ko Chrome me add kar lein.
3. Extension ko open karein, wahan "Choose Folder" par click karke us folder ko select karein jahan aapki index.html file rakhi hai.
4. Wahan aapko ek web link dikhega (jaise http://127.0.0.1:8887). Us link par click karte hi aapki website bilkul sahi chalne lagegi!

Tarika 3: Chrome ki setting badlein (Bina kuch download kiye)

Agar aap bina kuch download kiye test karna chahte hain, toh Chrome ko batana padega ki is file ko safe maane:
1. Chrome browser me ek naya tab kholein aur address bar me yeh likh kar Enter karein: chrome://flags/#unsafely-treat-insecure-origin-as-secure
2. Wahan ek setting dikhegi "Insecure origins treated as secure".
3. Uske saamne wale box me apni file ka path copy-paste kar dein (jaise aapke browser ke address bar me file:///C:/... dikh raha hai).
4. Dropdown se use Enabled karein aur niche Relaunch button par click kar dein.
Aap in teeno me se kaun sa tarika try kar rahe hain? Agar kisi step me dikkat aaye ya "Live Server" dhoondhne me pareshani ho, toh mujhe batayein!

Chrome apps will no longer be supported in the future

Aapne bilkul sahi baat kahi! Google ne Chrome Apps ka support poori tarah band kar diya hai, isliye "Web Server for Chrome" jaisi apps ab Chrome Web Store par nahi milengi ya kaam nahi karengi. Is badlav ke liye main maafi chahta hoon, chaliye ab iska ekdum naya aur aasan tarika dekhte hain.
Bina kisi coding ke aur bina kisi Chrome app ke, aap in 2 modern aur aasan tariko se apni file ko chalu kar sakte hain:

Tarika 1: GitHub Pages par free me live karein (Sabse Best)

Aapko apne computer par kuch bhi install nahi karna padega. Aap apni index.html file ko internet par free me live kar sakte hain jisse camera/mic dono chalne lagenge:
1. GitHub par ek free account banayein (agar pehle se nahi hai).
2. Login karne ke baad, right side me upar "+" icon par click karke New repository chuniye.
3. Repository ka koi bhi naam rakh dein (jaise: mycall) aur use Public select karke "Create repository" par click karein.
4. Agle page par "uploading an existing file" ka link dikhega, us par click karein.
5. Apni index.html file ko wahan drag karke chhod (drop) dein aur niche Commit changes par click kar dein.
6. Ab repository ki Settings tab me jayein -> Left side me Pages par click karein -> Branch me None ko badalkar main ya master select karke Save kar dein.
7. 1-2 minute me aapko ek real website link mil jayega (jaise: https://github.io). Is link ko kholte hi camera permission aur peer ID dono kaam karne lagenge!

Tarika 2: CodeSandbox ya Replit use karein (Tur
