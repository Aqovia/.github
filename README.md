# .github

## Notes on current state of this repo
This was introduced during the development of github workflows/CI pipelines for Aqovia.DurableFunctions.Testing. It was thought at the time that this `special` repo (github terminology) could maintain a workflow template for future pipeline build and inded can do so. However the development of this approach was halted due to time constraints and the limitation that github template workflows have no corresponding acion templates. Having no action template means every modular step in the workflow must be a github action and requires it's own repository (as per the current documentation). It was considered overly elaborate to meet the needs of the pipeline under development. 

The skeleton pipeline code that was intended to be published to this repo can be found in Aqovia/nuget-repo-template which maintains a workflow and a set of local actions. This code at a future date could be ported to use a workflow template in this repo using repositorised github actions. 
