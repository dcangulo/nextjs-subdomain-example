# Next.js Subdomain Example

## It uses the following as references:
* https://nextjs.org/docs/advanced-features/custom-server
* https://github.com/vercel/next.js/tree/canary/examples/custom-server-express
* https://stackoverflow.com/a/50052939/9375533

## If we are going to run this using `next dev` we will have the following routes:
* http://lvh.me:3000/admin
* http://lvh.me:3000/admin/sample-page
* http://lvh.me:3000/member
* http://lvh.me:3000/member/accounts/dashboard

## But by running `node server.js` we will have the following routes:
* http://admin.lvh.me:3000
* http://admin.lvh.me:3000/sample-page
* http://lvh.me:3000
* http://lvh.me:3000/accounts/dashboard

## Development Setup
* `git clone https://github.com/dcangulo/nextjs-subdomain-example.git`
* `cd nextjs-subdomain-example`
* `yarn`
* `yarn dev`
