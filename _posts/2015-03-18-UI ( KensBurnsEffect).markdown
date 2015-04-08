---
layout: post
title:  "UI/UX - Not So Boring Action Bar"
date:   2015-03-18 13:54:48
categories: fourth post
---

Hello readers,

Any mobile application is success only if it provides better user experience and interface (UX/UI). Considering that in mind, we discussed various UI/UX implementations , what we should include in our app. We went through various apps in the google play store, but none were as appealing as the Google Play NewsStand by Google. The ActionBar animations and effects plus UX it provides is remarkable. So we came up with the idea of using the same effect, with ActionBar being "NOT SO BORING". 

Action Bar of our app includes Pager Title Strip for swipe views with floating toolbar , new feature in Android API 22 [5.0 - Lollipop]. It includes parallax header with Ken Burns Effect, a ViewPager and Fragments containing scrollviews.

How to implement "NOT SO BORING ACTION BAR"
============

To implement this we imported three libraries : 

* [PagerSlidingTabStrip][pagerstrip]
* [KenBurnsView][kenburnsview]
* [NineOldAndroids][nineoldsandroid] 

This is blog post by flavienlaurent explaining how to implement the edition screen of Newsstand app.
- ActionBar effect
- Ken Burns animation

[http://flavienlaurent.com/blog/2013/11/20/making-your-action-bar-not-boring/][blogpost]

Example Image 
============

![Example Image][1]

Thanks to [kmshack][kmshack]  and [flavienlaurent][flavienlaurent] for the original [Android-ParallaxHeaderViewPager][parallaxHeader] and [NotBoringActionBar][NotBoringActionBar] demo app. 

[pagerstrip]: https://github.com/astuetz/PagerSlidingTabStrip
[kenburnsview]: https://github.com/flavioarfaria/KenBurnsView
[nineoldsandroid]: https://github.com/JakeWharton/NineOldAndroids 
[flavienlaurent]: https://github.com/flavienlaurent/
[kmshack]: https://github.com/kmshack/
[parallaxHeader]: https://github.com/kmshack/Android-ParallaxHeaderViewPager
[NotBoringActionBar]: https://github.com/flavienlaurent/NotBoringActionBar
[1]: https://raw.github.com/flavienlaurent/NotBoringActionBar/master/graphics/notboringab.gif
[blogpost]: http://flavienlaurent.com/blog/2013/11/20/making-your-action-bar-not-boring/