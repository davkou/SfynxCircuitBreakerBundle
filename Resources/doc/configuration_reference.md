# Configuration Reference

All available configuration options are listed below with their default values.

```yaml
#
# SfynxCircuitBreakerBundle configuration
#       
sfynx_circuit_breaker:
    cache_dir: "/tmp/"  # must finish with "/"
    service_names:
        currency:
            max_failure: 5
            reset_time: 50
        actor:
            max_failure: 10
            reset_time: 30
        film:
            max_failure: 10
            reset_time: 30
```
