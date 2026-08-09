# Autonomous Driving Evaluation Metrics

Reference metrics for evaluating safety, operational coverage, performance,
reliability, user experience, and cost.

## Safety

- **Disengagement rate:** Human interventions per distance or operating hour.
- **Accident rate:** Collisions or safety-critical incidents per distance or hour.
- **Near-miss rate:** Events that narrowly avoid a collision.
- **Edge-case success rate:** Correct responses to rare or emergency scenarios.
- **Safety-critical alerts:** Emergency warnings issued to the driver.

## Operational Design Domain

- **Weather coverage:** Supported weather conditions and test distance.
- **Lighting coverage:** Day, night, dawn, dusk, tunnel, and transition coverage.
- **Visibility range:** Effective perception distance under degraded visibility.
- **Road coverage:** Highways, urban, suburban, rural, and private roads.
- **Topology robustness:** Performance at intersections, roundabouts, and work zones.
- **Traffic adaptability:** Performance across traffic densities and road-user types.
- **Behavioral edge cases:** Response to non-standard road-user behavior.

## Vehicle Constraints

- **Speed compliance:** Time within configured speed limits.
- **Load sensitivity:** Braking and acceleration changes under different loads.
- **Vehicle adaptation:** Performance across supported vehicle types.

## Computational Performance

- **Inference latency:** Average and maximum processing delay.
- **Throughput:** Sustained processing rate at target sensor frequencies.
- **Resource utilization:** CPU, GPU, memory, and network usage.
- **Power consumption:** Energy used by onboard compute.

## Reliability

- **Failure rate:** Frequency of software or hardware failures.
- **Recovery time:** Time to return to normal operation after a fault.
- **Sensor degradation handling:** Performance retention with degraded sensors.

## User Experience

- **Comfort:** Lateral and longitudinal acceleration variation.
- **Ride smoothness:** Composite score from motion signals and feedback.
- **Driver interaction frequency:** Manual overrides or driver alerts per distance.

## Efficiency and Cost

- **Operational efficiency:** Trip time, average speed, and route optimality.
- **Operational cost:** Energy use and maintenance cost per distance.
- **Total cost of ownership:** Hardware, software, maintenance, and operations.
