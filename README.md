# istio_rating
1/clone the project
<br/>
2/install istio: 
<br/>
  istioctl install --set meshConfig.disablePolicyChecks=false --set values.pilot.policy.enabled=true
  <br/>
3/apply  the project yaml file with kubectl
<br/>
4/ send curl http://localhost multiple times, only 2 should have responseStatus 200... 
