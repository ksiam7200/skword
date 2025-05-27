<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="google-adsense-account" content="ca-pub-3822467696455800">
  <title>Bangla-English Search</title>
  <link rel="stylesheet" href="style.csss.css">
 <head>

</head> 
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 20px;
      background: #f9f9f9;
    }

    h2 {
      text-align: center;
      margin-bottom: 20px;
    }

    .search-container {
      max-width: 500px;
      margin: 0 auto;
      display: flex;
      gap: 10px;
    }

    input[type="text"] {
      flex: 1;
      padding: 10px;
      font-size: 16px;
      border: 2px solid #ccc;
      border-radius: 5px;
    }

    button {
      padding: 10px 15px;
      font-size: 16px;
      background-color: #28a745;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    button:hover {
      background-color: #218838;
    }

    .result {
      max-width: 500px;
      margin: 20px auto;
      background: white;
      border-radius: 5px;
      padding: 15px;
      box-shadow: 0 0 5px rgba(0,0,0,0.1);
    }

    .entry {
      margin-bottom: 15px;
      padding-bottom: 10px;
      border-bottom: 1px solid #ddd;
    }

    @media (max-width: 600px) {
      input[type="text"], button {
        font-size: 14px;
      }
    }
  </style>
</head>
<body>

  <h2>Search Your Word</h2>

  <div class="search-container">
    <input type="text" id="searchInput" placeholder="শব্দ বা শব্দের অর্থ লিখুন...">
    <button onclick="searchData()">Search</button>
  </div>

  <div class="result" id="resultBox">
    <!-- Search results will appear here -->
  </div>

  <!-- All entries -->
  <div id="dataList" style="display:none;">
<div class="entry">
  <pre>1. Apple (অ্যাপেল) - আপেল  
Synonym: fruit  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>2. Able (এবল) - সক্ষম  
Synonym: capable  
Antonym: incapable</pre>
</div>

<div class="entry">
  <pre>3. Accept (অ্যাকসেপ্ট) - গ্রহণ করা  
Synonym: receive  
Antonym: reject</pre>
</div>

<div class="entry">
  <pre>4. Angry (অ্যাংগ্রি) - রাগান্বিত  
Synonym: mad  
Antonym: calm</pre>
</div>

<div class="entry">
  <pre>5. Ancient (এনশিয়েন্ট) - প্রাচীন  
Synonym: old  
Antonym: modern</pre>
</div>

<div class="entry">
  <pre>6. Answer (আনসার) - উত্তর  
Synonym: reply  
Antonym: question</pre>
</div>

<div class="entry">
  <pre>7. Arrive (অ্যারাইভ) - পৌঁছানো  
Synonym: reach  
Antonym: depart</pre>
</div>

<div class="entry">
  <pre>8. Active (অ্যাকটিভ) - সক্রিয়  
Synonym: energetic  
Antonym: lazy</pre>
</div>

<div class="entry">
  <pre>9. Always (অলওয়েজ) - সর্বদা  
Synonym: constantly  
Antonym: never</pre>
</div>

<div class="entry">
  <pre>10. Agree (অ্যাগ্রি) - একমত হওয়া  
Synonym: consent  
Antonym: disagree</pre>
</div>
<div class="entry">
  <pre>11. Ability (অ্যাবিলিটি) - যোগ্যতা  
Synonym: skill  
Antonym: inability</pre>
</div>

<div class="entry">
  <pre>12. Abandon (আবান্ডন) - পরিত্যাগ করা  
Synonym: leave  
Antonym: keep</pre>
</div>

<div class="entry">
  <pre>13. Absent (অ্যাবসেন্ট) - অনুপস্থিত  
Synonym: missing  
Antonym: present</pre>
</div>

<div class="entry">
  <pre>14. Abundant (অ্যাবানডান্ট) - প্রচুর  
Synonym: plentiful  
Antonym: scarce</pre>
</div>

<div class="entry">
  <pre>15. Abuse (অ্যাবিউজ) - অপব্যবহার  
Synonym: misuse  
Antonym: respect</pre>
</div>

<div class="entry">
  <pre>16. Accurate (অ্যাকিউরেট) - সঠিক  
Synonym: correct  
Antonym: incorrect</pre>
</div>

<div class="entry">
  <pre>17. Achieve (অ্যাচিভ) - অর্জন করা  
Synonym: accomplish  
Antonym: fail</pre>
</div>

<div class="entry">
  <pre>18. Adapt (অ্যাডাপ্ট) - মানিয়ে নেওয়া  
Synonym: adjust  
Antonym: resist</pre>
</div>

<div class="entry">
  <pre>19. Add (অ্যাড) - যোগ করা  
Synonym: include  
Antonym: subtract</pre>
</div>

<div class="entry">
  <pre>20. Admire (অ্যাডমায়ার) - প্রশংসা করা  
Synonym: praise  
Antonym: criticize</pre>
</div>
<div class="entry">
  <pre>21. Admit (অ্যাডমিট) - স্বীকার করা  
Synonym: confess  
Antonym: deny</pre>
</div>

<div class="entry">
  <pre>22. Adopt (অ্যাডপ্ট) - দত্তক নেওয়া / গ্রহণ করা  
Synonym: embrace  
Antonym: reject</pre>
</div>

<div class="entry">
  <pre>23. Adult (অ্যাডাল্ট) - প্রাপ্তবয়স্ক  
Synonym: grown-up  
Antonym: child</pre>
</div>

<div class="entry">
  <pre>24. Advance (অ্যাডভান্স) - অগ্রগতি  
Synonym: progress  
Antonym: retreat</pre>
</div>

<div class="entry">
  <pre>25. Advice (অ্যাডভাইস) - উপদেশ  
Synonym: guidance  
Antonym: misguidance</pre>
</div>

<div class="entry">
  <pre>26. Afraid (আফ্রেইড) - ভীত  
Synonym: scared  
Antonym: brave</pre>
</div>

<div class="entry">
  <pre>27. After (আফটার) - পরে  
Synonym: following  
Antonym: before</pre>
</div>

<div class="entry">
  <pre>28. Again (অ্যাগেইন) - আবার  
Synonym: once more  
Antonym: never</pre>
</div>

<div class="entry">
  <pre>29. Against (অ্যাগেইনস্ট) - বিপক্ষে  
Synonym: opposed  
Antonym: for</pre>
</div>

<div class="entry">
  <pre>30. Age (এজ) - বয়স  
Synonym: lifetime  
Antonym: youth</pre>
</div>
<div class="entry">
  <pre>31. Agent (এজেন্ট) - প্রতিনিধি  
Synonym: representative  
Antonym: client</pre>
</div>

<div class="entry">
  <pre>32. Agreeable (অ্যাগ্রিয়াবল) - মনোরম / সম্মত  
Synonym: pleasant  
Antonym: disagreeable</pre>
</div>

<div class="entry">
  <pre>33. Agriculture (অ্যাগ্রিকালচার) - কৃষি  
Synonym: farming  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>34. Aim (এইম) - লক্ষ্য  
Synonym: goal  
Antonym: neglect</pre>
</div>

<div class="entry">
  <pre>35. Air (এয়ার) - বাতাস  
Synonym: breeze  
Antonym: vacuum</pre>
</div>

<div class="entry">
  <pre>36. Alarm (আলার্ম) - সতর্ক সংকেত  
Synonym: alert  
Antonym: calm</pre>
</div>

<div class="entry">
  <pre>37. Alert (অ্যালার্ট) - সতর্ক  
Synonym: watchful  
Antonym: careless</pre>
</div>

<div class="entry">
  <pre>38. Alive (অ্যালাইভ) - জীবিত  
Synonym: living  
Antonym: dead</pre>
</div>

<div class="entry">
  <pre>39. Allow (অ্যালাউ) - অনুমতি দেওয়া  
Synonym: permit  
Antonym: forbid</pre>
</div>

<div class="entry">
  <pre>40. Alone (অ্যালোন) - একা  
Synonym: solitary  
Antonym: together</pre>
</div>
<div class="entry">
  <pre>41. Along (অ্যালং) - বরাবর  
Synonym: beside  
Antonym: away</pre>
</div>

<div class="entry">
  <pre>42. Aloud (আলাউড) - উচ্চস্বরে  
Synonym: loudly  
Antonym: silently</pre>
</div>

<div class="entry">
  <pre>43. Alphabet (অ্যালফাবেট) - বর্ণমালা  
Synonym: letters  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>44. Already (অলরেডি) - ইতিমধ্যে  
Synonym: previously  
Antonym: not yet</pre>
</div>

<div class="entry">
  <pre>45. Also (অলসো) - এছাড়াও  
Synonym: too  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>46. Alter (অল্টার) - পরিবর্তন করা  
Synonym: change  
Antonym: preserve</pre>
</div>

<div class="entry">
  <pre>47. Although (অলদো) - যদিও  
Synonym: though  
Antonym: because</pre>
</div>

<div class="entry">
  <pre>48. Always (অলওয়েজ) - সর্বদা  
Synonym: forever  
Antonym: never</pre>
</div>

<div class="entry">
  <pre>49. Amazing (অ্যামেজিং) - বিস্ময়কর  
Synonym: astonishing  
Antonym: ordinary</pre>
</div>

<div class="entry">
  <pre>50. Ambition (অ্যাম্বিশন) - উচ্চাকাঙ্ক্ষা  
Synonym: aspiration  
Antonym: laziness</pre>
</div>
<div class="entry">
  <pre>51. Amount (অ্যামাউন্ট) - পরিমাণ  
Synonym: quantity  
Antonym: portion</pre>
</div>

<div class="entry">
  <pre>52. Amuse (অ্যামিউজ) - আনন্দ দেওয়া  
Synonym: entertain  
Antonym: bore</pre>
</div>

<div class="entry">
  <pre>53. Analyze (অ্যানালাইজ) - বিশ্লেষণ করা  
Synonym: examine  
Antonym: ignore</pre>
</div>

<div class="entry">
  <pre>54. Ancient (এনশিয়েন্ট) - প্রাচীন  
Synonym: antique  
Antonym: modern</pre>
</div>

<div class="entry">
  <pre>55. Anger (অ্যাঙ্গার) - রাগ  
Synonym: rage  
Antonym: peace</pre>
</div>

<div class="entry">
  <pre>56. Animal (অ্যানিম্যাল) - জন্তু  
Synonym: creature  
Antonym: human</pre>
</div>

<div class="entry">
  <pre>57. Announce (অ্যানাউন্স) - ঘোষণা করা  
Synonym: declare  
Antonym: hide</pre>
</div>

<div class="entry">
  <pre>58. Annoy (অ্যানয়) - বিরক্ত করা  
Synonym: irritate  
Antonym: please</pre>
</div>

<div class="entry">
  <pre>59. Annual (অ্যানুয়াল) - বার্ষিক  
Synonym: yearly  
Antonym: monthly</pre>
</div>

<div class="entry">
  <pre>60. Answer (আনসার) - উত্তর  
Synonym: response  
Antonym: question</pre>
</div>
<div class="entry">
  <pre>61. Ant (অ্যান্ট) - পিঁপড়ে  
Synonym: insect  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>62. Anticipate (অ্যান্টিসিপেট) - প্রত্যাশা করা  
Synonym: expect  
Antonym: doubt</pre>
</div>

<div class="entry">
  <pre>63. Anxious (অ্যাংকশাস) - উদ্বিগ্ন  
Synonym: worried  
Antonym: calm</pre>
</div>

<div class="entry">
  <pre>64. Apologize (অ্যাপলজাইজ) - ক্ষমা চাওয়া  
Synonym: beg pardon  
Antonym: blame</pre>
</div>

<div class="entry">
  <pre>65. Appeal (অ্যাপিল) - আবেদন  
Synonym: request  
Antonym: deny</pre>
</div>

<div class="entry">
  <pre>66. Appear (অ্যাপিয়ার) - প্রকাশ পাওয়া  
Synonym: emerge  
Antonym: disappear</pre>
</div>

<div class="entry">
  <pre>67. Appoint (অ্যাপয়েন্ট) - নিয়োগ দেওয়া  
Synonym: assign  
Antonym: dismiss</pre>
</div>

<div class="entry">
  <pre>68. Appreciate (অ্যাপ্রিসিয়েট) - কদর করা  
Synonym: value  
Antonym: criticize</pre>
</div>

<div class="entry">
  <pre>69. Approach (অ্যাপ্রোচ) - কাছে আসা / পদ্ধতি  
Synonym: method  
Antonym: retreat</pre>
</div>

<div class="entry">
  <pre>70. Approve (অ্যাপ্রুভ) - অনুমোদন করা  
Synonym: accept  
Antonym: reject</pre>
</div>
<div class="entry">
  <pre>71. Area (এরিয়া) - এলাকা  
Synonym: region  
Antonym: point</pre>
</div>

<div class="entry">
  <pre>72. Argue (আর্গিউ) - তর্ক করা  
Synonym: debate  
Antonym: agree</pre>
</div>

<div class="entry">
  <pre>73. Arise (অ্যারাইজ) - উদয় হওয়া / উঠা  
Synonym: emerge  
Antonym: settle</pre>
</div>

<div class="entry">
  <pre>74. Army (আর্মি) - সেনাবাহিনী  
Synonym: military  
Antonym: civilian</pre>
</div>

<div class="entry">
  <pre>75. Arrange (অ্যারেঞ্জ) - গুছিয়ে রাখা  
Synonym: organize  
Antonym: disorder</pre>
</div>

<div class="entry">
  <pre>76. Arrest (অ্যারেস্ট) - গ্রেপ্তার করা  
Synonym: capture  
Antonym: release</pre>
</div>

<div class="entry">
  <pre>77. Arrive (অ্যারাইভ) - পৌঁছানো  
Synonym: reach  
Antonym: leave</pre>
</div>

<div class="entry">
  <pre>78. Article (আর্টিকল) - প্রবন্ধ / নিবন্ধ  
Synonym: essay  
Antonym: silence</pre>
</div>

<div class="entry">
  <pre>79. Artist (আর্টিস্ট) - শিল্পী  
Synonym: painter  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>80. Ask (আস্ক) - জিজ্ঞেস করা  
Synonym: inquire  
Antonym: answer</pre>
</div>
<div class="entry">
  <pre>81. Aspect (অ্যাসপেক্ট) - দিক / দৃষ্টিভঙ্গি  
Synonym: perspective  
Antonym: whole</pre>
</div>

<div class="entry">
  <pre>82. Aspire (অ্যাসপায়ার) - আকাঙ্ক্ষা করা  
Synonym: desire  
Antonym: dislike</pre>
</div>

<div class="entry">
  <pre>83. Assault (অ্যাসল্ট) - আক্রমণ  
Synonym: attack  
Antonym: defense</pre>
</div>

<div class="entry">
  <pre>84. Assemble (অ্যাসেম্বল) - একত্রিত হওয়া  
Synonym: gather  
Antonym: disperse</pre>
</div>

<div class="entry">
  <pre>85. Assert (অ্যাসার্ট) - জোর দিয়ে বলা  
Synonym: declare  
Antonym: deny</pre>
</div>

<div class="entry">
  <pre>86. Assess (অ্যাসেস) - মূল্যায়ন করা  
Synonym: evaluate  
Antonym: guess</pre>
</div>

<div class="entry">
  <pre>87. Assign (অ্যাসাইন) - বরাদ্দ করা  
Synonym: allocate  
Antonym: withhold</pre>
</div>

<div class="entry">
  <pre>88. Assist (অ্যাসিস্ট) - সাহায্য করা  
Synonym: help  
Antonym: hinder</pre>
</div>

<div class="entry">
  <pre>89. Associate (অ্যাসোসিয়েট) - সম্পর্কযুক্ত করা  
Synonym: connect  
Antonym: separate</pre>
</div>

<div class="entry">
  <pre>90. Assume (অ্যাসিউম) - ধরে নেওয়া  
Synonym: suppose  
Antonym: doubt</pre>
</div>
<div class="entry">
  <pre>91. Assure (অ্যাশিউর) - আশ্বস্ত করা  
Synonym: guarantee  
Antonym: doubt</pre>
</div>

<div class="entry">
  <pre>92. Astonish (অ্যাস্টোনিশ) - বিস্মিত করা  
Synonym: amaze  
Antonym: bore</pre>
</div>

<div class="entry">
  <pre>93. Attach (অ্যাটাচ) - সংযুক্ত করা  
Synonym: join  
Antonym: detach</pre>
</div>

<div class="entry">
  <pre>94. Attack (অ্যাটাক) - আক্রমণ করা  
Synonym: assault  
Antonym: defend</pre>
</div>

<div class="entry">
  <pre>95. Attempt (অ্যাটেম্পট) - চেষ্টা  
Synonym: try  
Antonym: neglect</pre>
</div>

<div class="entry">
  <pre>96. Attend (অ্যাটেন্ড) - উপস্থিত হওয়া  
Synonym: be present  
Antonym: miss</pre>
</div>

<div class="entry">
  <pre>97. Attract (অ্যাট্র্যাক্ট) - আকর্ষণ করা  
Synonym: lure  
Antonym: repel</pre>
</div>

<div class="entry">
  <pre>98. Attribute (অ্যাট্রিবিউট) - গুণ / বৈশিষ্ট্য  
Synonym: quality  
Antonym: flaw</pre>
</div>

<div class="entry">
  <pre>99. Author (অথর) - লেখক  
Synonym: writer  
Antonym: reader</pre>
</div>

<div class="entry">
  <pre>100. Authority (অথরিটি) - কর্তৃত্ব  
Synonym: power  
Antonym: subordination</pre>
</div>
<div class="entry">
  <pre>101. Auto (অটো) - স্বয়ংক্রিয়  
Synonym: automatic  
Antonym: manual</pre>
</div>

<div class="entry">
  <pre>102. Available (অ্যাভেইলেবল) - উপলব্ধ  
Synonym: accessible  
Antonym: unavailable</pre>
</div>

<div class="entry">
  <pre>103. Average (অ্যাভারেজ) - গড়  
Synonym: mean  
Antonym: extreme</pre>
</div>

<div class="entry">
  <pre>104. Avoid (অ্যাভয়েড) - এড়িয়ে চলা  
Synonym: evade  
Antonym: confront</pre>
</div>

<div class="entry">
  <pre>105. Awake (অ্যাওয়েক) - জাগ্রত  
Synonym: alert  
Antonym: asleep</pre>
</div>

<div class="entry">
  <pre>106. Award (অ্যাওয়ার্ড) - পুরস্কার  
Synonym: prize  
Antonym: penalty</pre>
</div>

<div class="entry">
  <pre>107. Aware (অ্যাওয়ার) - সচেতন  
Synonym: conscious  
Antonym: unaware</pre>
</div>

<div class="entry">
  <pre>108. Away (অ্যাওয়ে) - দূরে  
Synonym: afar  
Antonym: near</pre>
</div>

<div class="entry">
  <pre>109. Awful (অউফুল) - ভয়ংকর  
Synonym: terrible  
Antonym: wonderful</pre>
</div>

<div class="entry">
  <pre>110. Awkward (অউকওয়ার্ড) - অস্বস্তিকর  
Synonym: clumsy  
Antonym: graceful</pre>
</div>
<div class="entry">
  <pre>111. Axis (অ্যাক্সিস) - অক্ষ  
Synonym: center line  
Antonym: edge</pre>
</div>

<div class="entry">
  <pre>112. Axiom (অ্যাক্সিওম) - স্বতঃসিদ্ধ সত্য  
Synonym: principle  
Antonym: absurdity</pre>
</div>

<div class="entry">
  <pre>113. Aye (আই) - হ্যাঁ  
Synonym: yes  
Antonym: no</pre>
</div>

<div class="entry">
  <pre>114. Azure (অ্যাজুর) - আকাশি নীল  
Synonym: sky-blue  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>115. Abiding (অ্যাবাইডিং) - স্থায়ী  
Synonym: lasting  
Antonym: temporary</pre>
</div>

<div class="entry">
  <pre>116. Abnormal (অ্যাবনর্মাল) - অস্বাভাবিক  
Synonym: irregular  
Antonym: normal</pre>
</div>

<div class="entry">
  <pre>117. Ablaze (অ্যাব্লেজ) - দাউদাউ করে জ্বলছে  
Synonym: burning  
Antonym: dark</pre>
</div>

<div class="entry">
  <pre>118. Abridge (অ্যাব্রিজ) - সংক্ষিপ্ত করা  
Synonym: shorten  
Antonym: expand</pre>
</div>

<div class="entry">
  <pre>119. Absent (অ্যাবসেন্ট) - অনুপস্থিত  
Synonym: missing  
Antonym: present</pre>
</div>

<div class="entry">
  <pre>120. Absorb (অ্যাবজর্ন) - শোষণ করা  
Synonym: soak  
Antonym: release</pre>
</div>
<div class="entry">
  <pre>121. Abstract (অ্যাবস্ট্রাক্ট) - বিমূর্ত  
Synonym: theoretical  
Antonym: concrete</pre>
</div>

<div class="entry">
  <pre>122. Absurd (অ্যাবসার্ড) - হাস্যকর / অযৌক্তিক  
Synonym: ridiculous  
Antonym: logical</pre>
</div>

<div class="entry">
  <pre>123. Abundance (অ্যাবানডেন্স) - প্রাচুর্য  
Synonym: plenty  
Antonym: scarcity</pre>
</div>

<div class="entry">
  <pre>124. Abuse (অ্যাবিউজ) - অপব্যবহার / গালিগালাজ  
Synonym: misuse  
Antonym: praise</pre>
</div>

<div class="entry">
  <pre>125. Academic (অ্যাকাডেমিক) - একাডেমিক / শিক্ষাগত  
Synonym: educational  
Antonym: nonacademic</pre>
</div>

<div class="entry">
  <pre>126. Accelerate (অ্যাক্সেলারেট) - গতি বাড়ানো  
Synonym: speed up  
Antonym: slow down</pre>
</div>

<div class="entry">
  <pre>127. Acceptable (অ্যাকসেপ্টেবল) - গ্রহণযোগ্য  
Synonym: suitable  
Antonym: unacceptable</pre>
</div>

<div class="entry">
  <pre>128. Access (অ্যাক্সেস) - প্রবেশাধিকার  
Synonym: entry  
Antonym: barrier</pre>
</div>

<div class="entry">
  <pre>129. Acclaim (অ্যাক্লেইম) - প্রশংসা  
Synonym: praise  
Antonym: criticism</pre>
</div>

<div class="entry">
  <pre>130. Accompany (অ্যাকম্পানি) - সঙ্গ দেওয়া  
Synonym: escort  
Antonym: abandon</pre>
</div>
<div class="entry">
  <pre>131. Accomplish (অ্যাকমপ্লিশ) - সম্পন্ন করা  
Synonym: achieve  
Antonym: fail</pre>
</div>

<div class="entry">
  <pre>132. Accord (অ্যাকর্ড) - সম্মতি  
Synonym: agreement  
Antonym: disagreement</pre>
</div>

<div class="entry">
  <pre>133. Account (অ্যাকাউন্ট) - হিসাব  
Synonym: record  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>134. Accurate (অ্যাকিউরেট) - সঠিক  
Synonym: precise  
Antonym: inaccurate</pre>
</div>

<div class="entry">
  <pre>135. Accuse (অ্যাকিউজ) - অভিযুক্ত করা  
Synonym: blame  
Antonym: defend</pre>
</div>

<div class="entry">
  <pre>136. Achieve (অ্যাচিভ) - অর্জন করা  
Synonym: accomplish  
Antonym: fail</pre>
</div>

<div class="entry">
  <pre>137. Acknowledge (অ্যাকনলেজ) - স্বীকার করা  
Synonym: admit  
Antonym: deny</pre>
</div>

<div class="entry">
  <pre>138. Acquire (অ্যাকোয়ার) - অর্জন করা  
Synonym: obtain  
Antonym: lose</pre>
</div>

<div class="entry">
  <pre>139. Act (অ্যাক্ট) - কাজ করা  
Synonym: do  
Antonym: refrain</pre>
</div>

<div class="entry">
  <pre>140. Active (অ্যাক্টিভ) - সক্রিয়  
Synonym: energetic  
Antonym: inactive</pre>
</div>
<div class="entry">
  <pre>141. Actual (অ্যাকচুয়াল) - প্রকৃত  
Synonym: real  
Antonym: imaginary</pre>
</div>

<div class="entry">
  <pre>142. Adapt (অ্যাডাপ্ট) - মানিয়ে নেওয়া  
Synonym: adjust  
Antonym: resist</pre>
</div>

<div class="entry">
  <pre>143. Add (অ্যাড) - যোগ করা  
Synonym: include  
Antonym: subtract</pre>
</div>

<div class="entry">
  <pre>144. Address (অ্যাড্রেস) - ঠিকানা / সমাধান করা  
Synonym: location / tackle  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>145. Adequate (অ্যাডিকুয়েট) - পর্যাপ্ত  
Synonym: sufficient  
Antonym: insufficient</pre>
</div>

<div class="entry">
  <pre>146. Adjust (অ্যাডজাস্ট) - মানিয়ে নেওয়া  
Synonym: modify  
Antonym: disturb</pre>
</div>

<div class="entry">
  <pre>147. Admire (অ্যাডমায়ার) - প্রশংসা করা  
Synonym: respect  
Antonym: despise</pre>
</div>

<div class="entry">
  <pre>148. Admit (অ্যাডমিট) - স্বীকার করা  
Synonym: confess  
Antonym: deny</pre>
</div>

<div class="entry">
  <pre>149. Adopt (অ্যাডপ্ট) - গৃহীত করা  
Synonym: accept  
Antonym: reject</pre>
</div>

<div class="entry">
  <pre>150. Advance (অ্যাডভান্স) - অগ্রসর হওয়া  
Synonym: progress  
Antonym: retreat</pre>
</div>
<div class="entry">
  <pre>151. Advantage (অ্যাডভান্টেজ) - সুবিধা  
Synonym: benefit  
Antonym: disadvantage</pre>
</div>

<div class="entry">
  <pre>152. Adventure (অ্যাডভেঞ্চার) - রোমাঞ্চ  
Synonym: excitement  
Antonym: safety</pre>
</div>

<div class="entry">
  <pre>153. Adverse (অ্যাডভার্স) - প্রতিকূল  
Synonym: unfavorable  
Antonym: favorable</pre>
</div>

<div class="entry">
  <pre>154. Advertise (অ্যাডভার্টাইজ) - বিজ্ঞাপন দেওয়া  
Synonym: promote  
Antonym: conceal</pre>
</div>

<div class="entry">
  <pre>155. Advice (অ্যাডভাইস) - পরামর্শ  
Synonym: suggestion  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>156. Advocate (অ্যাডভোকেট) - সমর্থন করা  
Synonym: support  
Antonym: oppose</pre>
</div>

<div class="entry">
  <pre>157. Affect (অ্যাফেক্ট) - প্রভাবিত করা  
Synonym: influence  
Antonym: ignore</pre>
</div>

<div class="entry">
  <pre>158. Affection (অ্যাফেকশন) - স্নেহ  
Synonym: love  
Antonym: hatred</pre>
</div>

<div class="entry">
  <pre>159. Affirm (অ্যাফার্ম) - নিশ্চিত করা  
Synonym: confirm  
Antonym: deny</pre>
</div>

<div class="entry">
  <pre>160. Afford (অ্যাফোর্ড) - সামর্থ্য থাকা  
Synonym: manage  
Antonym: lack</pre>
</div>
<div class="entry">
  <pre>161. Afraid (অ্যাফ্রেড) - ভীত  
Synonym: scared  
Antonym: brave</pre>
</div>

<div class="entry">
  <pre>162. After (আফটার) - পরে  
Synonym: following  
Antonym: before</pre>
</div>

<div class="entry">
  <pre>163. Afternoon (আফটারনুন) - অপরাহ্ন  
Synonym: midday  
Antonym: morning</pre>
</div>

<div class="entry">
  <pre>164. Again (অ্যাগেইন) - আবার  
Synonym: once more  
Antonym: never</pre>
</div>

<div class="entry">
  <pre>165. Against (অ্যাগেইনস্ট) - বিরুদ্ধে  
Synonym: opposed to  
Antonym: for</pre>
</div>

<div class="entry">
  <pre>166. Age (এজ) - বয়স  
Synonym: era  
Antonym: youth</pre>
</div>

<div class="entry">
  <pre>167. Agency (এজেন্সি) - সংস্থা  
Synonym: organization  
Antonym: individual</pre>
</div>

<div class="entry">
  <pre>168. Agenda (এজেন্ডা) - কার্যসূচি  
Synonym: schedule  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>169. Agent (এজেন্ট) - প্রতিনিধি  
Synonym: representative  
Antonym: principal</pre>
</div>

<div class="entry">
  <pre>170. Aggressive (অ্যাগ্রেসিভ) - আগ্রাসী  
Synonym: hostile  
Antonym: passive</pre>
</div>
<div class="entry">
  <pre>171. Agree (অ্যাগ্রি) - সম্মত হওয়া  
Synonym: consent  
Antonym: disagree</pre>
</div>

<div class="entry">
  <pre>172. Aid (এইড) - সাহায্য  
Synonym: assistance  
Antonym: hindrance</pre>
</div>

<div class="entry">
  <pre>173. Aim (এ임) - লক্ষ্য  
Synonym: goal  
Antonym: aimlessness</pre>
</div>

<div class="entry">
  <pre>174. Air (এয়ার) - বাতাস  
Synonym: atmosphere  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>175. Alarm (আলর্ম) - সতর্কতা  
Synonym: warning  
Antonym: calm</pre>
</div>

<div class="entry">
  <pre>176. Alert (অ্যালার্ট) - সতর্ক  
Synonym: vigilant  
Antonym: inattentive</pre>
</div>

<div class="entry">
  <pre>177. Alien (এলিয়েন) - বিদেশী / অপরিচিত  
Synonym: foreign  
Antonym: native</pre>
</div>

<div class="entry">
  <pre>178. Alike (অ্যালাইক) - সমান  
Synonym: similar  
Antonym: different</pre>
</div>

<div class="entry">
  <pre>179. Alive (আলাইভ) - জীবিত  
Synonym: living  
Antonym: dead</pre>
</div>

<div class="entry">
  <pre>180. All (অল) - সব  
Synonym: every  
Antonym: none</pre>
</div>
<div class="entry">
  <pre>181. Allegiance (অ্যালিজিয়েন্স) - আনুগত্য  
Synonym: loyalty  
Antonym: disloyalty</pre>
</div>

<div class="entry">
  <pre>182. Allow (অ্যালাউ) - অনুমতি দেওয়া  
Synonym: permit  
Antonym: forbid</pre>
</div>

<div class="entry">
  <pre>183. Almost (আলমোস্ট) - প্রায়  
Synonym: nearly  
Antonym: completely</pre>
</div>

<div class="entry">
  <pre>184. Alone (অ্যালোন) - একা  
Synonym: solitary  
Antonym: together</pre>
</div>

<div class="entry">
  <pre>185. Along (অ্যালং) - ধরে / সাথে  
Synonym: alongside  
Antonym: against</pre>
</div>

<div class="entry">
  <pre>186. Already (অ্যালরেডি) - ইতিমধ্যেই  
Synonym: previously  
Antonym: not yet</pre>
</div>

<div class="entry">
  <pre>187. Also (অ্যালসো) - এছাড়াও  
Synonym: too  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>188. Alter (অ্যালটার) - পরিবর্তন করা  
Synonym: change  
Antonym: preserve</pre>
</div>

<div class="entry">
  <pre>189. Alternative (অ্যালটারনেটিভ) - বিকল্প  
Synonym: option  
Antonym: necessity</pre>
</div>

<div class="entry">
  <pre>190. Although (অলথো) - যদিও  
Synonym: though  
Antonym: —</pre>
</div>
<div class="entry">
  <pre>191. Always (অলওয়েজ) - সর্বদা  
Synonym: forever  
Antonym: never</pre>
</div>

<div class="entry">
  <pre>192. Amateur (অ্যামেচার) - শখের কাজ করা  
Synonym: beginner  
Antonym: professional</pre>
</div>

<div class="entry">
  <pre>193. Amazing (অ্যামেজিং) - বিস্ময়কর  
Synonym: astonishing  
Antonym: ordinary</pre>
</div>

<div class="entry">
  <pre>194. Ambition (অ্যাম্বিশন) - উচ্চাকাঙ্ক্ষা  
Synonym: aspiration  
Antonym: indifference</pre>
</div>

<div class="entry">
  <pre>195. Ambiguous (অ্যাম্বিগুয়াস) - অস্পষ্ট  
Synonym: unclear  
Antonym: clear</pre>
</div>

<div class="entry">
  <pre>196. Amend (অ্যামেন্ড) - সংশোধন করা  
Synonym: modify  
Antonym: worsen</pre>
</div>

<div class="entry">
  <pre>197. Amount (অ্যামাউন্ট) - পরিমাণ  
Synonym: quantity  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>198. Amuse (অ্যামিউজ) - বিনোদন করা  
Synonym: entertain  
Antonym: bore</pre>
</div>

<div class="entry">
  <pre>199. Analyze (অ্যানালাইজ) - বিশ্লেষণ করা  
Synonym: examine  
Antonym: ignore</pre>
</div>

<div class="entry">
  <pre>200. Ancient (অ্যানসিয়েন্ট) - প্রাচীন  
Synonym: old  
Antonym: modern</pre>
</div>
<div class="entry">
  <pre>201. And (অ্যান্ড) - এবং  
Synonym: also  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>202. Anger (অ্যাংগার) - রাগ  
Synonym: rage  
Antonym: calm</pre>
</div>

<div class="entry">
  <pre>203. Angle (অ্যাঙ্গল) - কোণ  
Synonym: corner  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>204. Angry (অ্যাংরি) - রেগে যাওয়া  
Synonym: mad  
Antonym: happy</pre>
</div>

<div class="entry">
  <pre>205. Animal (অ্যানিমাল) - প্রাণী  
Synonym: creature  
Antonym: human</pre>
</div>

<div class="entry">
  <pre>206. Announce (অ্যানাউন্স) - ঘোষণা করা  
Synonym: declare  
Antonym: conceal</pre>
</div>

<div class="entry">
  <pre>207. Annual (অ্যানুয়াল) - বার্ষিক  
Synonym: yearly  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>208. Another (অ্যানাদার) - অন্য  
Synonym: different  
Antonym: same</pre>
</div>

<div class="entry">
  <pre>209. Answer (আনসার) - উত্তর  
Synonym: reply  
Antonym: question</pre>
</div>

<div class="entry">
  <pre>210. Anticipate (অ্যান্টিসিপেট) - প্রত্যাশা করা  
Synonym: expect  
Antonym: doubt</pre>
</div>
<div class="entry">
  <pre>211. Anxiety (অ্যাংজাইটি) - উদ্বেগ  
Synonym: worry  
Antonym: calmness</pre>
</div>

<div class="entry">
  <pre>212. Any (এনি) - যেকোনো  
Synonym: whichever  
Antonym: none</pre>
</div>

<div class="entry">
  <pre>213. Anybody (এনিবডি) - কেউ  
Synonym: anyone  
Antonym: nobody</pre>
</div>

<div class="entry">
  <pre>214. Anymore (এনিমোর) - আর  
Synonym: no longer  
Antonym: still</pre>
</div>

<div class="entry">
  <pre>215. Anyone (এনিওন) - কেউ  
Synonym: anybody  
Antonym: nobody</pre>
</div>

<div class="entry">
  <pre>216. Anything (এনিথিং) - কিছুই  
Synonym: something  
Antonym: nothing</pre>
</div>

<div class="entry">
  <pre>217. Anywhere (এনিহোয়্যার) - যেকোনো জায়গায়  
Synonym: everywhere  
Antonym: nowhere</pre>
</div>

<div class="entry">
  <pre>218. Apart (অ্যাপার্ট) - আলাদা  
Synonym: separate  
Antonym: together</pre>
</div>

<div class="entry">
  <pre>219. Apartment (অ্যাপার্টমেন্ট) - অ্যাপার্টমেন্ট  
Synonym: flat  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>220. Apologize (অ্যাপোলজাইজ) - ক্ষমা চাওয়া  
Synonym: excuse  
Antonym: blame</pre>
</div>
<div class="entry">
  <pre>221. Appeal (অ্যাপিল) - আবেদন  
Synonym: request  
Antonym: refusal</pre>
</div>

<div class="entry">
  <pre>222. Appear (অ্যাপিয়ার) - দেখা দেওয়া  
Synonym: seem  
Antonym: disappear</pre>
</div>

<div class="entry">
  <pre>223. Appearance (অ্যাপিয়ারেন্স) - চেহারা  
Synonym: look  
Antonym: disappearance</pre>
</div>

<div class="entry">
  <pre>224. Appetite (অ্যাপেটাইট) - ক্ষুধা  
Synonym: hunger  
Antonym: fullness</pre>
</div>

<div class="entry">
  <pre>225. Applaud (অ্যাপলড) - প্রশংসা করা  
Synonym: praise  
Antonym: criticize</pre>
</div>

<div class="entry">
  <pre>226. Apply (অ্যাপ্লাই) - আবেদন করা  
Synonym: request  
Antonym: ignore</pre>
</div>

<div class="entry">
  <pre>227. Appointment (অ্যাপয়েন্টমেন্ট) - নিয়োগ  
Synonym: meeting  
Antonym: cancellation</pre>
</div>

<div class="entry">
  <pre>228. Appreciate (অ্যাপ্রিসিয়েট) - প্রশংসা করা  
Synonym: value  
Antonym: disregard</pre>
</div>

<div class="entry">
  <pre>229. Approach (অ্যাপ্রোচ) - পদ্ধতি  
Synonym: method  
Antonym: avoidance</pre>
</div>

<div class="entry">
  <pre>230. Approve (অ্যাপ্রুভ) - অনুমোদন করা  
Synonym: accept  
Antonym: reject</pre>
</div>
<div class="entry">
  <pre>231. April (এপ্রিল) - এপ্রিল  
Synonym: —  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>232. Area (এরিয়া) - এলাকা  
Synonym: region  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>233. Argue (আর্গু) - তর্ক করা  
Synonym: debate  
Antonym: agree</pre>
</div>

<div class="entry">
  <pre>234. Argument (আর্গুমেন্ট) - বিতর্ক  
Synonym: dispute  
Antonym: agreement</pre>
</div>

<div class="entry">
  <pre>235. Arise (আরাইজ) - উদয় হওয়া  
Synonym: emerge  
Antonym: disappear</pre>
</div>

<div class="entry">
  <pre>236. Arm (আর্ম) - বাহু  
Synonym: limb  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>237. Armed (আর্মড) - সশস্ত্র  
Synonym: equipped  
Antonym: unarmed</pre>
</div>

<div class="entry">
  <pre>238. Army (আর্মি) - সেনাবাহিনী  
Synonym: troops  
Antonym: civilians</pre>
</div>

<div class="entry">
  <pre>239. Around (আরাউন্ড) - চারপাশে  
Synonym: about  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>240. Arrange (অ্যারেঞ্জ) - সাজানো  
Synonym: organize  
Antonym: disorder</pre>
</div>
<div class="entry">
  <pre>241. Arrest (অ্যারেস্ট) - গ্রেফতার করা  
Synonym: capture  
Antonym: release</pre>
</div>

<div class="entry">
  <pre>242. Arrival (অ্যারাইভাল) - আগমন  
Synonym: coming  
Antonym: departure</pre>
</div>

<div class="entry">
  <pre>243. Arrive (অ্যারাইভ) - পৌঁছানো  
Synonym: reach  
Antonym: leave</pre>
</div>

<div class="entry">
  <pre>244. Art (আর্ট) - শিল্প  
Synonym: craft  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>245. Article (আর্টিকেল) - প্রবন্ধ  
Synonym: essay  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>246. Artist (আর্টিস্ট) - শিল্পী  
Synonym: creator  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>247. Artistic (আর্টিস্টিক) - শিল্পময়  
Synonym: creative  
Antonym: uncreative</pre>
</div>

<div class="entry">
  <pre>248. As (অ্যাজ) - হিসাবে  
Synonym: like  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>249. Ash (অ্যাশ) - ছাই  
Synonym: residue  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>250. Aside (অ্যাসাইড) - পাশে  
Synonym: aside  
Antonym: —</pre>
</div>
<div class="entry">
  <pre>251. Ask (আস্ক) - জিজ্ঞাসা করা  
Synonym: inquire  
Antonym: answer</pre>
</div>

<div class="entry">
  <pre>252. Aspect (অ্যাসপেক্ট) - দিক  
Synonym: facet  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>253. Assault (অ্যাসল্ট) - আক্রমণ  
Synonym: attack  
Antonym: defense</pre>
</div>

<div class="entry">
  <pre>254. Assemble (অ্যাসেম্বল) - একত্রিত হওয়া  
Synonym: gather  
Antonym: disperse</pre>
</div>

<div class="entry">
  <pre>255. Assert (অ্যাসার্ট) - জোর দিয়ে বলা  
Synonym: declare  
Antonym: deny</pre>
</div>

<div class="entry">
  <pre>256. Assess (অ্যাসেস) - মূল্যায়ন করা  
Synonym: evaluate  
Antonym: ignore</pre>
</div>

<div class="entry">
  <pre>257. Assign (অ্যাসাইন) - নিযুক্ত করা  
Synonym: allocate  
Antonym: withhold</pre>
</div>

<div class="entry">
  <pre>258. Assist (অ্যাসিস্ট) - সাহায্য করা  
Synonym: help  
Antonym: hinder</pre>
</div>

<div class="entry">
  <pre>259. Associate (অ্যাসোসিয়েট) - সংযুক্ত করা  
Synonym: connect  
Antonym: separate</pre>
</div>

<div class="entry">
  <pre>260. Assume (অ্যাসিউম) - ধরে নেওয়া  
Synonym: suppose  
Antonym: doubt</pre>
</div>
<div class="entry">
  <pre>261. Astonish (অ্যাস্টনিশ) - অবাক করা  
Synonym: amaze  
Antonym: bore</pre>
</div>

<div class="entry">
  <pre>262. Attach (অ্যাটাচ) - সংযুক্ত করা  
Synonym: fasten  
Antonym: detach</pre>
</div>

<div class="entry">
  <pre>263. Attack (অ্যাটাক) - আক্রমণ  
Synonym: assault  
Antonym: defend</pre>
</div>

<div class="entry">
  <pre>264. Attempt (অ্যাটেম্পট) - চেষ্টা  
Synonym: try  
Antonym: give up</pre>
</div>

<div class="entry">
  <pre>265. Attend (অ্যাটেন্ড) - উপস্থিত থাকা  
Synonym: be present  
Antonym: absent</pre>
</div>

<div class="entry">
  <pre>266. Attention (অ্যাটেনশন) - মনোযোগ  
Synonym: focus  
Antonym: distraction</pre>
</div>

<div class="entry">
  <pre>267. Attitude (অ্যাটিচুড) - মনোভাব  
Synonym: mindset  
Antonym: indifference</pre>
</div>

<div class="entry">
  <pre>268. Attorney (অ্যাটর্নি) - আইনজীবী  
Synonym: lawyer  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>269. Attractive (অ্যাট্রাক্টিভ) - আকর্ষণীয়  
Synonym: appealing  
Antonym: unattractive</pre>
</div>

<div class="entry">
  <pre>270. Audience (অডিয়েন্স) - দর্শক  
Synonym: spectators  
Antonym: —</pre>
</div>
<div class="entry">
  <pre>271. Author (অথর) - লেখক  
Synonym: writer  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>272. Authority (অথরিটি) - কর্তৃপক্ষ  
Synonym: power  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>273. Automatic (অটোমেটিক) - স্বয়ংক্রিয়  
Synonym: mechanical  
Antonym: manual</pre>
</div>

<div class="entry">
  <pre>274. Available (অ্যাভেইলেবল) - উপলব্ধ  
Synonym: accessible  
Antonym: unavailable</pre>
</div>

<div class="entry">
  <pre>275. Average (অ্যাভারেজ) - গড়  
Synonym: mean  
Antonym: exceptional</pre>
</div>

<div class="entry">
  <pre>276. Avoid (অ্যাভয়েড) - এড়ানো  
Synonym: evade  
Antonym: confront</pre>
</div>

<div class="entry">
  <pre>277. Awake (অ্যাওয়েক) - জাগ্রত  
Synonym: alert  
Antonym: asleep</pre>
</div>

<div class="entry">
  <pre>278. Award (অ্যাওয়ার্ড) - পুরস্কার  
Synonym: prize  
Antonym: penalty</pre>
</div>

<div class="entry">
  <pre>279. Aware (অ্যাওয়ার) - সচেতন  
Synonym: conscious  
Antonym: unaware</pre>
</div>

<div class="entry">
  <pre>280. Away (অ্যাওয়ে) - দূরে  
Synonym: absent  
Antonym: present</pre>
</div>
<div class="entry">
  <pre>281. Awful (অ্যাওফুল) - ভয়ঙ্কর  
Synonym: terrible  
Antonym: wonderful</pre>
</div>

<div class="entry">
  <pre>282. Awkward (অ্যাওয়ার্ড) - বিব্রতকর  
Synonym: clumsy  
Antonym: graceful</pre>
</div>

<div class="entry">
  <pre>283. Axiom (অ্যাক্সিওম) - মৌলিক সত্য  
Synonym: principle  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>284. Azure (আজুর) - আকাশী রঙ  
Synonym: sky blue  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>285. Abandon (অ্যাব্যান্ডন) - পরিত্যাগ করা  
Synonym: forsake  
Antonym: keep</pre>
</div>

<div class="entry">
  <pre>286. Ability (এবিলিটি) - ক্ষমতা  
Synonym: capability  
Antonym: inability</pre>
</div>

<div class="entry">
  <pre>287. Able (এবল) - সক্ষম  
Synonym: competent  
Antonym: incapable</pre>
</div>

<div class="entry">
  <pre>288. Abnormal (অ্যাবনরমাল) - অস্বাভাবিক  
Synonym: unusual  
Antonym: normal</pre>
</div>

<div class="entry">
  <pre>289. Abode (অ্যাবোড) - আবাস  
Synonym: home  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>290. Abolish (অ্যাবলিশ) - বিলুপ্ত করা  
Synonym: eliminate  
Antonym: establish</pre>
</div>
<div class="entry">
  <pre>291. Abominable (অ্যাবমিনেবল) - ঘৃণ্য  
Synonym: hateful  
Antonym: delightful</pre>
</div>

<div class="entry">
  <pre>292. Aboriginal (অ্যাবরিজিনাল) - আদিম  
Synonym: native  
Antonym: foreign</pre>
</div>

<div class="entry">
  <pre>293. Abound (অ্যাবাউন্ড) - প্রাচুর্যপূর্ণ  
Synonym: flourish  
Antonym: lack</pre>
</div>

<div class="entry">
  <pre>294. Abrupt (অ্যাবরাপ্ট) - হঠাৎ  
Synonym: sudden  
Antonym: gradual</pre>
</div>

<div class="entry">
  <pre>295. Abscond (অ্যাবস্কন্ড) - গোপনে পালানো  
Synonym: flee  
Antonym: stay</pre>
</div>

<div class="entry">
  <pre>296. Absence (অ্যাবসেন্স) - অনুপস্থিতি  
Synonym: nonattendance  
Antonym: presence</pre>
</div>

<div class="entry">
  <pre>297. Absent (অ্যাবসেন্ট) - অনুপস্থিত  
Synonym: away  
Antonym: present</pre>
</div>

<div class="entry">
  <pre>298. Absolute (অ্যাবসলিউট) - সম্পূর্ণ  
Synonym: complete  
Antonym: partial</pre>
</div>

<div class="entry">
  <pre>299. Absorb (অ্যাবসর্ব) - শোষণ করা  
Synonym: soak up  
Antonym: repel</pre>
</div>

<div class="entry">
  <pre>300. Abstain (অ্যাবস্টেইন) - বিরত থাকা  
Synonym: refrain  
Antonym: indulge</pre>
</div>
<div class="entry">
  <pre>301. Abstract (অ্যাবস্ট্রাক্ট) - বিমূর্ত  
Synonym: theoretical  
Antonym: concrete</pre>
</div>

<div class="entry">
  <pre>302. Abundant (অ্যাবান্ডেন্ট) - প্রচুর  
Synonym: plentiful  
Antonym: scarce</pre>
</div>

<div class="entry">
  <pre>303. Abuse (অ্যাবিউজ) - অপব্যবহার  
Synonym: mistreatment  
Antonym: care</pre>
</div>

<div class="entry">
  <pre>304. Academic (অ্যাকাডেমিক) - শিক্ষাগত  
Synonym: scholarly  
Antonym: uneducated</pre>
</div>

<div class="entry">
  <pre>305. Accelerate (অ্যাক্সেলরেট) - দ্রুত করা  
Synonym: speed up  
Antonym: slow down</pre>
</div>

<div class="entry">
  <pre>306. Accept (অ্যাকসেপ্ট) - গ্রহণ করা  
Synonym: receive  
Antonym: reject</pre>
</div>

<div class="entry">
  <pre>307. Access (অ্যাক্সেস) - প্রবেশাধিকার  
Synonym: entry  
Antonym: denial</pre>
</div>

<div class="entry">
  <pre>308. Accident (অ্যাকসিডেন্ট) - দুর্ঘটনা  
Synonym: mishap  
Antonym: intention</pre>
</div>

<div class="entry">
  <pre>309. Accompany (অ্যাকোম্পানি) - সঙ্গ দেওয়া  
Synonym: escort  
Antonym: abandon</pre>
</div>

<div class="entry">
  <pre>310. Accomplish (অ্যাকমপ্লিশ) - সম্পন্ন করা  
Synonym: achieve  
Antonym: fail</pre>
</div>
<div class="entry">
  <pre>311. Accord (অ্যাকর্ড) - সামঞ্জস্য  
Synonym: agreement  
Antonym: conflict</pre>
</div>

<div class="entry">
  <pre>312. Account (অ্যাকাউন্ট) - হিসাব  
Synonym: record  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>313. Accurate (অ্যাকুরেট) - সঠিক  
Synonym: precise  
Antonym: inaccurate</pre>
</div>

<div class="entry">
  <pre>314. Accuse (অ্যাকিউজ) - অভিযোগ করা  
Synonym: blame  
Antonym: defend</pre>
</div>

<div class="entry">
  <pre>315. Achieve (অ্যাচিভ) - অর্জন করা  
Synonym: accomplish  
Antonym: fail</pre>
</div>

<div class="entry">
  <pre>316. Acknowledge (অ্যাকনলেজ) - স্বীকার করা  
Synonym: admit  
Antonym: deny</pre>
</div>

<div class="entry">
  <pre>317. Acquire (অ্যাকুয়ার) - অর্জন করা  
Synonym: obtain  
Antonym: lose</pre>
</div>

<div class="entry">
  <pre>318. Act (অ্যাক্ট) - কাজ করা  
Synonym: do  
Antonym: neglect</pre>
</div>

<div class="entry">
  <pre>319. Active (অ্যাকটিভ) - সক্রিয়  
Synonym: energetic  
Antonym: inactive</pre>
</div>

<div class="entry">
  <pre>320. Actual (অ্যাকচুয়াল) - প্রকৃত  
Synonym: real  
Antonym: fake</pre>
</div>
<div class="entry">
  <pre>321. Adapt (অ্যাডাপ্ট) - মানিয়ে নেওয়া  
Synonym: adjust  
Antonym: resist</pre>
</div>

<div class="entry">
  <pre>322. Add (অ্যাড) - যোগ করা  
Synonym: include  
Antonym: subtract</pre>
</div>

<div class="entry">
  <pre>323. Addict (অ্যাডিক্ট) - আসক্ত  
Synonym: dependent  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>324. Address (অ্যাড্রেস) - ঠিকানা  
Synonym: location  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>325. Adequate (অ্যাডিকুয়েট) - যথেষ্ট  
Synonym: sufficient  
Antonym: inadequate</pre>
</div>

<div class="entry">
  <pre>326. Adjust (অ্যাডজাস্ট) - মানিয়ে নেওয়া  
Synonym: adapt  
Antonym: disturb</pre>
</div>

<div class="entry">
  <pre>327. Administer (অ্যাডমিনিস্টার) - পরিচালনা করা  
Synonym: manage  
Antonym: neglect</pre>
</div>

<div class="entry">
  <pre>328. Admire (অ্যাডমায়ার) - প্রশংসা করা  
Synonym: appreciate  
Antonym: despise</pre>
</div>

<div class="entry">
  <pre>329. Admit (অ্যাডমিট) - স্বীকার করা  
Synonym: confess  
Antonym: deny</pre>
</div>

<div class="entry">
  <pre>330. Adopt (অ্যাডপ্ট) - গৃহীত করা  
Synonym: accept  
Antonym: reject</pre>
</div>
<div class="entry">
  <pre>331. Adore (অ্যাডোর) - খুব ভালোবাসা  
Synonym: love  
Antonym: hate</pre>
</div>

<div class="entry">
  <pre>332. Advance (অ্যাডভান্স) - অগ্রসর হওয়া  
Synonym: progress  
Antonym: retreat</pre>
</div>

<div class="entry">
  <pre>333. Advantage (অ্যাডভান্টেজ) - সুবিধা  
Synonym: benefit  
Antonym: disadvantage</pre>
</div>

<div class="entry">
  <pre>334. Adventure (অ্যাডভেঞ্চার) - অভিযান  
Synonym: expedition  
Antonym: safety</pre>
</div>

<div class="entry">
  <pre>335. Adverse (অ্যাডভার্স) - প্রতিকূল  
Synonym: unfavorable  
Antonym: favorable</pre>
</div>

<div class="entry">
  <pre>336. Advertise (অ্যাডভারটাইস) - বিজ্ঞাপন দেয়া  
Synonym: promote  
Antonym: conceal</pre>
</div>

<div class="entry">
  <pre>337. Advice (অ্যাডভাইস) - পরামর্শ  
Synonym: recommendation  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>338. Advocate (অ্যাডভোকেট) - সমর্থন করা  
Synonym: support  
Antonym: oppose</pre>
</div>

<div class="entry">
  <pre>339. Aerial (এয়ারিয়াল) - আকাশীয়  
Synonym: airborne  
Antonym: terrestrial</pre>
</div>

<div class="entry">
  <pre>340. Affect (অ্যাফেক্ট) - প্রভাবিত করা  
Synonym: influence  
Antonym: neglect</pre>
</div>
<div class="entry">
  <pre>341. Affection (অ্যাফেকশন) - স্নেহ  
Synonym: love  
Antonym: dislike</pre>
</div>

<div class="entry">
  <pre>342. Affirm (অ্যাফার্ম) - নিশ্চিত করা  
Synonym: confirm  
Antonym: deny</pre>
</div>

<div class="entry">
  <pre>343. Afflict (অ্যাফ্লিক্ট) - কষ্ট দেওয়া  
Synonym: trouble  
Antonym: comfort</pre>
</div>

<div class="entry">
  <pre>344. Afford (অ্যাফর্ড) - সামর্থ্য থাকা  
Synonym: manage  
Antonym: lack</pre>
</div>

<div class="entry">
  <pre>345. Afraid (অ্যাফ্রেইড) - ভয় পেয়েছে  
Synonym: scared  
Antonym: brave</pre>
</div>

<div class="entry">
  <pre>346. After (আফটার) - পরে  
Synonym: later  
Antonym: before</pre>
</div>

<div class="entry">
  <pre>347. Afternoon (আফটারনুন) - অপরাহ্ন  
Synonym: midday  
Antonym: morning</pre>
</div>

<div class="entry">
  <pre>348. Again (অ্যাগেইন) - আবার  
Synonym: once more  
Antonym: never</pre>
</div>

<div class="entry">
  <pre>349. Against (অ্যাগেইনস্ট) - বিরুদ্ধে  
Synonym: opposed to  
Antonym: for</pre>
</div>

<div class="entry">
  <pre>350. Age (এজ) - বয়স  
Synonym: era  
Antonym: youth</pre>
</div>
<div class="entry">
  <pre>351. Agency (এজেন্সি) - সংস্থা  
Synonym: organization  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>352. Agenda (এজেন্ডা) - কর্মসূচি  
Synonym: schedule  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>353. Agent (এজেন্ট) - প্রতিনিধি  
Synonym: representative  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>354. Aggressive (অ্যাগ্রেসিভ) - আগ্রাসী  
Synonym: hostile  
Antonym: peaceful</pre>
</div>

<div class="entry">
  <pre>355. Agree (অ্যাগ্রী) - সম্মত হওয়া  
Synonym: consent  
Antonym: disagree</pre>
</div>

<div class="entry">
  <pre>356. Agriculture (অ্যাগ্রিকালচার) - কৃষি  
Synonym: farming  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>357. Aid (এইড) - সাহায্য  
Synonym: help  
Antonym: hinder</pre>
</div>

<div class="entry">
  <pre>358. Aim (এইম) - লক্ষ্য  
Synonym: goal  
Antonym: miss</pre>
</div>

<div class="entry">
  <pre>359. Air (এয়ার) - বায়ু  
Synonym: atmosphere  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>360. Alarm (অ্যালার্ম) - সতর্কতা  
Synonym: alert  
Antonym: calm</pre>
</div>
<div class="entry">
  <pre>361. Alert (অ্যালার্ট) - সতর্ক  
Synonym: attentive  
Antonym: inattentive</pre>
</div>

<div class="entry">
  <pre>362. Alien (এলিয়েন) - বিদেশী  
Synonym: foreigner  
Antonym: native</pre>
</div>

<div class="entry">
  <pre>363. Align (অ্যালাইন) - সারিবদ্ধ করা  
Synonym: arrange  
Antonym: misalign</pre>
</div>

<div class="entry">
  <pre>364. Alike (আলাইক) - একইরকম  
Synonym: similar  
Antonym: different</pre>
</div>

<div class="entry">
  <pre>365. Alive (আলাইভ) - জীবিত  
Synonym: living  
Antonym: dead</pre>
</div>

<div class="entry">
  <pre>366. All (অল) - সব  
Synonym: every  
Antonym: none</pre>
</div>

<div class="entry">
  <pre>367. Allegation (অ্যালিজেশন) - অভিযোগ  
Synonym: accusation  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>368. Allow (অ্যালাউ) - অনুমতি দেওয়া  
Synonym: permit  
Antonym: forbid</pre>
</div>

<div class="entry">
  <pre>369. Ally (অ্যালাই) - মিত্র  
Synonym: partner  
Antonym: enemy</pre>
</div>

<div class="entry">
  <pre>370. Almost (আলমোস্ট) - প্রায়  
Synonym: nearly  
Antonym: completely</pre>
</div>
<div class="entry">
  <pre>371. Alone (আলোন) - একা  
Synonym: solitary  
Antonym: accompanied</pre>
</div>

<div class="entry">
  <pre>372. Along (আলং) - বরাবর  
Synonym: beside  
Antonym: against</pre>
</div>

<div class="entry">
  <pre>373. Already (অ্যালরেডি) - ইতোমধ্যে  
Synonym: previously  
Antonym: later</pre>
</div>

<div class="entry">
  <pre>374. Also (অ্যালসো) - ও  
Synonym: too  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>375. Alter (অ্যাল্টার) - পরিবর্তন করা  
Synonym: change  
Antonym: preserve</pre>
</div>

<div class="entry">
  <pre>376. Alternative (অ্যালটারনেটিভ) - বিকল্প  
Synonym: substitute  
Antonym: original</pre>
</div>

<div class="entry">
  <pre>377. Although (অলথো) - যদিও  
Synonym: though  
Antonym: because</pre>
</div>

<div class="entry">
  <pre>378. Always (অলওয়েজ) - সর্বদা  
Synonym: forever  
Antonym: never</pre>
</div>

<div class="entry">
  <pre>379. Amateur (অ্যামেচার) - অমateurs  
Synonym: novice  
Antonym: professional</pre>
</div>

<div class="entry">
  <pre>380. Amazing (অ্যামেজিং) - অবিশ্বাস্য  
Synonym: astonishing  
Antonym: ordinary</pre>
</div>
<div class="entry">
  <pre>381. Ambition (অ্যাম্বিশন) - উচ্চাকাঙ্ক্ষা  
Synonym: aspiration  
Antonym: contentment</pre>
</div>

<div class="entry">
  <pre>382. Ambulance (অ্যাম্বুলেন্স) - অ্যাম্বুলেন্স  
Synonym: emergency vehicle  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>383. Amend (অ্যামেন্ড) - সংশোধন করা  
Synonym: modify  
Antonym: worsen</pre>
</div>

<div class="entry">
  <pre>384. Amount (অ্যামাউন্ট) - পরিমাণ  
Synonym: quantity  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>385. Amuse (অ্যামিউজ) - মনোরঞ্জন করা  
Synonym: entertain  
Antonym: bore</pre>
</div>

<div class="entry">
  <pre>386. Analyze (অ্যানালাইজ) - বিশ্লেষণ করা  
Synonym: examine  
Antonym: ignore</pre>
</div>

<div class="entry">
  <pre>387. Ancient (এনসিয়েন্ট) - প্রাচীন  
Synonym: old  
Antonym: modern</pre>
</div>

<div class="entry">
  <pre>388. And (এন্ড) - এবং  
Synonym: plus  
Antonym: or</pre>
</div>

<div class="entry">
  <pre>389. Anger (অ্যাঙ্গার) - রাগ  
Synonym: rage  
Antonym: calm</pre>
</div>

<div class="entry">
  <pre>390. Angle (অ্যাঙ্গেল) - কোণ  
Synonym: corner  
Antonym: —</pre>
</div>
<div class="entry">
  <pre>391. Animal (অ্যানিমাল) - প্রাণী  
Synonym: creature  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>392. Announce (অ্যানাউন্স) - ঘোষণা করা  
Synonym: proclaim  
Antonym: conceal</pre>
</div>

<div class="entry">
  <pre>393. Annual (অ্যানুয়াল) - বার্ষিক  
Synonym: yearly  
Antonym: monthly</pre>
</div>

<div class="entry">
  <pre>394. Another (অ্যানাদার) - অন্য  
Synonym: additional  
Antonym: same</pre>
</div>

<div class="entry">
  <pre>395. Answer (আন্সার) - উত্তর  
Synonym: reply  
Antonym: question</pre>
</div>

<div class="entry">
  <pre>396. Anticipate (অ্যান্টিসিপেট) - প্রত্যাশা করা  
Synonym: expect  
Antonym: doubt</pre>
</div>

<div class="entry">
  <pre>397. Anxiety (অ্যাংজাইটি) - উদ্বেগ  
Synonym: worry  
Antonym: calmness</pre>
</div>

<div class="entry">
  <pre>398. Any (এনি) - যেকোনো  
Synonym: whichever  
Antonym: none</pre>
</div>

<div class="entry">
  <pre>399. Apart (অপার্ট) - আলাদা  
Synonym: separate  
Antonym: together</pre>
</div>

<div class="entry">
  <pre>400. Apology (অ্যাপোলজি) - ক্ষমা  
Synonym: excuse  
Antonym: blame</pre>
</div>
<div class="entry">
  <pre>401. Apparent (অ্যাপ্যারেন্ট) - স্পষ্ট  
Synonym: obvious  
Antonym: hidden</pre>
</div>

<div class="entry">
  <pre>402. Appeal (অ্যাপিল) - আবেদন  
Synonym: request  
Antonym: refuse</pre>
</div>

<div class="entry">
  <pre>403. Applaud (অ্যাপলড) - প্রশংসা করা  
Synonym: praise  
Antonym: criticize</pre>
</div>

<div class="entry">
  <pre>404. Apply (অ্যাপ্লাই) - প্রয়োগ করা  
Synonym: use  
Antonym: ignore</pre>
</div>

<div class="entry">
  <pre>405. Appointment (অ্যাপয়েন্টমেন্ট) - নিয়োগ  
Synonym: meeting  
Antonym: cancellation</pre>
</div>

<div class="entry">
  <pre>406. Appreciate (অ্যাপ্রিসিয়েট) - প্রশংসা করা  
Synonym: value  
Antonym: disregard</pre>
</div>

<div class="entry">
  <pre>407. Approach (অ্যাপ্রোচ) - নিকট হওয়া  
Synonym: method  
Antonym: avoidance</pre>
</div>

<div class="entry">
  <pre>408. Appropriate (অ্যাপ্রোপ্রিয়েট) - উপযুক্ত  
Synonym: suitable  
Antonym: inappropriate</pre>
</div>

<div class="entry">
  <pre>409. Approve (অ্যাপ্রুভ) - অনুমোদন করা  
Synonym: accept  
Antonym: reject</pre>
</div>

<div class="entry">
  <pre>410. Approximate (অ্যাপ্রোক্সিমেট) - আনুমানিক  
Synonym: estimated  
Antonym: exact</pre>
</div>

<div class="entry">
  <pre>411. April (এপ্রিল) - এপ্রিল মাস  
Synonym: —  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>412. Arch (আর্চ) - তালা  
Synonym: curve  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>413. Area (এরিয়া) - এলাকা  
Synonym: region  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>414. Argue (আর্গু) - বিতর্ক করা  
Synonym: debate  
Antonym: agree</pre>
</div>

<div class="entry">
  <pre>415. Arise (অ্যারাইজ) - উদ্ভব হওয়া  
Synonym: emerge  
Antonym: disappear</pre>
</div>

<div class="entry">
  <pre>416. Arm (আর্ম) - হাত  
Synonym: limb  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>417. Army (আর্মি) - সেনাবাহিনী  
Synonym: military  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>418. Arrange (অ্যারের) - সাজানো  
Synonym: organize  
Antonym: disorder</pre>
</div>

<div class="entry">
  <pre>419. Arrest (অ্যারেস্ট) - গ্রেপ্তার করা  
Synonym: capture  
Antonym: release</pre>
</div>

<div class="entry">
  <pre>420. Arrive (অ্যারাইভ) - পৌঁছানো  
Synonym: reach  
Antonym: depart</pre>
</div>

<div class="entry">
  <pre>421. Art (আর্ট) - শিল্প  
Synonym: craft  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>422. Article (আর্টিকেল) - প্রবন্ধ  
Synonym: essay  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>423. Artist (আর্টিস্ট) - শিল্পী  
Synonym: painter  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>424. As (অ্যাজ) - যেমন  
Synonym: like  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>425. Ash (অ্যাশ) - ছাই  
Synonym: residue  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>426. Aside (অ্যাসাইড) - একপাশে  
Synonym: aside  
Antonym: front</pre>
</div>

<div class="entry">
  <pre>427. Ask (আস্ক) - জিজ্ঞেস করা  
Synonym: inquire  
Antonym: answer</pre>
</div>

<div class="entry">
  <pre>428. Asleep (অ্যাস্লিপ) - ঘুমন্ত  
Synonym: sleeping  
Antonym: awake</pre>
</div>

<div class="entry">
  <pre>429. Aspect (অ্যাসপেক্ট) - দিক  
Synonym: feature  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>430. Assist (অ্যাসিস্ট) - সাহায্য করা  
Synonym: help  
Antonym: hinder</pre>
</div>

<div class="entry">
  <pre>431. Associate (অ্যাসোসিয়েট) - যুক্ত করা  
Synonym: connect  
Antonym: separate</pre>
</div>

<div class="entry">
  <pre>432. Assume (অ্যাসিউম) - অনুমান করা  
Synonym: suppose  
Antonym: doubt</pre>
</div>

<div class="entry">
  <pre>433. Assure (অ্যাসিউর) - নিশ্চয়তা দেওয়া  
Synonym: guarantee  
Antonym: doubt</pre>
</div>

<div class="entry">
  <pre>434. Astonish (অ্যাস্টনিশ) - বিস্মিত করা  
Synonym: surprise  
Antonym: bore</pre>
</div>

<div class="entry">
  <pre>435. Astute (অ্যাস্টিউট) - সূক্ষ্মবুদ্ধি সম্পন্ন  
Synonym: shrewd  
Antonym: foolish</pre>
</div>

<div class="entry">
  <pre>436. Asylum (অ্যাসাইলাম) - আশ্রয়  
Synonym: refuge  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>437. At (অ্যাট) - এ  
Synonym: in  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>438. Athlete (অ্যাথলিট) - ক্রীড়াবিদ  
Synonym: sportsman  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>439. Atmosphere (অ্যাটমোস্ফিয়ার) - পরিবেশ  
Synonym: environment  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>440. Attach (অ্যাটাচ) - সংযুক্ত করা  
Synonym: connect  
Antonym: detach</pre>
</div>

<div class="entry">
  <pre>441. Attack (অ্যাটাক) - আক্রমণ করা  
Synonym: assault  
Antonym: defend</pre>
</div>

<div class="entry">
  <pre>442. Attempt (অ্যাটেম্পট) - চেষ্টা করা  
Synonym: try  
Antonym: give up</pre>
</div>

<div class="entry">
  <pre>443. Attend (অ্যাটেন্ড) - উপস্থিত থাকা  
Synonym: be present  
Antonym: absent</pre>
</div>

<div class="entry">
  <pre>444. Attitude (অ্যাটিটিউড) - মনোভাব  
Synonym: mindset  
Antonym: indifference</pre>
</div>

<div class="entry">
  <pre>445. Attorney (অ্যাটর্নি) - আইনজীবী  
Synonym: lawyer  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>446. Attractive (অ্যাট্রাক্টিভ) - আকর্ষণীয়  
Synonym: appealing  
Antonym: unattractive</pre>
</div>

<div class="entry">
  <pre>447. Attribute (অ্যাট্রিবিউট) - গুণ  
Synonym: quality  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>448. Audience (অডিয়েন্স) - দর্শক  
Synonym: spectators  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>449. Author (অথর) - লেখক  
Synonym: writer  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>450. Automatic (অটোমেটিক) - স্বয়ংক্রিয়  
Synonym: mechanical  
Antonym: manual</pre>
</div>
<div class="entry">
  <pre>451. Available (অ্যাভেইলেবল) - উপলব্ধ  
Synonym: accessible  
Antonym: unavailable</pre>
</div>

<div class="entry">
  <pre>452. Average (অ্যাভারেজ) - গড়  
Synonym: normal  
Antonym: exceptional</pre>
</div>

<div class="entry">
  <pre>453. Avoid (অ্যাভয়েড) - এড়ানো  
Synonym: evade  
Antonym: confront</pre>
</div>

<div class="entry">
  <pre>454. Awake (অ্যাওয়েক) - জেগে থাকা  
Synonym: alert  
Antonym: asleep</pre>
</div>

<div class="entry">
  <pre>455. Award (অ্যাওয়ার্ড) - পুরস্কার  
Synonym: prize  
Antonym: penalty</pre>
</div>

<div class="entry">
  <pre>456. Aware (অ্যাওয়ার) - সচেতন  
Synonym: conscious  
Antonym: unaware</pre>
</div>

<div class="entry">
  <pre>457. Away (অ্যাওয়ে) - দূরে  
Synonym: distant  
Antonym: near</pre>
</div>

<div class="entry">
  <pre>458. Awesome (অ্যাওসম) - চমৎকার  
Synonym: amazing  
Antonym: awful</pre>
</div>

<div class="entry">
  <pre>459. Awful (অ্যাফুল) - ভয়ঙ্কর  
Synonym: terrible  
Antonym: wonderful</pre>
</div>

<div class="entry">
  <pre>460. Awkward (অ্যকওয়ার্ড) - অস্বস্তিকর  
Synonym: clumsy  
Antonym: graceful</pre>
</div>

<div class="entry">
  <pre>461. Axis (অ্যাক্সিস) - অক্ষ  
Synonym: pivot  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>462. Azure (অ্যাজুর) - আকাশি রং  
Synonym: sky blue  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>463. Abandon (অ্যাব্যান্ডন) - পরিত্যাগ করা  
Synonym: leave  
Antonym: keep</pre>
</div>

<div class="entry">
  <pre>464. Abate (অ্যাবেট) - কমানো  
Synonym: lessen  
Antonym: increase</pre>
</div>

<div class="entry">
  <pre>465. Abdicate (অ্যাবডিকেট) - পদত্যাগ করা  
Synonym: resign  
Antonym: retain</pre>
</div>

<div class="entry">
  <pre>466. Abduct (অ্যাবডাক্ট) - অপহরণ করা  
Synonym: kidnap  
Antonym: release</pre>
</div>

<div class="entry">
  <pre>467. Abhor (অ্যাবহোর) - ঘৃণা করা  
Synonym: detest  
Antonym: love</pre>
</div>

<div class="entry">
  <pre>468. Abide (অ্যাবাইড) - মানা  
Synonym: comply  
Antonym: disobey</pre>
</div>

<div class="entry">
  <pre>469. Ability (অ্যাবিলিটি) - সক্ষমতা  
Synonym: capability  
Antonym: inability</pre>
</div>

<div class="entry">
  <pre>470. Able (অ্যাবল) - সক্ষম  
Synonym: capable  
Antonym: incapable</pre>
</div>

<div class="entry">
  <pre>471. Abnormal (অ্যাবনরমাল) - অস্বাভাবিক  
Synonym: unusual  
Antonym: normal</pre>
</div>

<div class="entry">
  <pre>472. Aboard (অ্যাবোর্ড) - বোর্ডে  
Synonym: on board  
Antonym: ashore</pre>
</div>

<div class="entry">
  <pre>473. Abolish (অ্যাবলিশ) - বিলুপ্ত করা  
Synonym: eliminate  
Antonym: establish</pre>
</div>

<div class="entry">
  <pre>474. Abominable (অ্যাবমিনেবল) - ঘৃণ্য  
Synonym: detestable  
Antonym: delightful</pre>
</div>

<div class="entry">
  <pre>475. Aboriginal (অ্যাবরিজিনাল) - আদিবাসী  
Synonym: native  
Antonym: foreign</pre>
</div>

<div class="entry">
  <pre>476. Abort (অ্যাবর্ট) - বাতিল করা  
Synonym: cancel  
Antonym: continue</pre>
</div>

<div class="entry">
  <pre>477. Abrupt (অ্যাবরপ্ট) - হঠাৎ  
Synonym: sudden  
Antonym: gradual</pre>
</div>

<div class="entry">
  <pre>478. Absence (অ্যাবসেন্স) - অনুপস্থিতি  
Synonym: nonattendance  
Antonym: presence</pre>
</div>

<div class="entry">
  <pre>479. Absolute (অ্যাবসোলিউট) - সম্পূর্ণ  
Synonym: complete  
Antonym: partial</pre>
</div>

<div class="entry">
  <pre>480. Absorb (অ্যাবসর্ব) - শোষণ করা  
Synonym: soak up  
Antonym: release</pre>
</div>

<div class="entry">
  <pre>481. Abstain (অ্যাবস্টেইন) - বিরত থাকা  
Synonym: refrain  
Antonym: indulge</pre>
</div>

<div class="entry">
  <pre>482. Abstract (অ্যাবস্ট্রাক্ট) - বিমূর্ত  
Synonym: theoretical  
Antonym: concrete</pre>
</div>

<div class="entry">
  <pre>483. Abundant (অ্যাবান্ডান্ট) - প্রচুর  
Synonym: plentiful  
Antonym: scarce</pre>
</div>

<div class="entry">
  <pre>484. Abuse (অ্যাবিউজ) - অপব্যবহার  
Synonym: mistreatment  
Antonym: care</pre>
</div>

<div class="entry">
  <pre>485. Academic (অ্যাকাডেমিক) - শিক্ষাগত  
Synonym: scholarly  
Antonym: unacademic</pre>
</div>

<div class="entry">
  <pre>486. Accelerate (অ্যাকসেলেরেট) - দ্রুততর হওয়া  
Synonym: speed up  
Antonym: decelerate</pre>
</div>

<div class="entry">
  <pre>487. Accept (অ্যাকসেপ্ট) - গ্রহণ করা  
Synonym: receive  
Antonym: refuse</pre>
</div>

<div class="entry">
  <pre>488. Access (অ্যাকসেস) - প্রবেশাধিকার  
Synonym: entry  
Antonym: denial</pre>
</div>

<div class="entry">
  <pre>489. Accident (অ্যাকসিডেন্ট) - দুর্ঘটনা  
Synonym: mishap  
Antonym: intention</pre>
</div>

<div class="entry">
  <pre>490. Acclaim (অ্যাকলেইম) - প্রশংসা করা  
Synonym: praise  
Antonym: criticize</pre>
</div>

<div class="entry">
  <pre>491. Accommodate (অ্যাকোমোডেট) - ব্যবস্থা করা  
Synonym: lodge  
Antonym: inconvenience</pre>
</div>

<div class="entry">
  <pre>492. Accompany (অ্যাকাম্পানি) - সঙ্গ দেওয়া  
Synonym: escort  
Antonym: abandon</pre>
</div>

<div class="entry">
  <pre>493. Accomplish (অ্যাকমপ্লিশ) - সম্পন্ন করা  
Synonym: achieve  
Antonym: fail</pre>
</div>

<div class="entry">
  <pre>494. According (অ্যাকর্ডিং) - অনুযায়ী  
Synonym: as per  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>495. Account (অ্যাকাউন্ট) - হিসাব  
Synonym: record  
Antonym: —</pre>
</div>

<div class="entry">
  <pre>496. Accumulate (অ্যাকিউমুলেট) - সঞ্চয় করা  
Synonym: collect  
Antonym: disperse</pre>
</div>

<div class="entry">
  <pre>497. Accurate (অ্যাকিউরেট) - সঠিক  
Synonym: precise  
Antonym: inaccurate</pre>
</div>

<div class="entry">
  <pre>498. Accuse (অ্যাকিউজ) - অভিযুক্ত করা  
Synonym: blame  
Antonym: defend</pre>
</div>

<div class="entry">
  <pre>499. Achieve (অ্যাচিভ) - অর্জন করা  
Synonym: accomplish  
Antonym: fail</pre>
</div>

<div class="entry">
  <pre>500. Acknowledge (অ্যাকনলেজ) - স্বীকার করা  
Synonym: admit  
Antonym: deny</pre>
</div>

    
  </div>

  <script>
    function searchData() {
      const value = document.getElementById("searchInput").value.trim().toLowerCase();
      const resultBox = document.getElementById("resultBox");
      resultBox.innerHTML = "";

      const allItems = document.querySelectorAll("#dataList .entry");
      let found = false;

      allItems.forEach(item => {
        const text = item.textContent.toLowerCase();
        if (text.includes(value)) {
          resultBox.appendChild(item.cloneNode(true));
          found = true;
        }
      });

      if (!found) {
        resultBox.textContent = "কোনও মিল পাওয়া যায়নি!";
      }
    }
  </script>

</body>
</html>
