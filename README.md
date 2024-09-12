# HELM DEMO
This repository used to practice helm demo

# Create a release name as  app1-release and set source image for pod (Replace image name with your customized image)
#helm install app1-release ./app1 --set image.repository="devsecops90/dummy:v1"

# Upgrade release with new image version v2
#helm  upgrade --install app1-release ./app1 --set image.repository="devsecops90/dummy:v2"

# Rollback to previous release
#helm rollback app1-release 1

# Helm history
#helm history

