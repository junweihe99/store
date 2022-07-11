This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## Store
<a href="https://store-phi-hazel.vercel.app/">This</a> is a full stack ECommerce application


<h4>Features</h4>
  <ul>
    <li> Customizable banner (Change change/update using Sanity)
    <li> Shopping-Cart feature
    <li> Individual product page
    <li> Rotating carousel display of recommended products
    <li> Toast notification after adding items to cart
    <li> Checkout with Stripe
  </ul>

<h4>Lessons Learned</h4>
  <ul>
    <li> Next.js framework: file-based routing (for server-side rendering and static websites); api folder serves as server
    <li> Sanity (backend) for creating schemas and adding new items to database: Connect frontend to Sanity with sanity client
    <li> Stripe (payment method)
    <li> Use getServerSideProps to fetch data from API, Next.js will pre-render the page on request using data returned
    <li> React: Pass component to inside of another component, parent has acess to child component using children prop
    <li> Next.js getStaticProps -> uses getStaticPaths to define a list of paths to be statically generated
    <li> React Context hook to store states; wrap entire app in StateContext component
    <li> Canvas confetti for confetti effect
    <li> Use Vercel to deploy app
    <li> Use Sanity <a href="https://ecommerce-jun.sanity.studio/desk">studio</a> to update database 
  </ul> 
  
<h4>Problems Encountered</h4>
  <ul>
    <li> Product images not showing up on Stripe checkout page -> Fixed typo on stripe.js
  </ul>

<h4>Improvements to Add</h4>
  <ul>
    <li> Fix cart items swapping order when changing quantities
  </ul>

<h4>Credits</h4>
  <ul>
    <li><a href="https://www.youtube.com/watch?v=4mOkFXyxfsU&t=456">YouTube</a>
  </ul>
