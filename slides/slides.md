---
marp: true
theme: custom-default
paginate: true
---

![bg left:40% ](./img/maneki-neko.avif)
# こんにちは!

## Stay fit 💪 Code better 🧑‍💻
Presenter: **Csaba Tamas**

>  A sportsman’s real life practical advices for JavaScript Developers

<!--
こんにちは, (ko-n-ni-csi-va) everyone! Thank you for joining me today.
My name is Csaba Tamas, Today, I would like to share my real life practical advices
to help you stay fit and code better.
And don’t worry—I’ve included some JavaScript magic to make it interesting for all of us!
 -->

---

## About me 🧔🏻‍♂️
👨‍💻 Frontend Architect

🅰️ Angular contributor

🏋️‍♀️Powerlifter competitor

![bg right:63% ](./img/fuji.jpg)

<!--
Let me quickly introduce myself.
👨‍💻 I’m a frontend architect from Hungary 🇭🇺 with more than 10 years of experience, mostly I worked with angular projects, but nowdays I also work with react based technoligies.
🏋️‍♀️ Outside of coding, I’ve been actively involved in competitive powerlifting and natual bodybuilding.
Powerlifting is the combination of the main bodybuilding excercises. (squat, deadlift and benchpress).

I can tell I have quite good competition results.
I rank around the middle of the hungarian leaderboard, with 500kg total.

I’m really passionate about any health related topic. I could talk about them for hours!
-->

---

# Why ligthning talk? ⚡️

- It is a JavaScript conference, this topic is not so related to JS world, but I tried to add the maxium amount of developer content to it (dark slides).
- I try to give you the most of the takeaways what I can
- I would like to share my own experiances, how I was able to improve my life with some small changes. I hope you will like it. 🤗

<!--
But today it is "only" kightning talk, but why?
Because this is a JavaScript conference, and I know not all of you are interested in the topic. But I’ve tried to collect lot of interesting statistics and information.

I would like to share my own experiances, how I was able to improve my life with some small changes.

My goal is to give you as many takeaways as I can,
if you are interedted only JS just follow the dark slides.
-->

---
<!-- _class: invert -->

# Slides
- **Marp**: markdown presentation ecosystem from **Yuki Hattori** 🇯🇵
- It is a powerful TypesSript based framework, that enables you to create stunning slides effortlessly.
- You can download my slides from  [JSConf.JP](https://jsconf.jp)

![bg right:40% height:100](./img/marp-dark.png)

<!--

By the way, these slides are made with Marp, a TypeScript-based framework created by Japanese developer Yuki Hattori.

You can download these slides later from JSConf.JP.
-->

---

<!-- _class: invert -->

# <!--fit --> MarpAI.app
Feel free to join if you are interedted.

![bg right:40% height:100](./img/marp-dark.png)

<!--

I have just started to develop project which is an online presentation editor based on Mar.
-->

---

# Let's start with my favorite topic: STRENGTH 🏋️‍♀️
> The average grip strength of **women** from the **1970s** is comparable to that of **teeneager boys today**.

> In the 2020 [study](https://pmc.ncbi.nlm.nih.gov/articles/PMC7877981/) shows the people with lower grip strength were more likely (20%) to die of any cause compared to people with higher grip strength.

#### But why it is important? 💪
- It isn't just important for daily tasks (carry groceries, lift objects etc..).
- Strength helps you to live a better quality life. Everything became easier.
- It reduces the risk of injuries, by improving your balance and stability.
- More strength equals more muscle which helps you in the weight management
- **Reduce mortality**.

<!--
Let’s start with my favorite topic strength.

Did you know the grip strength of today’s average teenagers is weaker than that of women in the 1970s?

So we became weaker and weaker time by time.
But why the strength important:

A 2020 study found that people with lower strength were 20% more likely to die prematurely.
Strength improves balance, reduces injuries.
Strength helps you to live a better quality life. Everything became easier.
Earlier I had a lot of back problem, but after I started train it became much better.

 -->

---
# How can we improve our strength? 🏋️‍♀️

First advice: **Just lift weights.**
![bg right ](./img/stone-lifting.jpg)


<!-- _footer: Japan’s hidden strength culture you didn’t know of - Chikara Ishi 力石 https://www.youtube.com/watch?v=3CEjK9haKSQ -->

<!--
My advice? Just lift weights.
It doesn’t have to be heavy; consistency is key. You can even start with bodyweight exercises or resistance bands.
It is not necesary to go the the gym you know one of the acciant sport is the traditional japanese stone lifting.
 -->

---
![bg contain](./img/adjustable-kettlebell.webp)

Adjustable kettlebell
From: 3,4-18kg

<!-- If you’re looking for a simple tool to get started, try adjustable kettlebells. They’re compact, versatile, and perfect for a quick home workout. As developers, efficiency matters, and this is the Swiss Army knife of fitness equipment, you can reach the maximum performance what you need. -->

---
<!-- _class: invert -->
# Howto calculate your maximum performance with JS

```javascript
const weight = 100; // Weight in kg
const reps = 5; // Repetitions

function calculate1RM(weight, reps) {
  return {
    epley: weight * (1 + reps / 30),
    brzycki: weight * (36 / (37 - reps)),
    mcglothin: weight * (100 / (101.3 - 2.67123 * reps)),
    lombardi: weight * Math.pow(reps, 0.10),
    mayhew: (100 * weight) / (52.2 + 41.9 * Math.exp(-0.055 * reps))
  }
}

console.log(calculate1RM(weight, reps));
/*
{
  epley : 116.66666666666667,
  brzycki: 112.5,
  mcglothin: 113.70891767872342,
  lombardi: 117.4618943088019,
  mayhew : 119.01068045151959
}
/*
```

---

# Perfect workstation for perfect performance 💪

> Office workers with proper ergonomic setups report a 15% reduction in pain and a 12% productivity boost -> [PubMed Central](https://pmc.ncbi.nlm.nih.gov/articles/PMC8010160/).

> Poor posture leads to back and neck pain, affecting 50% of tech workers -> [American Chiropractic Association](https://www.acatoday.org/news-publications/trending-in-the-media-and-at-home-musculoskeletal-pain/).

> 70% of tech workers experience computer vision syndrome -> [American Optometric Association](https://www.aoa.org/about-the-aoa/press-room/press-releases/most-americans-experience-digital-eye-strain-from-overexposure-to-computers-according-to-survey).

> Regular movement boosts **creativity** by 81% (*Stanford University, 2014*).

![bg right:35%](./img/workstation.jpg)

<!--
The right side this is my workstation. As you can see I using a standing table with a walking pad.
It is really important to setup the proper desk and monitor height of the to make it comfortable.

The best if the monitor center is front of you eyes and you can lie your fingers to the keyboard.

 -->

---

#  How much is the ideal breaks? ⏰
 Ideal break :
  - For eyes: Every 20 minutes you should have a break and for 20 secounds 20 feet away, like looking out of the window
  - Take a 5-10 minute break every hour to stretch, walk around, hydrate, or simply relax your mind.

 Use break reminder apps like:
 -  Time Out, Breaktimer,  Pandan, Zenbreak, Breather, TotalPause or Stretchly

**Small, consistent recovery breaks = Better performance in the long run!**

<!--
Screen time takes a toll on your eyes. 70% of tech workers experience symptoms of Computer Vision Syndrome, including headaches and dry eyes.

Here’s my 4th tip: Use break reminder apps like Time Out or Stretchly. The 20-20-20 rule works wonders: Every 20 minutes, look 20 meters away for 20 seconds. For overall health, take a 5-10 minute break every hour.
-->

---
<!-- _class: invert -->
# How to use Notification API
```javascript
Notification.requestPermission();

function showNotification(title, body) {
  if (Notification.permission === "granted") {
    new Notification(title, { body });
  }
}

// Notify for eye break every 20 minutes
setInterval(() => {
  showNotification(
    "Eye Break Reminder",
    "Time for a 20-second eye break! Look away from your screen."
  );
}, 20 * 60 * 1000);

// Notify for rest every hour
setInterval(() => {
  showNotification(
    "Get Up and Rest",
    "It's time to get up and take a 5-10 minute rest!"
  );
}, 60 * 60 * 1000);
```

---

# The power of deep sleep. 🚀

> Sleep deprivation affects memory, focus, and productivity. One sleepless night reduces cognitive performance by up to 30% (*Nature*).

> Developers sleeping 7–8 hours are 29% more productive than those with less than 6 hours (*Sleep Foundation*).

### Track and optimize sleep patterns
Athletes need 8–10 hours per night for optimal recovery.
Developers benefit similarly for focus and creativity, but not only the quantity is important.
It is really important to take time in deep sleep (stage 3) and not to stop it.

<!--
Sleep is the unsung hero of productivity. Athletes need 8–10 hours of sleep for recovery, and developers benefit similarly.
Deep sleep, in particular, helps consolidate memory and repair the body. Skipping it reduces cognitive performance by up to 30%.

Use apps like SleepCycle to track your sleep. Prioritize quality over quantity to wake up refreshed and focused.
 -->

---

# How can I improve my sleep quality?:
Do not use the default alarm clock. Instead use **SleepCycle**  or any other app to track and analyze sleep data.


# Let's take a look at one of the biggest health issues in Japan 🇯🇵
## Overwork and Burnout 🔥

> In the tech industry in Japan, 57% of developers report working more than 8 hours daily, leading to burnout (*Stack Overflow Developer Survey*).

> Burnout rates among developers have increased by 18% in the last five years (*Gallup Workplace Study, 2023*).

> Overwork increases the risk of depression by 60% (*Journal of Occupational Health*).

<!--
Japan’s culture of overwork has led to burnout becoming a significant issue. 57% of developers here work more than 8 hours a day, and burnout rates have increased by 18% in five years.

How do we tackle this? Sports teach us to:

Set clear goals: Prioritize what matters.
Maintain consistency: Sustainable habits beat sporadic sprints.
Value recovery: Rest isn’t optional—it’s essential.
Work as a team: Share the workload and support each other.
-->

---

## How sports mentality solves this:
1. **Set clear goals**: Like athletes, prioritize measurable daily goals and set boundaries for work hours.
2. **Consistency, not intensity**:  Use structured techniques like Pomodoro.
3. **Prioritize recovery**: Athletes invest in rest. We should too, using tools like **Calm** for mental recovery.
5. **Think long-term**: Life is a marathon not a marathon. We should focus on sustainable long-term growth.


---
# Food 🍜
> The Japanese diet is linked to a 15% lower risk of early death compared to Western diets (*BMJ, 2016*).

> Japan has one of the highest life expectancies globally (85 years) due to its nutrient-rich traditional meals (*WHO, 2023*).

<br>

**Just eat your traditional meals.**

![bg right:40%](./img/food.jpg)

<!--
The Japanese diet is a global benchmark for health.

My advice? Stick to nutrient-dense, whole foods. If possible, incorporate elements of the Japanese diet into your routine.
 -->

---

### My final takeaway:
# Life is like to squat, find tha balance in your life.

<!--
Here’s my final takeaway: Life is like a squat—it’s about balance. Balancing mobility and stability is key in both sports and life. Similarly, balancing work and health leads to sustainable success.
-->

---

# Thank you very much!

ありがとう ございます

# 🙋🏻‍♀️ Questions? 🙋🏻

![bg right](./img/crane-and-turtle.jpg)

<!--

Árigatō Gozájmász

Thank you all for listening! Remember, taking care of your health isn’t just a personal investment—it’s a professional one too. I’m happy to answer any questions you have.
-->