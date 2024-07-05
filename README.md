## CLSX

- Conditional CSS

## Postgress

- pnpm i @vercel/postgres

## Data Fetching

- Waterfall Model (Behves synchronusly)
- Parallel Fetching 

# Static Rendering

-- Only Used when same data is shared across the users 
- reduces server load
- fast-reloading as cached and globally distributed data (cahed data when build is made)
- SEO is easy

# Dynamic Rendering

-- Data is generated for every user when requested (when user visit the page)
- real time data
- user specific data 

## Streaming 

-- To solve slow fetching problem 
- Suspense (gives a fallback until specific condition matches means eg: data loads ). It can be used  on specific componenets.
- Loading
