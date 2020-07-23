# istio_rating
1/clone the project
2/install istio: 
  istioctl install --set meshConfig.disablePolicyChecks=false --set values.pilot.policy.enabled=true
3/apply  the project yaml file with kubectl
4/ send curl http://localhost multiple times, only 2 should have responseStatus 200... 
