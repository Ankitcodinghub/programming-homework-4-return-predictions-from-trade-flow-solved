# programming-homework-4-return-predictions-from-trade-flow-solved
**TO GET THIS SOLUTION VISIT:** [Programming Homework 4-Return Predictions From Trade Flow Solved](https://www.ankitcodinghub.com/product/programming-homework-4-return-predictions-from-trade-flow-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97961&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Programming Homework 4-Return Predictions From Trade Flow Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

1 Introduction

Here you will assess trade flow as means of generating profit opportunities in 3 cryptotoken markets. We stress the word “opportunity” because at high data rates like these, and given the markets’ price-time priority, it is far easier to identify desirable trades in the data stream than it is to inject oneself profitably into the fray.

2 Data

We have preprocessed level 2 exchange messages from the Coinbase WebSocket API for you into a more digestible format.

2.1 Treatment

Load the 2021 data for all 3 pairs from the class website. For each one, split it into test and training sets, with your training set containing the first 20% of the data and the test set containing the remainder.

</div>
</div>
<div class="layoutArea">
<div class="column">
2.2 Format

The data has the following structure1 2.2.1 Trades

</div>
</div>
<div class="layoutArea">
<div class="column">
received utc nanoseconds

1618090137140737000 1618090137851379000 1618270615253262000 1618270616012160000

The Side is actually a

2.2.2 Book

</div>
<div class="column">
timestamp utc nanoseconds

1618090137157544000 1618090137864544000 1618270615358639000 1618270616105583000

sum of trade sides at the same

</div>
<div class="column">
PriceMillionths

35690 35700 35760 35760

price and time.

35690 11872084060 32957203990 35710 35680 30332423370 45284575470 1618090136378911000 1618090136388074000 35695

</div>
<div class="column">
SizeBillionths Side

1000000 -1 29801980 2 2926932560 -1 16673940 -1

35770

35760 1255039420 24752612680 35780 35750 31011776970 41785630850 1618270617727565000 1618270617836039000 35765

</div>
</div>
<div class="layoutArea">
<div class="column">
Ask1PriceMillionths

Bid1PriceMillionths

Ask1SizeBillionths

Bid1SizeBillionths

Ask2PriceMillionths

Bid2PriceMillionths

Ask2SizeBillionths

Bid2SizeBillionths

received utc nanoseconds

timestamp utc nanoseconds

Mid 35695

</div>
</div>
<div class="layoutArea">
<div class="column">
(transposed)

</div>
</div>
<div class="layoutArea">
<div class="column">
35700

35690 11872084060 32957203990 35710 35680 31032423370 45284575470 1618090136351018000 1618090135799659000

</div>
<div class="column">
35700

</div>
<div class="column">
35770

35760 1255039420 24752612680 35780 35750 31011776970 41785630850 1618270617738680100 1618270617846283000 35765

</div>
</div>
<div class="layoutArea">
<div class="column">
1Note that inaccuracies in clock settings, i.e. “clock skew”, can cause timestamps to appear later than the time at which they are recorded as having been received.

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
3 Exercise

Write code to find τ-interval trade flow F(τ) just prior2 to each trade data point3 i. Compute T-second i

forward returns4 r(T). Regress them against each other in your training set, to find a coefficient β of i

regression.

For each data point in your test set you already have F(τ), so your return prediction is rˆ := β · F(τ).

</div>
</div>
<div class="layoutArea">
<div class="column">
Define a threshold j for rˆ and assume you might attempt to trade whenever j &lt; |rˆ | . ii

4 Analysis

Assess the trading opportunities arising from using these return predictions in your test set. As part of this assessment, comment on the reliability of β, how you chose j, and what you might expect from using much longer training and test periods.

</div>
</div>
<div class="layoutArea">
<div class="column">
iii

</div>
</div>
</div>
