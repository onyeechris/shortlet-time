# time-api-project
#download and install terraform terraform
terraform init
terraform plan
terraform apply --auto-approve



#download gcp cloudsdk
gcloud auth login
gcloud config set project <YOUR_PROJECT_ID>
gcloud iam service-accounts keys create key.json --iam-account <SERVICE_ACCOUNT_EMAIL>
#copy the json key and updtate your github
