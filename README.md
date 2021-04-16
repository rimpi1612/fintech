{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "4b9b4215",
   "metadata": {},
   "source": [
    "# PAYMENT WITH STRIPE\n"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "6775c485",
   "metadata": {},
   "source": [
    "![Stripe](https://stripe.com/img/v3/home/social.png)"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "254e75e8",
   "metadata": {},
   "source": [
    "## Overview and Origin"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "15420873",
   "metadata": {},
   "source": [
    "\n",
    "**Stripe is a payment processing software that is integrated mainly with e-commerce wesites and mobile application. It is an  Irish-American company which gives services both as financial and software. It has dual-headquartered in San Francisco, California and Dublin, Ireland.**\n",
    "\n",
    "---"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "679e57a6",
   "metadata": {},
   "source": [
    "John and Patrick Collision, the Collision brothers, began working on Stripe together. It was originally partnered with a payments company but later they kept the compnay as private to keep to control all aspects of the process.\n",
    "\n",
    "---"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "515f28b1",
   "metadata": {},
   "source": [
    "Stripe was founded in 2010 by John Collison & Patrick Collison. It was initially a private company but later was launched publicly in September 2011. \n",
    "\n",
    "Patrick Collison is the co-founder and CEO of Stripe with  his younger brother, John who also founded Shuppa which was merged with Auctomatic that built tools for the eBay platform. \n",
    "\n",
    "---"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "65e0c83f",
   "metadata": {},
   "source": [
    "John and Patrick first started working on Stripe in early 2010. As Derek Andersen stated in the article \"The Story Behind Payment Disruptor Stripe.com and it's founder Patrick ..\", the inspiration came when Patrick, who was working on a few side projects, found it very difficult to accept payments on the web. They tried to find a way to solve the problem and if it was possible to make the entire process simple - really simple. Both of them The two quickly developed a simple solution and within 2-weeks they had processed their first transaction.\n",
    "After 6-months, both John and Patrick started working on it full-time but they were starting to realize that as a payment startup they would need institutional credibility that an investor could provide. According to them they “didn’t look great on paper.” John became the President and Patrick the CEO.\n",
    "\n",
    "---\n"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "803795b2",
   "metadata": {},
   "source": [
    "Stripe received their first funding from Y Combinator. Patrick's earlier involevemet with Paul Graham through Lisp and Auctomatic, and he agreed to invest on Stripe. The amount YC invested was in the $20k-$30k range. In May 2011, Stripe raised $2 million investment from venture capitalists Peter Thiel and added other usual Silicon Valley persona like Michael Moritz and Sequoia Capital, Andreessen Horowitz, and SV Angel.\n",
    "![Valuation](https://lh3.googleusercontent.com/YviYnTSz78mok188eLb7ulsmPVg0Bo-IaUdxOgjT71_xATNRZbSJVxdt2bblGr7JP354BM9hhH5mZuVlFYX-fXZUoNeo7CBd5No6hW25mAx2LPy4H5eAjH4qY2idZaMlErXL06we)\n",
    "\n",
    "“Elon and Peter have been very insightful,” Patrick says. “They have sharp opinions on what PayPal did right and wrong. They have deep appreciation for how difficult it is to get there. They fought this battle for many years and it’s really helpful to have someone who can talk about the future in 15-years, but also someone who can empathize and sympathize with the day-to-day considerations. I don’t think there are that many people who can straddle both sides of that. “"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "351c0174",
   "metadata": {},
   "source": [
    "## Business Activities:"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "c5693575",
   "metadata": {},
   "source": [
    "---\n",
    "\n",
    "Stripe basically solved the cumbersome process of setting up a way to accept online payments. Before stripe, it was required working with an existing merchant services company or required multiple layers of approvals, dealing with banks, and setting up complex systems and integrations. Stripe is a simple API for accepting payments online. It focuses on making it easy to integrate and find the simplest way to accept payments.\n"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "43d14b31",
   "metadata": {},
   "source": [
    "---\n",
    "\n",
    "Stripe's major customers are ecommerce developers. They integrates stripe into their developed the ecommece sites that allows business owners to collect payments, including recurring payments. It transfers the money directly to the client's own account instantly. It also eliminats the need to store credit card information.\n",
    "\n",
    "PayPal was the main online payment platform, which allowed companies to receive payments, without having to build their own stack. But integrating with PayPal was complex and also PayPal works in a that required customers to leave the original business site and make the payment to the site of PayPal and again return back.\n",
    "\n",
    "Stripe solveed this problem. They also focussed on going after developers — the main group of people involved in integrating payments. To achieve that, they provided a super simple solution that allowed developers to receive payments with as few lines of code as possible.\n",
    "\n",
    "\"By adopting a simple and transparent pricing model, Stripe has managed to position itself as a “toll booth”, collecting a small commission fee from a large share of the internet economy. This pricing also puts in on track to continue growing in an era where the environment is going to be much more competitive than in the past.\" \n"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "17edd16c",
   "metadata": {},
   "source": [
    "---\n",
    "\n",
    "Stripe's core technology is machine learning. They use it to respond to their users' complex, real-world problems. Machine learning also powers Radar to block fraud, and Billing to retry failed charges on the network. Strip's machine learning infrastructure ensures the hundreds of millions of predictions across many machine learning models."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "b6435e10",
   "metadata": {},
   "source": [
    "## Landscape:"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "145f87cb",
   "metadata": {},
   "source": [
    "---\n",
    "\n",
    "Stripe mainly focuses on Online Payment Structure. It basically built the economic infrastructure for the internet. Businesses of every size, strating from new startups to public companies require some way to accept payments and manage their businesses online. Stripe focuses on that process."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "3f5d4e35",
   "metadata": {},
   "source": [
    "---\n",
    "\n",
    "![Evaluation](https://www.cashbook.com/wp-content/uploads/2020/06/Payment-Trends3-1024x575.png)"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "d4f48bf4",
   "metadata": {},
   "source": [
    "---\n",
    "\n",
    "The 10 Top Stripe Competitors  are as follows:\n",
    " - PayPal\n",
    " - Adyen\n",
    " - 2Checkout.\n",
    " - WePay.\n",
    " - Authorize.Net.\n",
    " - Braintree.\n",
    " - Payline Data."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "2b3534d9",
   "metadata": {},
   "source": [
    "## Results"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "185adb0b",
   "metadata": {},
   "source": [
    "---\n",
    "\n",
    "According to the online data, 117,416 companies are using Stripe. Stripe is most often used by companies with 10-50 employees and 1M-10M dollars in revenue. The data for Stripe usage goes back as far as 5 years and 4 months.\n",
    "\n",
    "As per IDC report on 2016, Business Value teh impact of Stripe after deploying are as followa: \n",
    "   - 6.7% higher revenue\n",
    "   - 59% higher developer productivity\n",
    "   - 24% lower cost of building/operat- ing online payments platform\n",
    "   - 81% fewer unplanned outages\n",
    "\n",
    "On average, the business organizations who are using Stripe achieved a revenue increase of almost 7% to the Stripe platform. In the report IDC also showed that Stripe customers would lower their processing costs of online transactions by 24% over five years by using Stripe. The also indicated that the organizations using Stripe would incur significantly lower costs compared with a broader set of surveyed organizations accepting payments for their online businesses. \n",
    "\n",
    "![impact](https://enlyft.com/tech/static/images/static_charts/stripe_industry.png)\n",
    "![impact2](https://enlyft.com/tech/static/images/static_charts/stripe_revenue_range.png)\n"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "8bdfc6a0",
   "metadata": {},
   "source": [
    "---\n",
    "\n",
    "Fast partner onboarding: A software marketplace explained: “Stripe has made it very easy for us to onboard our merchant partners. With Stripe Connect, it’s very seamless and frictionless and easy to get up and running.”\n",
    "\n",
    "Customer satisfaction and seamless easy operation is the key measur of sucess for Stripe. The study of IDC shows that Stripe customers are even more efficient compared with all surveyed organizations. This results in part from economies of scale due to Stripe customers’ larger transaction volumes, but it also reflects the core efficiencies Stripe offers in terms of building, maintaining, and running online payments platforms.\n",
    "Stripe's impacts on development teams are said to be 37% more efficient which also inicates it is 59% more productive in terms of the amount of work that the teams can handle. This reflects that that these organizations are improving and extending their development platforms without increasing the development team size.\n"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "21759074",
   "metadata": {},
   "source": [
    "---\n",
    "\n",
    "![Performance](https://enlyft.com/tech/static/images/static_charts/stripe.png)\n",
    "    Online Payment\n",
    "       - Stripe (11.13%)\n",
    "       - PayPal (66.17%)\n",
    "       - Apple Pay (6.87%)\n",
    "       - Google Pay (3.57%)"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "06dbdf86",
   "metadata": {},
   "source": [
    "## Recommendations"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "2d9131ea",
   "metadata": {},
   "source": [
    "---\n",
    "\n",
    "The financial future is having a cashless society. It is described as an economic state where financial transactions are not conducted with physical banknotes or coins,  but rather using credit and debit cards, mobile wallets, payment apps, internet banking, cashless point of sales (POS) systems, and other forms of digital payments. The evaluation has started already and it will be used more and more in payment technology like advance cryptocurrencies, AI and ML, blockchain, QR codes etc. \n",
    "\n",
    "![trend](https://www.cashbook.com/wp-content/uploads/2020/06/Payment-Trends11-1024x581.png)\n",
    "![trend2](https://www.cashbook.com/wp-content/uploads/2020/06/Payment-Trends12-1024x581.png)\n"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "47bc01e6",
   "metadata": {},
   "source": [
    "---\n",
    "\n",
    "Payment using blockchain technologies would reduced Business risks and costs – reduced cash in-store, less cash counting & trips to the bank, reduction in fraud and burglary, improve the transaction speed – greatly increased, better for busy outlets – that can process customers faster, and improved economic data – better collection due to increased card transaction data, and eliminate money laundering and tax evasion – reduction in this due to clear paper trail."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "75b3fc1e",
   "metadata": {},
   "source": [
    "---\n",
    "\n",
    "The next generation of cryptocurrencies and blockchain technology could be the evaluation the payment platforms can see in future. The advancement of AI and ML with blockchain can turn the finanacial world around. \n",
    "![future](https://www.wowso.me/hs-fs/hubfs/Ten_disruptive_technologies_that_will_shape_the_future_rev.png?width=817&name=Ten_disruptive_technologies_that_will_shape_the_future_rev.png)\n",
    "\n",
    "The structure of cryptocurrency has opened the way for financial blockchain technology developments. It allows for new ways of payments to be made without the need for intermediaries such as banks. Meaning, you don’t need a bank account and it is peer to peer. A financial blockchain is defined as “an open, distributed global ledger that can record transactions between two parties efficiently and in a verifiable and permanent way”.\n",
    "\n",
    "Blockchains are secure by design, and are an example of a distributed computing system with high fault tolerance. Decentralized consensus has been achieved with a blockchain. Blockchain technology has managed and distributed more than $270bn. The Blockchain market size is predicted to be worth $60bn by 2024. This will turn the future payment in fast pace position which Stipe can get a hold. "
   ]
  },
  {
   "cell_type": "markdown",
   "id": "e5e67902",
   "metadata": {},
   "source": [
    "Sources:\n",
    "https://stripe.com/files/payments/IDC_Business_Value_of_Stripe_Platform_Full%20Study.pdf\n",
    "https://stripe.com/about\n",
    "https://www.cnbc.com/2020/06/16/why-online-payments-start-up-stripe-is-the-no-1-disruptor-50-company.html\n",
    "https://www.cashbook.com/changes-in-payment-trends-over-the-last-10-years/\n",
    "https://enlyft.com/tech/products/stripe"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.8.5"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
