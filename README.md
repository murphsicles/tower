# @net/tower — Service/Middleware Abstraction for Zeta

Auto-converted from [tower](https://crates.io/crates/tower) v0.5.3 via [Dark Factory](https://github.com/murphsicles/dark-factory).

## Features
- **Service** trait — async function from Request to Result<Response, Error>
- **Layer** trait — middleware composition and stacking
- **Buffer** — per-service request buffering with bounded capacity
- **Retry** — automatic retry with configurable policy and backoff
- **Timeout** — per-request timeouts
- **RateLimit** — token-bucket rate limiting
- **Load** — capacity-aware load shedding
- **Discover** — dynamic service discovery for load balancing
- **filter** — request filtering and rejection
- **steer** — traffic steering across services
- **util** — ready, oneshot, optional, boxed service adapters

## Stats: ~5,000 lines, 0 unsupported items

## License
MIT