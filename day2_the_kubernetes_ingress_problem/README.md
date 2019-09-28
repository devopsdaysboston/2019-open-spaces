# The Kubernetes Ingress Problem(s)

- Devs don't manage ingress for themselves
- Istio - fact as fiction?
- API Gateway versus ingress vs mesh...unwanted complexity
  - Is there a common subset?
- Straightforward rollout / deployment management
  - (Maybe according to users, etc.)
  - mTLS
    - Who supports it? Where?
  - Ingress versus mesh?
  - "You can just trust us! We encrypt things!"
- Non-HTTP support
- (Maybe as a service rather than manually configured)
- Multiple LBs vs API Gateway
- Ideal mesh deployment is invisible...
- How can we keep E-W traffic internal to the cluster? (Delease (?) in depth)
- Service discovery
- TLS termination and LBs (it's nice to hand off termination)
- Distributed tracing
