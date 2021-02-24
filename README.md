# tslavaluation.com

### ideas

_People_ can upload _documents_ and put _tags_ on them. Documents can contain _elements_ which can also have _tags_ on them

_document_ example could be "Warren's TSLA DCF model part 1"

_element_ could be "Q1 2021 deliveries prediction" or "Q1 Model S deliveries prediction" or "Q1 Model S USA deliveries prediction. _elements_ can have child _elements_, recursively.

_element_
 - id: string
 - type: DATA | PREDICTION
 - name: string
 - author
 - value: any, but probably number
 - formula: (computed dynamically from other elements)
 - smart_rating: some metric that looks at the depth of depencies of the elements of these ratings, how well users have rated each of those elements (and have those ratings be weighted by some sort of prediction/rigor score of each rater)
 - version: hash number similar to git - but rather than complicated hex names has some more intuitive branching name
 _ _tags_


why do this? Why not just link to everyone's spreadsheets? well this way you can see easily all of the people's Q1 Model S USA deliveries predictions, perform queries, and get more granular on what the assumptios are, how much variance in a value of an assumption leads to variance in the stock price. (Of the top of my head, the highest variance assumptios right now are those around fsd and TSLA's long term manufacturing edge. As a community we could rank order the assumptions by most variance-causing, and then conduct community research appropriately, including what questios to ask on the earnings calls.

first elements:
-current valuation (stock price & link to source)
- q1 - q4 delivery estimates

get the community to not just emphasize expected value, but to emphasize distribution as well


crowd source all the possible inputs for all the models and possible distributions for those inputs, and then anyone can essentially create their own formulae based off those inputs, and then the server will run monte carlos for all those inputs


somehow have monte carlos for specific situations - e.g. investing on margin w/ X capital at x price w/ y margin call rules, and then a certain distribution of stock prices occur which trigger margin calls at certain times.

people can create models that use future inputs . e.g. you can make a model that would incorporate certain line items from q1 2021 report before the report is released, and then th eapp automatically scrapes the report or has trusted users input numbers from the report, and your formulae would receive those new numbers and send you a text message saying "your model has calculated that TSLA is now worth $900"

----
### biz model
- free. Unlike TipRanks
- plus focuses on long term. unlike tip ransk
- highest quality info on the web for tsla existence. all free. uses repuation mechanisms to make most thorough and accurate and easy to understand info to rise to the top.
- reason it needs to be free is so that you can get a lot of participants on the network, and a lot of people sharing, so that we can aggregate and discuss as much info as possible.
- i really don't want to monetize it by making some parts of it paywalled, because then we could lose the information advantage to some well researched hedge fund or something. The more open the access, the more accurate of a price we can come to.
- moreover, as soon as I monetize it, I feel like it no longer becomes special. No longer would be something everyone link to.
- so I guess I'd just monetize it by selling merch, and affiliate links to brokerages like Steven does
- or just use it as a resume item / personal networking tool. a way to build a following for myself on the internet.


### vision
- frankly, I think as a community, we could and should come up with a more accurate model than ARK, Rob, or any one actor. Rise of the open-source retail investors.
- The assumption in this vision, is that the retail TSLA community has somehow been more accurate than the market as a whole (assumedly because a large portion of the market (e.g. Wall Street analysts) miscalculating/misunderstanding the non-linear nature of tsla's growth
- Creating the "Third Normal Form" of crowdsourced investing models, referencing database schema terminology.
- If successful, using similar community framework to help allocate capital in other stocks, or important humanity projects (e.g. fighting climate change).
