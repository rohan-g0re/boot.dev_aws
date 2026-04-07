**Idempotency: A request method is considered idempotent if the intended effect of the server of multiple identical requests with that method is the same as the effect for a single such request.**
    - Idempotent HTTP methods: GET, PUT, DELETE --> multiple requests of this type will only change the state of server once (at first request)
    - **NON-Idempotent** HTTP methods: POST, PATCH --> these type of multiple requests will change the server state more than once, eg: POST will make multiple users of the same credentials
