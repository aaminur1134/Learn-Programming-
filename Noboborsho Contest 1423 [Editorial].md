[Editorial: নববর্ষ কনটেস্ট ১৪২৩](https://algo.codemarshal.org/contests/noboborsho-1423)
--------------------------------------------- 

------------------------------- 

প্রোগ্রামিং কনটেস্টের মাধ্যমে বিভিন্ন বিশেষ দিবস পালনের ধারাবাহিকতায় গত ১৮ এপ্রিল ২০১৬ ইং তারিখে আয়োজন করা হয়েছিল **নববর্ষ কনটেস্ট ১৪২৩**। আমাদের গ্রুপের পক্ষ থেকে আয়োজিত এ যাবৎ কালের সবচেয়ে বেশি কনটেস্ট্যান্টদের অংশগ্রহন ছিল এই কনটেস্টে। একই সাথে ক'জন বিশ্ব সেরা প্রোগ্রামারদের পেয়েছিলাম জাজ হিসেবে। এটাও আমাদের অনেক বড় অর্জন।<br>
প্রবলেমগুলোর শিরোনামে ক্লিক করলে মূল প্রবলেম ডেস্ক্রিপশন পাওয়া যাবে। এখনো কোন অনলাইন জাজে এগুলো আপলোড করা হয় নি। ২-১ দিনের মধ্যে আপলোড হলে ফাইলে এড করে দেয়া হবে।<br>
গ্রুপ কর্তৃক আয়োজিত সকল কনটেস্টের লিংক পাওয়া যাবে এখানেঃ https://goo.gl/gQ0zrK 

সবাইকে ধন্যবাদ। :) <br> <br>

#### [A. খাঁজ কাটা… খাঁজ কাটা… খাঁজ কাটা…](https://algo.codemarshal.org/contests/noboborsho-1423/problems/A) <br>
Problem setter: [Hasan Abdullah](https://www.facebook.com/hasan.cse91)

এক লাইনে 50000 3500 প্রিন্ট করাই ছিল এই প্রবলেমের কাজ। ৩৫০০ এর পরে একটা new line প্রিন্ট না করায় অনেকের AC হয় নি।

এপিক পয়েন্ট ১ঃ
এক ছোট ভাই নক দিয়ে জিজ্ঞেস করল "ভাই এইটা কি DP problem?”

এপিক পয়েন্ট ২ঃ
আরেক জন বলল ভাই উইকিপিডিয়ায় দেখলাম সৈন্য সংখ্যা অমুক। ঐটা দিলে হবে না?
 
#### [B . ঘোড়ার ডিম](https://algo.codemarshal.org/contests/noboborsho-1423/problems/B) 
Problem setter: [Soummyo Sarkar Avik](https://www.facebook.com/avik.sarkar.77) <br>
Alternate Writer : [Khairul Basar Rofi](https://www.facebook.com/Omaanuushh)  <br>

কেস ১ঃ যদি ডিম এর পরিমান 0 হয় তাহলে Answer সবসময় 0 হবে। [ যেহেতু 0 টা ডিম সেদ্ধ করতে 0 Seconds টাইম লাগবে এবং কোন পাত্রের ও দরকার হবে না । ] <br>
কেস ২ঃ যদি ডিম এর পরিমাণ 0 এর চাইতে বড় হয় কিন্তু পাত্রের সংখ্যা 0 হয় তাহলে Answer হবে “Impossible” । [পাত্র না থাকলে কিভাবে ডিম সেদ্ধ করবে ]  <br>
কেস ৩ঃ প্রব্লেম এ যেহেতু বলা আছে প্রত্যেকটা পাত্র অসীম সাইজের সেহেতু সবসময় Answer হবে Given Time . [ একটা পাত্রেই E ডিম দেয়া যাবে ] <br>

#### [C. যোগ নিয়ে গুটিবাজি](https://algo.codemarshal.org/contests/noboborsho-1423/problems/C)
Problem setter: [Khairul Basar Rofi](https://www.facebook.com/Omaanuushh) 

একটি স্ট্রেইট ফরওয়ার্ড অ্যাড-হক প্রবলেম। প্রথমে অ্যারে A এর কিছু এলিমেন্ট বের করে নিয়ে যোগ করলেই প্যাটার্ন পাওয়া যায়। একটা নির্দিষ্ট সংখ্যা x পর্যন্ত যোগফল বের করার জন্য সূত্র হল k=(x/4+1)*2, sum = k * k । এখন x%4==0 হলে sum-=4 আর x % 4 = = 1 হলে sum-=2 করতে হবে। তাহলেই ওই সংখ্যা পর্যন্ত যোগফল পাওয়া যাবে। এখন R এবং L-1 এর জন্য যোগফল বের করে প্রথম যোগফল থেকে দ্বিতীয় যোগফল বাদ দিলেই অ্যান্সার পাওয়া যাবে।


#### [D. ভিত্তিহীন মদন](https://algo.codemarshal.org/contests/noboborsho-1423/problems/D)
Problem setter: [Hasan Abdullah](https://www.facebook.com/hasan.cse91)

খুব straightforward প্রবলেম ছিল এটা। শুধু কয়েকটা কেসের কথা উল্লেখ করছি যা দেখলে কোন নাম্বার valid/invalid বুঝা যাবে। এগুলো মিললেই কোড AC হবার কথা। 

011 - binary, octal, decimal, hexadecimal <br>
.110 - binary, octal, decimal, hexadecimal  <br>
0.11 - binary, octal, decimal, hexadecimal  <br>
0.11.01 - habijabi  <br>
123W.ABC - habijabi  <br>
10125.  -  habijabi (for ending point)  <br>
AbC.dEf - hexadecimal <br>

Input হিসেবে alphanumeric দেয়া হবে বলা হলেও ভুলক্রমে ডাটাসেটের একটা কেসে ‘$’ sign দেয়া ছিল। এর কারণে অনেকের প্রবলেম AC হয় নি। অনাকাংক্ষিত এই ভুলের জন্য দুঃখিত। 


#### [E. ABS() নিয়ে লীলাখেলা](https://algo.codemarshal.org/contests/noboborsho-1423/problems/E)
প্রব্লেম সেটার এবং এডিটরিয়ালঃ [রাইহাত জামান নিলয়](https://www.facebook.com/Dj.NILOY) <br>
প্রব্লেমের ধরণঃ ডাটা স্ট্রাকচার

সমাধানঃ <br>
প্রব্লেমটিতে আমরা যদি একটু লক্ষ্য করি তাহলে দেখতে পাব, একটি নম্বর X এর সাথে অন্য সকল Y নম্বরের জন্যে abs(X-Y) এর যোগফলের মান দুটি বিষয় থেকে পাওয়া যাবেঃ <br>
১| যদি Y নম্বরটি X এর চেয়ে ছোট হয়, তাহলে যোগফলের সাথে যোগ হবে X-Y
২| আর Y নম্বরটি যদি X এর চেয়ে বড় হয়, তাহলে যোগফলের সাথে Y-X যোগ হবে। <br>
সে জন্যে আমাদের প্রধান কাজ হবে, ডাটা স্ট্রাকচার কে এমন ভাবে ব্যবহার করা যেন আমরা একটি নম্বর এর চেয়ে ছোট কতগুলি নম্বর আছে এবং তাদের যোগফল কত,আবার একই সাথে, 
একটি নম্বরের চেয়ে বড় কতগুলি নম্বর আছে এবং তাদের যোগফল কত সেটি বের করতে পারি। এর জন্যে আমরা সেগমেন্ট ট্রি অথবা বাইনারী ইন্ডেক্সট ট্রি ব্যবহার করতে পারি। <br>
এই সমস্যাটির আরও একটি চ্যালেঞ্জ হচ্ছে যে কোন পজিশনে একটি নতুন ভ্যালু বসানো। এই কাজটি সঠিক ভাবে করার জন্যে আমরা অফলাইন প্রসেসিং করে সেগমেন্ট ট্রি / বাইনারী ইন্ডেক্সট ট্রি
ব্যবহার করে একটি নম্বর প্রকৃতপক্ষে কোন পজিশনে বসবে সেটা বের করতে পারি। আর যদি কেউ অফলাইন প্রসেসিং এর জটিলতা এড়াতে চায়, তাহলে সবচেয়ে ভাল উপায় ব্যালেন্সড বাইনারী সার্চ 
ট্রি, যেমন - এভিএল ট্রি, ট্রিপ ট্রি, রেড-ব্ল্যাক ট্রি, স্প্লে ট্রি, যে কোন কিছু ব্যবহার করা যাবে।

#### [F. হা-ডু-ডু টুর্নামেন্ট](https://algo.codemarshal.org/contests/noboborsho-1423/problems/F)
প্রবলেম সেটার, সল্যুশন এবং এডিটরিয়াল: [মোঃ ইমরুল হাসান](https://www.facebook.com/mdimrul.hassan)<br>
এলগরিদম: ম্যাক্সিমাম ফ্লো <br> 

সল্যুশন:<br>
সল্যুশন বলার আগে একটা ছোট কথা বলে নেই। আমার সল্যুশনের জন্য প্রতিটি ম্যাচের পয়েন্ট একটু ভিন্নভাবে ধরেছি। জয়ের জন্য ১ পয়েন্ট, ড্র এর জন্য ০ পয়েন্ট, আর হারের জন্য -১ পয়েন্ট ধরে বাকি সল্যুশন টা করব। যেহেতু টুর্নামেন্টে সবাই একই সংখ্যক খেলা খেলবে (N-১), তাই সবার সম্মিলিত পয়েন্ট এতে করে (N-১) কমে যাবে। কিন্তু আপেক্ষিকভাবে সবার রাঙ্কিং এ কোন পরিবর্তন আসবে না, অথবা একে অন্যের সাথে পয়েন্টের ব্যাবধানও একই থাকবে।

প্রথমেই তোমার টিমের (টিম ০) যেসব খেলা বাকি আছে, সেগুলোতে ধরে নেই তোমার টিমই জিতবে। এতে টিম ০ এর চ্যাম্পিয়ন হওয়ার সম্ভাবনা বাড়বে বৈ কমবে না।

এরপর প্রত্যেক টিমের সম্মিলিত পয়েন্ট হিসেব করে ফেলি (i টিমের পয়েন্ট হবে score[i])। কিছু টিমের (সম্মিলিতভাবে তাদেরকে 'ক' টিমস বলব) পয়েন্ট থাকবে তোমার টিমের পয়েন্টের চেয়ে বেশি, আর কিছু টিমের (সম্মিলিতভাবে তাদেরকে 'খ' টিমস বলব) পয়েন্ট তোমার টিমের পয়েন্টের চেয়ে কম। আমাদের উদ্দেশ্য হবে এমনভাবে বাকি খেলাগুলোর ফলাফল নির্ধারণ করা যেন খ টিমসের সব টিমের পয়েন্ট তোমার টিমের পয়েন্টের চেয়ে বেশি না হয়, কিন্তু ক টিমেসের সব টিমের পয়েন্ট কমে তোমার টিমের সমান বা কম হয়।

এটা বের করার জন্য আমরা একটা ফ্লো গ্রাফ (G) ব্যাবহার করব যেখানে (N+১) টি নোড থাকবে। নোড ১ থেকে নোড (N-১) রিপ্রেসেন্ট করবে এক এক টি টিমকে। তোমার টিম, টিম ০, এর জন্য কোন নোডের প্রয়োজন নেই কারণ টিম ০ এর সব খেলার শেষ। যদি টিম i এবং j এর মধ্যে খেলা এখন না হয়ে থাকে, তাহলে G[i][j] = G[j][i] = ১ হবে - যার অর্থ i এবং j নোডের মধ্যে ক্যাপাসিটি ১। আর যদি খেলা ইতোমধ্যে হয়ে গিয়ে থাকে তাহলে G[i][j] = G[j][i] = ০।

নোড ০ এবং নোড N কে আমরা ফ্লো গ্রাফের সোর্স এবং ডেসটিনেশন হিসেবে রাখব। যেসব টিমের পয়েন্ট তোমার টিমের চেয়ে কম ('খ' টিমস) সোর্স থেকে তাদের প্রত্যেকটি টিমের মধ্যে এজ থাকবে আর তার ক্যাপাসিটি হবে G[0][i] = min(score[0] - score[i], 0)। একি ভাবে যেসব টিমের পয়েন্ট তোমার টিমের চেয়ে বেশি ('ক' টিমস) তাদের প্রত্যেকটি টিমের থেকে ডেসটিনেশন নোডের মধ্যে এজ থাকবে আর তার ক্যাপাসিটি হবে G[i][N] = min(score[i] - score[0], 0)। 

এর পর এই গ্রাফের উপর যেকোনো ম্যাক্স ফ্লো এলগরিদম চালালে আমরা পেয়ে যাব ম্যাক্সিমাম ফ্লো এবং প্রত্যেক নোডের মধ্যে ফ্লো (F[i][j] = নোড i এবং j এর মধ্যে ফ্লো)। এর পরেও যদি কোন নোড i এর জন্য F[i][N] < G[i][N] হয় তার মানে টিম i এর পয়েন্ট কোনভাবেই তোমার টিমের সমান করা গেল না। তাই তোমার টিমের প্রতিযোগিতায় চ্যাম্পিয়ন হওয়ার কোন সম্ভাবনা নেই। আর যদি তা না হয় তাহলে তোমার টিম চ্যাম্পিয়ন হতে পারবে। 

কমপ্লেক্সিটিঃ O(N^3)


#### [G. নীল গ্রহের ঘোড়া](https://algo.codemarshal.org/contests/noboborsho-1423/problems/G)
Problem setter: [S. M. Shakir Ahsan Romeo](https://www.facebook.com/romeo.cse) <br> 
Problem Name Credit: [Khairul Basar Rofi](https://www.facebook.com/Omaanuushh) <br>
Alternate Solution Writer: [Asif Mujtaba](https://www.facebook.com/profile.php?id=100006260718473) <br>
Alternate DP Solution Writer: [রাইহাত জামান নিলয়](https://www.facebook.com/Dj.NILOY) <br>

 
প্রবলেম টি তে একটা প্যালিন্ড্রোম সংখ্যা ইনপুট দেওয়া হবে, তোমাকে সেটা কতো তম প্যালিন্ড্রোম সংখ্যা বলতে হবে।
যেহেতু লিমিট বেশ বড় সেহেতু নেইভ এপ্রোচে করলে ১ সেকেন্ড টাইম লিমিটে বড় ইনপুটের একটা টেস্ট কেসও সলভ হবে না, সেহেতু তোমাকে একটু অন্য রকম করে ভাবতে হবে। খেয়াল করে দেখো ১ লেংথের প্যালিন্ড্রোম সংখ্যা আছে ৯  টা, ২ লেংথের প্যালিন্ড্রোমও আছে ৯ টা। ৩ লেংথ এর প্যালিন্ড্রোম আছে ৯০ টা, ৪ লেংথেও আছে ৯০ টা। অর্থাৎ f(n) যদি n-লেংথ বিশিষ্ট প্যালিন্ড্রোমিক সংখ্যার মোট সংখ্যা নির্দেশ করে তবেঃ-
f(n) = 9 * ( 10 ^ (n/2) ),  যদি n বিজোড় হয়।
f(n) = 9 * ( 10 ^ ((n – 1)/2) ),  যদি n জোড় হয়। [ Integer Division ]
যেহেতু সর্বোচ্চ ইনপুট ১০০০০০০০০১০০০০০০০০১ একটি ১৯-লেংথ এর প্যালিন্ড্রোম সংখ্যা, সেহেতু ১ থেকে ১৯ পর্যন্ত সব লেংথের মোট কতোটি প্যালিন্ড্রোম আছে খুব সহজেই উপরের সমীকরণ ব্যাবহার করে বের করা যাবে।
একটা array নাও, array টার i’তম ইনডেক্সে থাকবে 1 থেকে i-লেংথ পর্যন্ত মোট কতোটি প্যালিন্ড্রোম সংখ্যা আছে। উপরের সমীকরণ ব্যাবহার করে সেটা করতে পারবে।
এরপরে প্রতিটা ইনপুটের জন্যে সেটার লেংথ থেকে বের করো।  লেংথ আর উপরের array ব্যাবহার করে বের করো যে সেই লেংথ এর আগ পর্যন্ত কতোটা প্যালিন্ড্রোম  সংখ্যা আছে। যেমন লেংথ যদি ৫ হয় তবে ৫ – ১ = ৪ লেংথ পর্যন্ত কতোটি প্যালিন্ড্রোম আছে সেটা বের করতে পারবে, কারণ সেটা আছে array[4] এ। এবার তোমার কাজ কমে আসলো, কারণ এখন তোমাকে শুধু বের করতে হবে যে ইনপুট দেওয়া প্যালিন্ড্রোম সংখ্যাটা তার লেংথ এর যতো প্যালিন্ড্রোম আছে তাদের মধ্যে কতো তম।
যেমন, ৫ লেংথ এর প্রথম প্যালিন্ড্রোম সংখ্যা হলো ১০০০১, দ্বিতীয় হলো ১০১০১।
লক্ষ করো তুমি এখন ইনপুটের শেষ (লেংথ/২) টি ডিজিট বাদ দিতে পারছো, ওটা নিয়ে কাজ না করলেও চলবে। যদি ১০০০১ কে কেটে ফেলো তাহলে পাবে ১০০, ১০১০১ কে কাটলে পাবে ১০১। সুতরাং ৫ লেংথের
১০০ (১০০০১) হলো ১ম প্যালিন্ড্রোম
১০১ ( ১০১০১) হলো ২য় প্যালিন্ড্রোম
১০২ (১০২০১) ৩য় প্যালিন্ড্রোম
১০৯ (১০৯০১) ১০ম প্যালিন্ড্রোম
১১০ (১১০১১) ১১তম প্যালিন্ড্রোম
কি ? প্যাটার্ণ পেলে তো ? তোমার উপর একটু ছেড়ে দিই ;)
এমন একটি ফাংশন লিখো যেটাতে এই কাটা প্যালিন্ড্রোম ইনপুট দিলে সেটা ওই লেংথ এর কতো তম প্যালিন্ড্রোম সেটা বলে দিবে।
ফাইনাল এন্সার হবে এই ফাংশনের ভ্যালু + এই লেংথ এর আগের লেংথ পর্যন্ত মোট যতোটি প্যালিন্ড্রোম আছে তার ভ্যালু।

বোনাস চ্যালেঞ্জ ১:- Solve UVA-12050 ;) <br>
বোনাস চ্যালেঞ্জ ২:- ইনপুট প্যালিন্ড্রোমের সর্বোচ্চ লেংথ যদি ১০০০০০ হয় এবং আউটপুট কে ১০০০০০০০০৭ দিয়ে মোড করে দিতে বলা হয় <br>
সেক্ষেত্রে তোমার সল্যুশন কেমন হবে ? ;)


#### [H - কু ঝিক ঝিক](https://algo.codemarshal.org/contests/noboborsho-1423/problems/H)
Problem setter: [Sheikh Monir](https://www.facebook.com/SkMonirOFFICIAL) <br>
Alternate Writer: [Khairul Basar Rofi](https://www.facebook.com/Omaanuushh)  <br>

যেহেতু একটি ট্রেন দুটি শহরের মধ্যে চলাচল করে , সুতরাং n সংখ্যক শহর থেকে মোট যতভাবে দুটি শহর নির্বাচন করা যায় সেটিই হবে n সংখ্যক শহরে প্রয়োজনীয় মোট ট্রেনের সংখ্যা।<br>
অর্থাৎ nC2 এর মানই হবে উত্তর ।  nC2 কে simplify করলে n * (n – 1) / 2 পাওয়া যায় ।

nC2 = n! / { 2! * (n – 2)! }<br>
= { n * (n – 1) * (n - 2) * (n - 3) * . . . * (n – n + 1) } / { 2! * (n - 2) * (n - 3) *. . .* (n – n + 1) }<br>
= n * (n – 1) / 2<br>

#### [I. সর্ষের মধ্যে ভুত](https://algo.codemarshal.org/contests/noboborsho-1423/problems/I)
প্রব্লেম সেটারঃ [Ripon Kumar Roy](https://www.facebook.com/reponkumar.roy)<br> 
অল্টারনেট সল্যুশন  এবং এডিটরিয়ালঃ [রাইহাত জামান নিলয়](https://www.facebook.com/Dj.NILOY) <br> 

সল্যুশন ১: 
আমরা এখানে একটি মার্জ সর্ট ট্রি ব্যবহার  করতে পারি। ট্রি-টির প্রতিটি নোডে নম্বরগুলিকে সর্ট করে আমরা সংরক্ষণ করব। পরবর্তীতে যখন কোন কুয়েরি করা হবে, তখন আমরা সে সকল নোডগুলিতে যাব যারা আমাদের কুয়েরি-এর L থেকে R এর মধ্যের নম্বরগুলিকে সংরক্ষণ করা আছে। তারপর আমরা সেই নোডগুলিতে দেখব যে, K এর চেয়ে ছোট বা সমান কতগুলি নম্বর আছে এবং তাদের যোগফল কত। সেটার  জন্যে আমরা নোডগুলির নম্বরগুলির উপর বাইনারি সার্চ করতে পারি। L থেকে R এর মধ্যের বাকী নম্বরগুলি অবশ্যই K এর চেয়ে বড় হবে। এই অবস্থা থেকে পরবর্তীতে আমরা একটু গণিত ব্যবহার করে ফলাফল হিসাব করে ফেলতে পারি।  <br>
এই সল্যুশনের কমপ্লেক্সিটিঃ O(N*Log^2(N))

সল্যুশন ২:
অফলাইন প্রসেসিং এর মাধ্যমে প্রব্লেমটি সল্ভ করা সম্ভব। এর জন্যে আমাদের প্রয়োজনীয় ডাটা স্ট্রাকচার হচ্ছে একটি সেগমেন্ট ট্রি অথবা একটি বাইনারি ইন্ডেক্সট ট্রি। প্রথমে আমরা অ্যারে এবং সব কুয়েরিগুলিকে ইনপুট আকারে নিয়ে সেভ করে রাখব। তারপর কুয়েরিকে আমরা K এর মানের উপর ভিত্তি করে সর্ট করে ফেলব। এর পর এখন একটা কুয়েরিকে নিয়ে কাজ করব, তার জন্যে অ্যারেটিতে যে যে পজিশনের নম্বরগুলি বর্তমান কুয়েরি এর K এর সমান বা ছোট সে সব পজিশনে আমরা সেগমেন্ট ট্রি অথবা বাইনারি ইন্ডেক্সট ট্রি তে আপডেট করব। এরপর আমরা আমাদের কুয়েরি এর L থেকে R এর মধ্যে যোগফল এবং কতটি আছে, সেটা হিসাব করে আমরা আমাদের ফলাফল বের করে ফেলব।  <br>
এই সল্যুশনের কমপ্লিক্সিটিঃ O(N*Log(N))

সল্যুশন ৩:
অনলাইন পদ্ধতিতে এই প্রব্লেমটি সল্ভ করার আরও একটি পদ্ধতি হচ্ছে পারসিস্টেন্ট সেগমেন্ট ট্রি ব্যবহার করা। পারসিস্টেন্ট সেগমেন্ট ট্রি তে আমরা অ্যারে ইনপুট নেওয়ার সাথে সাথে আমরা আপডেট করে ফেলব। তার পর কুয়েরিতে ইনপুট নিয়ে পারসিস্টেন্ট সেগমেন্ট ট্রি এর R ট্রি থেকে L-1 ট্রি টি বাদ দিয়ে 1 থেকে K এর জন্যে ট্রি তে কুয়েরি করে আমরা ফলাফল হিসাব করে 
ফেলতে পারব। <br>
এই সল্যুশনটির কমপ্লিক্সিটিঃ  O(N*Log(N))

পারসিস্টেন্ট সেগমেন্ট ট্রি এর ভাল একটি টিউটোরিয়াল পাওয়া যাবে এখানেঃ http://blog.anudeep2011.com/persistent-segment-trees-explained-with-spoj-problems/


#### [J. দাদুর চকোলেট রঙ্গ](https://algo.codemarshal.org/contests/noboborsho-1423/problems/J)
Problem setter: [Asif Mujtaba](https://www.facebook.com/profile.php?id=100006260718473)<br>
Alternate Writer: [Khairul Basar Rofi](https://www.facebook.com/Omaanuushh)  <br>

ধরে নেই, a_(n) হল n তম স্তর এর চকোলেট এর সংখ্যা আর b_(n) হল প্রথম n

স্তরের মোট চকোলেট এর সংখ্যা ,

ছবি গুলোর একটু ভাল ভাবে পর্যবেক্ষণ করলে দেখা যাবে (n+1) তম স্তরে 6*n

সংখ্যক চকোলেট আছে, তাই a_(n+1) = a_(n) + 6*n. প্রাথমিক অবস্থায় a_(0) = 1।

অতএব

a_(n) = 1 + 6 [ 1 + 2 + ..... + (n-1) ]

= 1 + 6 [n*(n-1)/2]

= 3*n^2 - 3*n + 1।

আর b_(n) এর জন্য

b_(n) = a_1 + a_2 + ....... + a_n ।

= 3(1^2 + 2^2 + ... + n^2) - 3 (1+...+n) + (1+1+....+1)

= 3 * [n*(n+1)*(2n+1)/6] - 3 [n*(n+1)/2] + n

= n^3।
