# Getting Started

This is a starter template for [Learn Next.js](https://nextjs.org/learn).

## Next boilerplate

`npx create-next-app nextjs-blog --use-npm --example "https://github.com/vercel/next-learn-starter/tree/master/data-fetching-starter"`


## Taking it further

[Conditional Styling](https://nextjs.org/learn/basics/assets-metadata-css/styling-tips)

## You can fetch data from the server side

This is possible because getStaticProps runs only on the server-side. It will never run on the client-side. It won’t even be included in the JS bundle for the browser. That means you can write code such as direct database queries without them being sent to browsers.


```
export async function getServerSideProps(context) {
  return {
    props: {
      // props for your component
    }
  }
}
```

## Preview mode

https://nextjs.org/docs/advanced-features/preview-mode