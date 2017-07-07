# Hands-on-With-Kubeless



•	Download Kubeless from https://github.com/kubeless/kubeless/releases
•	kubeless install
•	kubectl get pods –n kubeless 
•	kubectl get deployment –n kubeless
•	kubectl get statefulset –n kubeless
•	kubectl get thirdpartyresorces 
•	kubeless function deploy get-recommendation --runtime python27 --handler recommendation.getrec --from-file recommendation.py --trigger-http
•	kubeless function ls
•	kubeless function call get-recommendation
•	kubeless function delete get-recommendation
