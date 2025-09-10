# Question 1: What is system design?

## Introduction / Hook
नमस्ते दोस्तों!  
<!-- आज हम detail में समझेंगे — "System Design" क्या है और इसका इस्तेमाल कहाँ किया जाता है। (On-screen text: "System Design Basics")   -->
System Design software development की दुनिया का foundation है।  
अगर आप एक छोटा सा app बना रहे हैं, या फिर Netflix और Amazon जैसे बड़े scale पर system design कर रहे हैं — आपको पहले यह clear होना चाहिए कि structure कैसा होगा, data कैसे flow करेगा और system future load को कैसे handle करेगा।  

---

## Section 1: Definition
System Design का मतलब है — किसी भी system को design करने की **structured process**।    
इसमें हम define करते हैं:  
- Components क्या होंगे  
- Data कैसे move करेगा  
- Users को कैसा experience मिलेगा  

<!-- (Narration cue: "Think of it like an architect designing a building.")   -->

<!-- Visual cue: Animation में architect एक building का blueprint बना रहा है → फिर वही building construct होकर तैयार हो रही है।   -->

---

## Section 2: Purpose
System Design का सबसे बड़ा purpose है —  
1. एक clear blueprint देना ताकि हर developer और architect को पता रहे कि कौन-सा module कैसे काम करेगा।  
2. Future load handle करने के लिए scalability और reliability ensure करना।  
3. Errors और miscommunication को कम करना।  

Example: अगर Ola या Uber अपने system design को strong ना रखते, तो peak hours में पूरा system down हो जाता।  

<!-- (On-screen text: "Purpose = Structure + Flow + Experience")   -->

---

## Section 3: Types of System Design
System Design को दो main parts में divide किया जाता है।  

1. **High-Level Design (HLD)** → यह हमें पूरी architecture दिखाता है।  
   इसमें modules और उनके interactions define होते हैं।  
   Example: Client → API → Database → Services।  

2. **Low-Level Design (LLD)** → इसमें हर module का internal detail define होता है।  
   Example: कौन-सी class होगी, कौन-सा method कौन-सा काम करेगा, कौन-सा database table कहाँ use होगा।  
