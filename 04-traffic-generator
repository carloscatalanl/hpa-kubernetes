#!/bin/bash
 
# Get minikube ip
MKIP=$(minikube ip)

# Infinite loop
while true
do 
  curl $MKIP':30000'
  echo 'Press ctrl+c to escape.'
done
# Press ctrl+c to escape