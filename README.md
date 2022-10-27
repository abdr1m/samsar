# Semsar ( Samsar in Frensh )
**A peer-to-peer (P2P) Marketplace as decentralized platform whereby two individuals interact directly with each other, Dedicated in this stage for Mauritanians**

## Technologies

- NodeJs & NPM, NuxtJs, Vuetify, VueJs
- Laravel
- Flutter

## Web app

https://abdr1m.github.io/semsar-ui

[light_ui]: ./UI/light_mode.png "Light Sketch"
![][light_ui]

- i18n: Support Frensh, Arabic
- Search by Brand, Tags @todo
- Database Structure
- Statistics @todo
- AI Filters  @todo
- Smart Import Tool Miracle for Marketing 🐿️

## Night Sketch

[dark_ui]: ./UI/night_mode.png "Night Sketch"
![][dark_ui]

## Mobile APP
- @todo

### Other Features
- AI Filters  @todo
- Qr Generator for New Store's (Phones Shops in Nouakchott) should implemented inside Customers Resource => ready for Bulk Products @todo

## Admin Security
- Google Authenticator
> Each account has a unique Google Authenticator that can only be created by Super-Admin, since password alone is not secure enough for such IMPORTANT PROJECT

## Administration [ Create-Read-Update-Delete ]
- Products CRUD
- Categories CRUD
- Users CRUD
- Import Sellers Data from Voursa or Facebook
- Audit (Logs CRUD)

### Categories
> Specify the type of a product perhaps as "tags" too ?<br />
> Example: Electronics, Car, Real Estate, Property, Crypto...
> There can be many products inside one category

## Users [ aka Customers ]
> It's all about people :)
- User can propose a product/goods
- User can have a profile
- User can set a photo
- User can link a bankily account
- User can have a feedback [ on his wall / later badges ]

### Products
> It's all about goods, a product is a generally an item. it might belong to a user.
- Product can have one Category
- Product can have many Photos
- Product can have different Tags

## Purchases
> A instant/scheduled transactions.
- A guest who matches necessary payment method acquire the product
- A purchase might be optional [ direct chat with the seller @todo ]
> The aim is to motivate the customers by using AI filters [ to-do later awesome but not required at this stage maybe too advanced ?]
> the most visited product ranked hence mentioned at the home page @todo

### Tags
> Specify a unique tag for common products such as "iphone", "corolla"..

### Guests
> A guest is a hidden customer [ ability to be tracked during navigation @todo ]
- There can be many products inside home page @todo
- Each purshace has it log history [ are we gone offer shipping service for the clients ?]
- A purchase might be optional
> and there may be financial prizes as well

## Database Diagram
https://dbdiagram.io/d/635a944c6848d85eee8647c8

[logo]: ./Back-End/db_design.png "Database Diagram"
![][logo]

## Awesome Demos:

- https://haraj.com ( An Interested Seller Inserting UI )
- https://www.avito.ma/ ( Front-End / UI )
- https://www.leboncoin.fr/ ( Front-End / UI )

## Funding
- Management Budget 
> Office
> Electricity
> Designers
...

- Development Budget
> .mr TLD License (Top-level domain)
> Cloud Server

- Marketing Budget
> Facebook Ads
> Snapchat Infulencers
