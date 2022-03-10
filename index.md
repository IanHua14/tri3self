## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/IanHua14/tri3self/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

# TPT Q&A
## TPT 5.1
1. Come up with three of your own Beneficial and corresponding Harmful Effects of Computing
- three beneficial are it helps increase productivity, Keeps you connected, and can help make money
- three negatives are it can cause an unhealthy habit, cause great amount of stress, and can cause an overall unhealthy lifestyle
2. Talk about dopamine issues above. Real? Parent conspiracy? Anything that is impacting your personal study and success in High School?
- The use of computing can be related to dopamine due to the addictions created by many factors, an example is gaming, but this is also not all true since computing has created many positives for others. For parents now a days, technology is mostly seen as a negative. Technology has not affected me personally in my lifestyle but for others it may have.

## TPT 5.2 
1. How does someone empower themself in a digital world?
- Someone is able to empower themselves by gaining fame on social media, start up a business online that has become worldwide like amazon, and even starting an organization to cause positivity in the world
2. How does someone that is empowered help someone that is not empowered? Describe something you could do at Del Norte HS.
- Something that can help someone that is not empowered is to become their friend
3. Is paper or red tape blocking digital empowerment? Are there such barriers at Del Norte? Elsewhere?
- Del norte doesnt have much digital divide but it does have red tape, when in the school the wifi doesnt allow people to access certain sites or apps. But for other places in the world that are most likely developing countries, have digital divide because they can't access technology or even people deciding not to use technology.

# menuy.py - function style menu
# Imports typically listed at top
# each import enables us to use logic that has been abstracted to other files and folders


# Main list of [Prompts, Actions]
# Two styles are supported to execute abstracted logic
# 1. file names will be run by exec(open("filename.py").read())
# 2. function references will be executed directly file.function()
main_menu = [
    ["Stringy", None],
    ["Listy", None],
    ["Loopy", None],
]

# Submenu list of [Prompt, Action]
# Works similarly to main_menu
sub_menu = [
    ["Factors", None],
    ["GCD", None],
    ["LCM", None],
    ["Primes", None],
]

patterns_sub_menu = [
    ["Patterns", None],
    ["PreFuncy", None],
    ["Funcy", None],
]

# Menu banner is typically defined by menu owner
border = "=" * 25
banner = f"\n{border}\nPlease Select An Option\n{border}"
