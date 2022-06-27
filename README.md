# Egg Timer 수업으로 배운 점 및 원자료

## 실습으로 배운 점
* 계란 요리법에 따른 시간을 Dictionaty, if-else 와 switch 등으로 표현 (Angela: 조건 개수가 5개 미만일 경우 if-else, 그 외의 경우 switch가 효율적).
* Swift Timer 및 앞선 실습에서 배운 AVFoundation,  AVAudioPlayer 사용 연습.
* Progress Veiw 사용 (진행상태는 0.0 ~ 1.0 의 숫자로 표시되며, progressBar.progress = Float(secondsPassed) / Float(totalTime) 등으로 사용. timer.invalidate()은 timer의 사용을 중단시킬 때 사용: Stops the timer from ever firing again and requests its removal from its run loop).  
* timer = Timer.scheduledTimer(timeInterval: 1.0, target: self, selector:#selector(updateTimer), userInfo: nil, repeats: true)

## 수업 원자료는 아래와 같음
![App Brewery Banner](Documentation/AppBreweryBanner.png)

# Egg Timer

## Our Goal

This module will be a mix of tutorials and challenges. Most importantly, we want you to get comfortable with looking up how to do something you've never done before. In certain places of this module, you’ll need to follow the 5 step process you learnt in the Xylophone module and use Google search, StackOverflow and Apple Documentation to make your code do what you want it to. But there are also other parts where we’ll take you step-by-step through new Swift programming concepts. 

## What You'll Make

You’ll be building a beautiful egg timer app to boil your eggs to perfection depending on how you prefer your eggs. 

## What you will learn

* Swift Collection types - Dictionaries
* The Swift Timer API
* Conditional statements - IF/ELSE
* Conditional statements - Switch
* Functions with outputs
* How to use the ProgressView



>This is a companion project to The App Brewery's Complete App Development Bootcamp, check out the full course at [www.appbrewery.co](https://www.appbrewery.co/)

![End Banner](Documentation/readme-end-banner.png)

