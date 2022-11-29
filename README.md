These charts get updated by github worflow.
Set Env : export GIT_TOKEN=<GIT_TOKEN>

Add Repo : helm repo add --username ${GIT_TOKEN} --password ${GIT_TOKEN} fin3-helm 'https://raw.githubusercontent.com/Fin3-Technologies-Inc/fin3-helm/gh-pages/'

List repos: helm repo list
