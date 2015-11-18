i)What is the rule for underlining text that is not a link?
- Don't underline any text that's not a link, even if your links aren't underlined. Reserve underlining for links. Because underlines provide a strong perceived affordance of clickability, users will be confused and disappointed if underlined text doesn't have an actual affordance to match this perception.





ii) How should the unvisited link color compare to the visited link color in terms of:

a) Brightness
    - The color for unvisited links should be more vivid, bright, and saturated than the color for visited links, which should look "used" (dull and washed out).

b) Hue
    - The two colors should be variants or shades of the same color, so that they're clearly related. Using drastically different colors (say, orange and green) makes it hard for users to understand the relationship between the two types of links and to identify which color is the "used" version of the other.

c) Visibility to color-blind users
    - As always, when using color to signal information, you should provide redundant cues for color-blind users. Making unvisited links brighter and more luminous than visited links will usually accomplish this goal.

iii) What is a "perceived affordance"? Hint: Google is your friend. (OK, not really, but the search is nice.)
    - Affordances are what an object/product/site can do. Perceived affordances are what we think it can do, which may be correct or incorrect. The way to make sure the affordances are clear (that is, the perceived affordances match the real affordances) is to use signifiers, which are signs indicating what you can do.

    - Let's say an affordance of a door is that it opens inward. This is all it does. With no signifier - no doorknob or handle or anything - the perceived affordance is that it may open inward or outward. If you place a push bar on the door (a signifier), it should be clear that you push it to open it inward.

iv) When can you safely eliminate underlines for links?
  - There are two main cases in which you can safely eliminate underlines: navigation menus and other lists of links. However, this is true only when the page design clearly indicates the area's function. (Remember: your design might not be as obvious to outside users as it is to your own team members.) Users typically understand a left-hand navigation rail with a list of links on a colored background, assuming it resembles the navigation areas on most other sites.

v) Should you use blue for text? Why or why not?
  - Shades of blue provide the strongest signal for links, but other colors work almost as well.
      *****Exception ***** Don't use blue for non-link text, even if you don't use blue as your link color. Blue is still the color with the strongest perceived affordance of clickability.

vi) If for some shocking reason, your contextual links are not underlined (horrors!), what can you do to improve link discovery by users?

  - if you've opted to present links with less than the maximum perceived affordance for clickability, you can recover some of the lost usability by signaling clickability when the user hovers over the link. For example, if your links aren't underlined, you can make an underline appear while hovering.

  - One useful hovering effect is to use link titles to help users predict where a link will lead before they click it. (If you're using a mainstream browser, you can see this effect by hovering over the links in this column.)

vii) What are link titles and how might you use them?
  - a pop up to give the user a preview of where the link will lead and improve their navigation
  - The link explanation is called a link title and is very easy to encode. For example, the HTML code for making my name (immediately above the headline) into an anchor is <A HREF="/jakob/" TITLE="Author biography"> . If you rest your cursor on my name, the words "Author biography" will pop up after about a second if you have a browser that supports link titles (most don't).

  - Having the title "Author biography" pop up when the user is thinking about what might be linked from my name gives the user an indication of the type of information he or she can expected to get from following the link. Among other things, it makes it clear that the link is not a "mailto" link that will spawn an email message.