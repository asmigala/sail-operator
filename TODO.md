- find solution how to apply openshift profile by default
  -- it is stored as IstioOperator resource... we would need to convert to pure helm values
- script to generate a type-safe Helm Values struct (or use upstream's - but codegen is based on protobuf there)
- script to generate Watches for all resource types in the helm charts
- mutatingwebhook for setting defaults
- validatingwebhook