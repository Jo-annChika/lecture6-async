Why do we use async/await?

async/await lets us write asynchronous code that looks and reads like normal step-by-step code, making it easier to understand and debug compared to chaining .then() calls.

Why do we use try/catch with fetch?

Because fetch can fail due to network issues or server errors, try/catch lets us handle those failures gracefully instead of the app crashing or silently doing nothing.

Why do we check response.ok?

Because fetch does not automatically throw an error on HTTP error codes like 404 or 500 — it only rejects on network failure. Checking response.ok lets us manually catch and handle bad HTTP responses.
