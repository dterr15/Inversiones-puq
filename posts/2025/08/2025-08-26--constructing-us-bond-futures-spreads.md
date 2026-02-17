---
title: "Constructing US Bond Futures Spreads"
date: 2025-08-26
url: https://www.capitalflowsresearch.com/p/constructing-us-bond-futures-spreads
---

In the recent alpha report, I explained my view on the yield curve and HOW it links with the macro regime. I wanted to take a moment to explain why understanding these trades is important and how to structure them.

[

![](https://substackcdn.com/image/fetch/$s_!La5v!,w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F0e8b7fd5-d1ce-48e3-a96f-f578a9342589_771x581.png)

](https://substackcdn.com/image/fetch/$s_!La5v!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F0e8b7fd5-d1ce-48e3-a96f-f578a9342589_771x581.png)

[

![The Fed’s Policy Turn: New Outlooks for Rates, Equities, and Bitcoin](https://substackcdn.com/image/fetch/$s_!Yve-!,w_140,h_140,c_fill,f_auto,q_auto:good,fl_progressive:steep,g_auto/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F145c940b-754e-4b00-86c1-60a40e0e668c_1024x1536.png)

](https://www.capitalflowsresearch.com/p/the-feds-policy-turn-new-outlooks)

When managing risk, I'm always looking for ways to express a market view without taking on excessive amounts. That’s where bond futures spreads come in. A futures spread isn't about betting on whether bond prices will go up or down. Instead, it's a bet on the **relationship** between two different futures contracts. By simultaneously buying one contract and selling another, I'm isolating my risk to the relative performance of the two, effectively hedging away the general market movement. It’s an important strategy, especially in the US Treasury market, and understanding how to build a spread is key.

I would recommend signing up for the CME website and using the link below:

[https://www.cmegroup.com/tools-information/quikstrike/treasury-analytics.html](https://www.cmegroup.com/tools-information/quikstrike/treasury-analytics.html)

Once you are able to access the tool, see the following key sections:

*   #1 will show the DV01 - with toggles for contract #3 and will present the dollar value per basis point (DV01) #4.
    
*   #2 will show you the spread ratios for DV01 neutral (see the section below).
    

[

![](https://substackcdn.com/image/fetch/$s_!hnB-!,w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F02266d50-938c-4457-a3e6-14d4740a69d0_1086x447.png)

](https://substackcdn.com/image/fetch/$s_!hnB-!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F02266d50-938c-4457-a3e6-14d4740a69d0_1086x447.png)

[

![](https://substackcdn.com/image/fetch/$s_!2KVG!,w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F24a06a64-2798-4a4e-9bb5-86dcbb0ccb2c_504x611.png)

](https://substackcdn.com/image/fetch/$s_!2KVG!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F24a06a64-2798-4a4e-9bb5-86dcbb0ccb2c_504x611.png)

Every spread has two sides, or “legs.” There’s the **front leg** and the **back leg**. These are simply the two different futures contracts I’m trading. For example, in a **TUT** spread, my front leg is the 2-Year Treasury future, and my back leg is the 10-Year Treasury future. The whole trade is a way for me to bet on whether the spread between the 2-year and 10-year yields will widen or narrow (steepen or flatten).

**To make the spread work properly, I can’t just buy one of each contract.** I need to balance them. That's where the **price ratio** and **leg ratio** come in. These ratios are my guide to creating a position that's **duration-neutral**. In other words, I'm trying to match the interest rate sensitivity of my long position to that of my short position. This ensures that if all bond yields move up or down in a parallel shift, my profit and loss will be close to zero. Any P&L I get comes from the two legs moving apart or together. The ratios in a spread table are typically based on the **DV01** (Dollar Value of a 01), which is a measure of how a bond's price changes for a one-basis-point change in its yield. The quantities listed in the table are just a simple way of expressing these complex ratios using whole numbers.

Let me walk you through how I'd construct a few of these spreads using the kind of table I keep on my trading screen.

**Example 1: The TUT Spread (2 Yr vs 10 Yr)**

The **TUT** spread is when I have a view on the steepness of the yield curve from the 2yr vs the 10yr. The quantities are as follows:

*   **Front Leg:** 2 Yr Treasury
    
*   **Back Leg:** 10 Yr Treasury
    
*   **Front Quantity:** 2
    
*   **Back Quantity:** 1
    

This tells me exactly what to do. To construct this specific spread, I would **buy two contracts of the 2-Year future (lower 2yr yield) and sell one contract of the 10-Year future (higher 10yr yield)**. This 2:1 ratio is what gives me the balanced position I’m looking for (dv01 neutral). When I place this trade, I’m betting on the 2s/10s curve steepening. If the spread between their yields widens (increases), my spread position will gain value.

**Example 2: The NOB Spread (10 Yr vs T-Bond)**

For a view on the long end of the curve, I trade the **NOB** spread. This one pits the standard 10-Year Treasury future against the T-Bond, which represents the longest-duration bonds. My table shows these quantities:

*   **Front Leg:** 10 Yr Treasury
    
*   **Back Leg:** T-Bond
    
*   **Front Quantity:** 2
    
*   **Back Quantity:** 1
    

In this case, I know I need to **buy two contracts of the 10-Year futures (lower 10yr yield) and sell one contract of the T-Bond futures (higher 30yr yield)**. The 2:1 ratio, which is the whole-number representation of the 2.00 leg ratio, is what balances this spread and makes it a pure bet on the relationship between these two specific contracts, rather than on the direction of the market as a whole.

The specific quantities for the 2:1 for TUT, the 2:1 for NOB are critical. They are the entire point of the spread. They remove the "outright" risk.

If I were simply long the 10-Year futures and the market sold off, I'd lose money. But if I'm long the NOB spread (long 2x 10 Yr, short 1x T-Bond), a general market sell-off would likely cause both contracts to lose value. My P&L would then come only from the relative performance from the 10-Year and the T-Bond futures moving in a way that doesn’t mirror each other exactly. This is what makes a spread a targeted and powerful tool.

When I place a spread trade, I don't just put in two separate orders and hope they both fill at a good price. Most modern futures platforms have a dedicated “spread” order type. This is crucial because it ensures both legs of my spread are executed simultaneously, eliminating the risk of one side getting filled while the other doesn't.

Of course, spread trading isn't without its risks. The most significant one is **basis risk**. This is the risk that my spread doesn't move as I expect because of factors unique to the underlying bonds, such as a change in the "cheapest-to-deliver" bond. It’s also important to be aware of liquidity. While the major Treasury futures are very liquid, some of the less common spreads might have wider bid-ask spreads, making it more challenging to get in and out of the trade at a fair price.

Ultimately, I find that constructing a US Treasury futures spread is a sophisticated but incredibly effective strategy. By using a simple table that provides the front and back legs and their precise quantities, I can build a balanced position that lets me target a specific relationship in the yield curve.

As always, a Pepe for the culture:

[

![](https://substackcdn.com/image/fetch/$s_!YE74!,w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fafefc02a-3c45-44e2-acb1-231f493b457b_1536x1024.png)

](https://substackcdn.com/image/fetch/$s_!YE74!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fafefc02a-3c45-44e2-acb1-231f493b457b_1536x1024.png)

_**The information on this website/Substack is for information purposes only. It is believed to be reliable, but Capital Flows does not warrant its completeness or accuracy. The information on the website/Substack is not intended as an offer or solicitation for the purchase of stock or any financial instrument. The information and materials contained in these pages and the terms, conditions and descriptions that appear, are subject to change without notice. Unauthorized use of Capital Flows websites and systems including but not limited to data scraping, unauthorized entry into Capital Flows systems, misuse of passwords, or misuse of any information posted on a site is strictly prohibited. Your eligibility for particular services is subject to final determination by Capital Flows and/or its affiliates. Investment services are not bank deposits or insured by the FDIC or other entity and are subject to investment risks, including possible loss of principal amount invested. Your use of any information which is proprietary to Capital Flows or a third-party information provider shall only be used on individual devices without any right to redistribute, upload, export, copy, or otherwise transfer the information to any centralized interdepartmental or shared device, directory, database or other repository nor to otherwise make it available to any other entity/person/third party, without the prior written consent of Capital Flows.**_