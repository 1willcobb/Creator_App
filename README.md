# Creator_App

The Creator App is an app to manage a Creator's cross platform influence and financial management.

## Figma

https://www.figma.com/file/Fmx1sUAOSJZDFFbjr8eenN/%22App-Name-Here%22---Project-1-Group-Project?type=design&node-id=0%3A1&t=8fKFVH06Jsgbxh1K-1

## Group Rolls

* Project Manager:
* UI:
* UX:
* API Developers:


## The Problem 

Creators post their content and utilize multiple platforms while only having access to 1 at a time, or multiple windows open to see and track all their data at once. 
What if there was one place they could access their metrics, track and manage their income, and budget and set goals for the future of their career. 

## User Stories

* AS A user I WANT to see all my social media, commerce, courses, and merch data SO THAT I can manage and view my accounts and income in once place

* AS A user I WANT to log in securely and for the app to remember my data SO THAT I dont have to type it over and over and someone else can't use stele my information.

* AS A USER, when make an accont, I WANT to put in my USER NAME for each platform, and any special API keys once and those to be remembered SO THAT the app can remember my info.

* AS A USER, after the app knows my account, I WANT the app to pull my info and provide me with widgets with my data in it so i can see my data clearly with no other widgets showing.

* a button should unhide those widgets if the creator wants to add more platforms. (the user will be greeted with a "COMING SOON" on every platform we do not find API for)

* Upon second log in, the User will be greeted with the widgets of choice with their corresponding data. 

* A master widget spanning the whole top will be on top holding an average of all incomes, an average of entire social impact, and distance to goals.

* There should be a goal setting widget, or maybe a page? 

* Note some platforms we will not be able to gater financial or any data at all and should possibly have an input form for people to help calculate a total. 

## Platforms considered

### Social

* Facebook
* Instaragram
* TikTok
* Twitter (paid)
* YouTube - https://developers.google.com/youtube/v3/docs/channels
`https://www.googleapis.com/youtube/v3/channels?part=snippet,statistics&id=${channelId}&key=${apiKey}`
* Twitch
* Snap chat
* Patreon

### Music

* Spotify - $.003 -to- $.005 per stream 
* Apple Music

### Courses

* Teachable
* Kajabi
* Skillshare
* Udemy
* Thinkific 

### E-Commerce

* Shopify
* Wix
* Squarespace

### Merchendice

* T-Spring
* Threads
* UberPrints
* Captiv8
* Vista Print
* Awesome Merch

## Competition

Platforms like social blade[https://socialblade.com/youtube/c/1willcobb] and VidIQ [https://vidiq.com/] both leverage the YouTube API and parse comparisons. They also use key word searching with potentially the google search API. But they both are generally single platform and dont let you agigate multi platform or finances. 

