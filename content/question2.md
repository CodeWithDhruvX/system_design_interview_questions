# Question 2: Difference between high-level and low-level design

## Introduction / Hook
नमस्ते दोस्तों!   
<!-- आज हम समझेंगे **High-Level Design (HLD)** और **Low-Level Design (LLD)** में actual difference। (On-screen text: "HLD vs LLD")   -->
ये दोनों design approaches एक-दूसरे के complement हैं — एक हमें big picture देता है और दूसरा हर छोटे-छोटे detail को define करता है।  

---

## Section 1: High-Level Design (HLD)
HLD का काम है system की **overall architecture** को define करना।  
इसमें हम देखेंगे:  
- कौन-से major modules होंगे  
- उनके बीच interaction कैसे होगा  
- Data का flow कैसे manage होगा  

Example: Zomato का HLD define करेगा — user app से request करेगा → API call जाएगी → server उस request को handle करेगा → और फिर database से data fetch होगा।  

<!-- (Narration cue: "HLD is like a city map showing roads and areas.")   -->

<!-- Visual cue: City map animation जिसमें अलग-अलग areas roads से जुड़े हुए हैं।   -->

---

## Section 2: Low-Level Design (LLD)
LLD हर module के अंदर के detail पर focus करता है।  
इसमें हम define करते हैं:  
- Classes और उनके attributes  
- Functions और उनका logic  
- Database tables और उनकी schema  

Example: Payment module का LLD बताएगा — Payment class में `processPayment()` method होगा, User table में `user_id`, `name`, `email` columns होंगे।  

<!-- (Narration cue: "LLD is like a detailed floor plan for each building.")   -->

<!-- Visual cue: Blueprint zoom होकर एक floor plan दिखा रहा है जिसमें कमरे, दरवाजे और दीवारें detail में हैं।   -->

---

## Section 3: Comparison
अगर हम simple शब्दों में कहें:  
- HLD = Big Picture (Architecture level)  
- LLD = Micro Detail (Implementation level)  

<!-- (On-screen text: "HLD = Architecture | LLD = Details")   -->

<!-- Visual cue: Split screen animation → Left side पर पूरा city map (HLD) और right side पर building floor plan (LLD)।   -->

---

## Conclusion / Call-to-action
तो दोस्तों, अब आपके लिए HLD और LLD का फर्क crystal clear होना चाहिए।   
HLD vision देता है, और LLD उस vision को practically implement करता है।  
<!-- (On-screen text: "Design Complete = HLD + LLD")   -->

Call-to-action:  
अगर ये explanation useful लगी हो तो comment में बताइए, और अब अगले video में हम Scalability समझेंगे।  

---