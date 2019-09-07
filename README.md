

this is a repo to show the gatekeeper functionality in Anthos Config Management 1.1.

to see the violations for the constraint:

`
kubectl get K8sRequiredLabels -ojson | jq .items[].status.violations
`
