# Firefox 65+ userChrome.css
Firefox 65+ userChrome.css for dark theme, with tabs on bottom, and increased contrast between selected and inactive tabs

## Resources and tools:

+ [chrome://browser/content/browser.xul](chrome://browser/content/browser.xul) opens a tab with Firefox UI, so that we can find CSS selectors with Inspector
+ [Aris-t2/CustomCSSforFx](https://github.com/Aris-t2/CustomCSSforFx): Best resource that I know of, for custom styling FF
+ [userChrome.org - Style Recipes](https://www.userchrome.org/find-user-style-recipes.html): A collection of various customisations to userChrome.css

## `chrome` directory:

[about:profiles](about:profiles) and scroll to the bottom to find currently used profile, if more than one user profiles. Open "**Root Directory**", create a new dir named `chrome`, if one does not already exist, and create (or edit the existing) `userChrome.css`
