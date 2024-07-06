## CLSX

- Conditional CSS

## Postgress

- pnpm i @vercel/postgres

## Data Fetching

- Waterfall Model (Behves synchronusly)
- Parallel Fetching 

# Static Rendering

- Only Used when same data is shared across the users 
- reduces server load
- fast-reloading as cached and globally distributed data (cahed data when build is made)
- SEO is easy

# Dynamic Rendering

- Data is generated for every user when requested (when user visit the page)
- real time data
- user specific data 

## Streaming 

- To solve slow fetching problem 
- Suspense (gives a fallback until specific condition matches means eg: data loads ). It can be used  on specific componenets.
- Loading


## Partial Perendering

- combine the effects of both partial and dynamic rendering
- fast loads the static data and create a hole for dynamic data which is requested. In other words dynamic content is postponed until the user requests the route.

## Debouncing 

- a program that limits the fire of function 
- Trigger Event (Timer Start)
- Wait (if new event comes timner again reset)
- Execute when timer completes countdown

-pnpm i use-debounce

## Mutation 

- mutate data along with revalidate cache and path ( means user can quickly navigate between the routes )

## Dynamic Route Segment 

- name in square brackets. For example, [id], [post] or [slug]
