
# Feynman Pi

A dashboard application that would help the farmers connect to the market, with prices (current, average, all time lowest, all time highest) of different item/goods they produce.

## Working
- Buyers push their demand to the market : item they need, the weight, and the max price they can afford.
- The backend route handles the request, and calculates the new current, average, lowest, and highest prices accordingly.
- One backend route send the all the information, including the item, and its different prices.
- The frontend receives the response and display it to the famers.


## Snippets

![screenshot_01](https://i.postimg.cc/HkBzsjxt/93a622b9-601d-4a70-a7e8-6a4db056ee53.jpg)

![screenshot_02](https://i.postimg.cc/WzQXMyrb/Screenshot-20240325-162859.png)
## Features

- Live price updation
- Option (price per Quintal or Price per Kg)
- Live graph for Current market pricing of different items
- Form feature for merchants to order their demand


## Tech Stack
### Frontend
- Next js
- Shadcn
- Tailwindcss
- Axios (for API calls)
### Backend
- Node
- Express
- PostgreSql
- Prisma (ORM)
- (all written in TypeScript)


## Authors

- [@Sagar Tamang](https://www.github.com/SAGAR-TAMANG)
- [@Jyotishman Pathak](https://www.github.com/Jyoti1368)
- [@Amit Karmakar](https://github.com/amitkarmakar)
- [@Priyanku Gogoi](https://github.com/ppriyankuu)
