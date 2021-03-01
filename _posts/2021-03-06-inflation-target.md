---
title:  ""  
tags: []
published: false
---

## Takeaway

<style>
      .iframe-container {
        overflow: hidden;        
        padding-top: 50%; <!-- Calculated from the aspect ration of the content (in case of 16:9 it is 9/16= 0.5625) -->
        position: relative;
      }
      .iframe-container iframe { 
         border: 0;
         height: 100%; <!-- Finally, width and height are set to 100% so the iframe takes up 100% of the containers space. -->
         left: 0;
         position: absolute;
         top: 0;
         width: 100%;
         display: block;
         margin: 0 auto; <!-- center image -->
      }
      <!-- 4x3 Aspect Ratio -->
      .iframe-container-4x3 {
        padding-top: 75%;
      }
</style> 

<div class="iframe-container-4x3">
  <p align="center"><iframe src="https://avoidboringpeople.substack.com/embed" frameborder="0" scrolling="no"> </iframe></p>
</div>

## What I don't understand about inflation

I don't understand inflation.

I get the concept of prices rising, sure. But for the longest time I haven't understood what *causes* inflation, how to *measure* inflation, and how to *adjust* inflation.

**I also have a feeling nobody really knows either.** 

That's ridiculous, you might say, there's a whole group of people out there [making policy on inflation targets](https://www.federalreserve.gov/faqs/economy_14400.htm "fed") and talking about hedging against inverted yield curves and if google trends is to be believed, some sonic the hedgehog game [(apparently some weird nsfw meme).](https://tvtropes.org/pmwiki/pmwiki.php/VideoGame/SonicInflationAdventure "sonic")

![post]({{ site.url }}{{ site.baseurl }}/assets/images/inflation_target/inf 1.png)

Yeah, but that doesn't mean they know the causes for what they're working on. If my work experience has taught me anything, it's that people can do huge amounts of work without understanding what they're doing \[1\]. Nassim Taleb wrote about this before, in a story of a finance trader becoming successful trading green lumber [without understanding what it was.](https://fs.blog/2016/11/green-lumber-fallacy/ "taleb")

A big problem with inflation is firstly deciding what counts towards it. **This is not a trivial task,** and if you think it is, ask yourself these questions:

- What broad categories of "things" do you want to include? Only physical goods? What about services? 
- Whatever thing you include, how are you going to measure its price? 
- How do you account for outlier data points, such as when toilet paper pricing spikes?
- How often do you take measurements?
- How do I account for quality improvements in those goods? If quality goes up and price stays same, is that deflation?

As you can see, it's not just "take the Consumer Price Index" and be done with it. In fact, the US Fed doesn't officially use the CPI, opting for another Personal Consumption Expenditures (PCE) price index instead \[2\]. And even then, [they acknowledge its imperfect nature:](https://www.federalreserve.gov/econres/notes/feds-notes/comparing-two-measures-of-core-inflation-20190802.htm "fed")

> However, total PCE price inflation is highly volatile, even on a year-to-year basis. Consequently, economists and policymakers have suggested alternative procedures for reweighting the index's components so as to reduce the variance of the measured inflation, to better distinguish transitory from persistent movements, and, ultimately to better anticipate future developments in inflation. The literature has used the generic term "core" inflation to refer to these alternative measures.

And as we recently discussed about [monopolies](https://avoidboringpeople.substack.com/p/monopoly-i-know-it-when-i-see-it "monopoly"), definitions are important. What counts as inflation affects public policy, hence small exclusions in an index can result in 
 
Another big problem with inflation is that it's influenced by expectations. Hoping for it to follow some mathematical law is like expecting the stock market to perfectly represent the present value of future cash flows. Which is why it's so hard to aim for an inflation target:

![post]({{ site.url }}{{ site.baseurl }}/assets/images/inflation_target/inf 1.png)

The US Fed has a 2% goal, so the first sentence above can either be interpreted as 1) the Fed is horrible at its job or 2) it's genuinely a difficult thing to do. I'm inclined to believe the latter.

There's always a whole game of [interpreting Fed statements](https://www.stlouisfed.org/open-vault/2019/may/how-read-fomc-statement "Fed") on monetary policy (interest rates) whenever they're released. What exactly do they mean in their press release, and why can't they just say it as it is?

Part of the reason the Fed can't speak simply and candidly is to [avoid being gamed.](https://www.reuters.com/article/us-usa-fed-powell/powell-says-may-take-more-than-three-years-to-hit-feds-inflation-goal-idUSKBN2AO254?il=0 "game") Another part of the reason is to also leave them flexibility, since there's so much that is not understood. **The ambiguity gives them buffer room for the unknown unknowns.** And then you can pretend that was the plan all along, building more confidence, continuing to be able to control expectations.

Measure with ruler.

I feel like these are the only things I'm comfortable saying about inflation:

1. Prices generally go up by small amounts over time, and when compounded the nominal values become large over long time periods
2. Prices can go up by large amounts in small periods of time, but what causes this is hard to say
3. It's hard to target a small increase in prices and easier to target a large increase. Nobody wants large increases
4. A lot of price changes are expectations driven, so maybe it's inherently unpredictable 
 
I'm not alone in thinking this, by the way. [Economist John Cochrane wrote about inflation recently](https://johnhcochrane.blogspot.com/2021/02/inflation-issues.html "john") \[3\], and also wonders how much we really know. He concludes by thinking that services could become a larger component of inflation over time, continuing trends of services inflation and goods deflation.

Maybe inflation's like the tide - [tide goes in, tide goes out, you can't explain that.](https://www.newser.com/story/109164/bill-oreilly-to-atheists-you-cant-explain-the-tides.html "tide")

## Footnotes

1. Myself included, having done so multiple times.
2. ["While the CPI and PCE price index both provide measures of how prices are changing over time, they are not constructed in the same way. One difference is the smaller number of items in the basket of the CPI. The CPI reflects out-of-pocket expenditures of all urban households, while the PCE price index also includes goods and services purchased on behalf of households. Another difference is the expenditure weights assigned to each of the CPI and PCE categories of items"](https://www.clevelandfed.org/en/our-research/center-for-inflation-research/consumer-price-data.aspx "fed")
3. His article was the inspiration behind getting my thoughts down on this topic.

*If you liked this, sign up for my [finance and tech newsletter:](https://avoidboringpeople.substack.com/ "ABP")*

<div class="iframe-container-4x3">
  <p align="center"><iframe src="https://avoidboringpeople.substack.com/embed" frameborder="0" scrolling="no"> </iframe></p>
</div>