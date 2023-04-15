# Troubleshooting for google auth
## corrected database urls 
This seemed to fix the google auth issue as it logs me in and stays logged in


# DIRECT_DATABASE_URL
## Database = pooler + ?pgbouncer=true

DIRECT_DATABASE_URL=postgres://axemanks:0tGf6RZzwkbx@ep-morning-hill-696478.us-east-2.aws.neon.tech/neondb

# Current issue - image not return from replicate
404 and 504 errors
Uncaught (in promise) SyntaxError: Unexpected token 'A', "An error o"... is not valid JSON

https://vercel.com/blog/gpt-3-app-next-js-vercel-edge-functions#edge-functions-vs.-serverless-functions