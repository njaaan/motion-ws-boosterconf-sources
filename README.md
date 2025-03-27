# Resources & Contact
 
## Workshop description
[njan & Lina's Inclusive Motion Design workshop @booster conf 28 March 2025](https://www.boosterconf.no/2025/program/friday/1_short_talks_and_workshops/dreggen_4/let-s-build-web-experiences-that-don-t-make-people-puke/)  
[Archive.org-Link](https://web.archive.org/web/20250217111130/https://www.boosterconf.no/2025/program/friday/1_short_talks_and_workshops/dreggen_4/let-s-build-web-experiences-that-don-t-make-people-puke/)


## External resources

### Overview articles
- [Val Head from Axe Con 2021: “Making Motion Inclusive”](https://www.youtube.com/watch?v=q-pUnKCUlJA)  
[→ The bit about smart toggles starts at 38min 21s](https://youtu.be/q-pUnKCUlJA?t=2301)

- [Val Head, “Designing Safer Web Animation For Motion Sensitivity” (Sep 8, 2015)](http://alistapart.com/article/designing-safer-web-animation-for-motion-sensitivity/)  
[Archive.org-Link](https://web.archive.org/web/20250210181452/http://alistapart.com/article/designing-safer-web-animation-for-motion-sensitivity/)

### Experiences from affected people

- [Affected people share their experiences (5-7 minutes podcasts)](https://a11yrules.com/?=animations) ⚠️ Link was down on 2025.02.17.

- [Eileen Webb on migraine: “Your Interactive Makes Me Sick. Why your coolest scrolly features can cause problems, and what to do about it” (Mar 1, 2018)](https://source.opennews.org/articles/motion-sick/)  
[Archive.org-Link](https://web.archive.org/web/20250202155300/https://source.opennews.org/articles/motion-sick/)

- [Facundo Corradini on vertigo: “Accessibility for Vestibular Disorders: How My Temporary Disability Changed My Perspective” (Apr 4, 2019)](https://alistapart.com/article/accessibility-for-vestibular/)  
[Archive.org-Link](https://web.archive.org/web/20250203052657/https://alistapart.com/article/accessibility-for-vestibular/)

- [Stephanie Cree: “Accessible motion: why it’s essential and how to do it right” (Feb 22, 2021)](https://medium.com/design-ibm/accessible-motion-why-its-essential-and-how-to-do-it-right-ff38afcbc7a9)  
[Archive.org-Link - unfortunately only available as images](https://web.archive.org/web/20250217114440/http://web.archive.org/screenshot/https://medium.com/design-ibm/accessible-motion-why-its-essential-and-how-to-do-it-right-ff38afcbc7a9)

- [Michelle Barker: “Respecting Users’ Motion Preferences” (Oct 21, 2021)](https://www.smashingmagazine.com/2021/10/respecting-users-motion-preferences/)  
[Archive.org-Link](https://web.archive.org/web/20250217120829/https://www.smashingmagazine.com/2021/10/respecting-users-motion-preferences/)

- [Hsin-Fang Wang: “From Breakdancer to Accessibility Champion: A design-for-Motion-Sensitivity Story” (Nov 9, 2022)](https://www.intuit.com/blog/innovation/from-breakdancer-to-accessibility-champion-a-design-for-motion-sensitivity-story/)  
[Archive.org-Link](https://web.archive.org/web/20250217132155/https://www.intuit.com/blog/social-responsibility/from-breakdancer-to-accessibility-champion-a-design-for-motion-sensitivity-story/)

### Quotes from slides came from those great AXE-Con-Talks
- [Foster, Seneca; Sharma, Ajay: “The Usability Gap: Why Accessibility does not always mean usable” (2025)](https://www.youtube.com/watch?v=XSPxwOqQGZ4)

- [Sumner, Melanie: “But why??!” (2025)](https://www.youtube.com/watch?v=PooU_zo3sqE) 

### Text with EEA (European Accessibility Act) relevance:

- [“Directive (EU) 2019/882 of the European Parliament and of the Council of 17 April 2019 on the accessibility requirements for products and services” (Dec 14, 2022)](https://eur-lex.europa.eu/eli/dir/2019/882)

- [European Commission: “European Accessibility Act: Q&A” (Dec 14, 2022)](https://ec.europa.eu/social/main.jsp?catId=1202&intPageId=5581&langId=en)

- [European Union of the Deaf: “Deadline for EAA transposition period missed by many EU Member States” (Sep 20, 2022)](https://www.eud.eu/deadline-for-eaa-transposition-period-missed-by-many-eu-member-states/)

### Relevant WCAG
- [2.2.2 Pause, Stop, Hide (A)](https://www.w3.org/WAI/WCAG21/Understanding/pause-stop-hide.html)
> “Moving, blinking, scrolling: For any moving, blinking or scrolling information that 
> (1) starts automatically, 
> (2) lasts more than five seconds, and 
> (3) is presented in parallel with other content, 
> there is a mechanism for the user to pause, stop, or hide it unless the movement, blinking, or scrolling is part of an activity where it is essential [...]".

Our opinion:  
→ Allow the users to pause/stop/hide every motion animation or blinking that lasts more than 5 seconds - unless it is essential. 
Exceptions are made for full-page loading animations.

- [2.3.3: Animation from Interactions (AAA)](https://www.w3.org/WAI/WCAG21/Understanding/animation-from-interactions)
>“Motion animation triggered by interaction can be disabled, unless the animation is essential to the functionality or the information being conveyed.”

Our opinion:  
→ Same as above but for animation triggered by interaction instead of page load. 
Either no unnecessary animations from interactions at all, 
or each animation that is not essential can be disabled, ideally globally.

---
Note about motion sickness and WCAG:  
Those guidelines define what we understand as passing some accessibility tests or not. Usually level A is understood as “the bare minimum”, AA as “this is what you need to fulfill to be WCAG compliant” and AAA as “the gold standard that is often more of an idea than 100% achievable”.
In this case, we strongly urge you to still make sure that your website/app passes the 2.3.3 requirement, even though it is labeled AAA. One reason is, that it doesn’t make sense for us, to have the user not be confronted with potentially triggering movement from site loading but then surprise them with parallax while scrolling or some animation after sending an email.
Also those guidelines get constantly refined, but it takes years for new insights to reach a final version of the guidelines. Vestibular disorders/motion sickness and their triggers in regards to web design are just starting to gain visibility. Better to make the website as user friendly as possible ahead of time.
Last but not least be aware that the five-second-rule in 2.2.2 has a length that was chosen rather arbitrarily. It’s still long enough to tick many peoples’ symptoms.

## Contact
Please get in touch if you have ideas/websites to share 
and use the hashtag for the same :)

Also drop us a line if you’d like to continue working on this topic.

### Contact us:
- Mail: lina.sievering@accenture.com
- Mastodon: [@njan@chaos.social](https://chaos.social/@njan)
 
### Hashtag: 
`#PukeLessWeb`



