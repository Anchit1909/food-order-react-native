<div style="display: flex; align-items: 'center'; justify-content: 'center';">
  <img alt="Groww Stonks - stocks/etfs broking website" src="/assets/images/1.jpg" width=40%>
</div>
  <h1 align="center">HotBox - Order Pizza Online</h1>

<p align="center">
  Order your favourite Pizzas online and get it delivered to your home.
</p>

<p align="center">
  <a href="https://twitter.com/anchit1909" target="_blank">
    <img src="https://img.shields.io/twitter/follow/anchit1909?style=flat&label=anchit1909&logo=twitter&color=0bf&logoColor=fff" alt="Anchit Sinha Twitter follower count" />
  </a>
  <a href="https://github.com/Anchit1909/hotbox-food-order-react-native" target="_blank">
    <img src="https://img.shields.io/github/stars/Anchit1909/hotbox-food-order-react-native?label=Anchit1909%2FHotBox" alt="HotBox repo star count" />
  </a>
</p>

<p align="center">
  <a href="#introduction"><strong>Introduction</strong></a> ·
  <a href="#features"><strong>Features</strong></a> ·
  <a href="#tech-stack"><strong>Tech Stack</strong></a> ·
  <a href="#screenshots"><strong>Screenshots</strong></a> ·
  <a href="#running-locally"><strong>Running Locally</strong></a> ·
  <a href="#author"><strong>Author</strong></a>
</p>
<br/>

## Introduction

HotBox is an application to order pizza online. It lets admins create and update new pizzas and lets users order their favourite pizza and check it's status as well. Realtime push notifications is integrated to update the users of the status of their order and alert admins when new orders are placed.

## Features

- Create account as an admin or user.
- Home Page with a list of pizzas.
- Product page to select the size of the pizza and proceed to checkout.
- Make payment using Stripe.
- Get status of your order.
- Create or update already listed pizza.
- Realtime push notifications to alert the users of the status of their order.
- Realtime push notifications to alert the admin when new orders are placed.

## Tech Stack

- [Typescript](https://www.typescriptlang.org/)
- [React Native](https://reactnative.dev/)
- [Expo](https://expo.dev/)
- [Expo Router](https://docs.expo.dev/router/introduction/)
- [Supabase](https://supabase.com/)
- [Tanstack React Query](https://tanstack.com/query/latest)
- [Stripe](https://stripe.com/)
- [Expo Notifications](https://docs.expo.dev/push-notifications/overview/)

## Screenshots

### User Screen

<div style="display: flex; flex-direction: 'row';">
<img src="/assets/images/1.jpg" width=20%>
<img src="/assets/images/2.jpg" width=20%>
<img src="/assets/images/3.jpg" width=20%>
<img src="/assets/images/4.jpg" width=20%>
<img src="/assets/images/5.jpg" width=20%>
</div>

### Admin Screen

<div style="display: flex; flex-direction: 'row';">
<img src="/assets/images/6.jpg" width=20%>
<img src="/assets/images/7.jpg" width=20%>
<img src="/assets/images/8.jpg" width=20%>
<img src="/assets/images/9.jpg" width=20%>
</div>

## Running Locally

### Cloning the repository to the local machine.

```bash
git clone
```

### Copy the .env.example file and rename it as .env

```bash
cp .env.example .env
```

### Get API Keys

1. Create a Supabase account to get SUPABASE URL and SUPABASE ANON key.
2. Create Stripe account to get API keys from stripe to process payments.

### Installing the dependencies.

```bash
npm install
```

### Running the application.

Then, run the application in the command line and it will be available at `http://localhost:3000`.

```bash
npm start
```

## Author

- Anchit Sinha ([@anchit1909](https://twitter.com/anchit1909))
