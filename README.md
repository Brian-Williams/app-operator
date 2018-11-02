# sdk example
operator-sdk new app-operator
Create cmd/manager/main.go
Create build/Dockerfile
Create deploy/service_account.yaml
Create deploy/role.yaml
Create deploy/role_binding.yaml
Create deploy/operator.yaml
Create pkg/apis/apis.go
Create pkg/controller/controller.go
Create version/version.go
Create .gitignore
Create Gopkg.toml
Run dep ensure ...
Run dep ensure done
Run git init ...
Initialized empty Git repository in /Users/brian/go/src/github.com/Brian-Williams/sdk-example/app-operator/.git/
Run git init done
Create pkg/apis/app/v1beta1/appservice_types.go
Create pkg/apis/addtoscheme_app_v1beta1.go
Create pkg/apis/app/v1beta1/register.go
Create pkg/apis/app/v1beta1/doc.go
Create deploy/crds/app_v1beta1_appservice_cr.yaml
Create deploy/crds/app_v1beta1_appservice_crd.yaml
Running code-generation for custom resource group versions: [app:v1beta1, ]
Generating deepcopy funcs

