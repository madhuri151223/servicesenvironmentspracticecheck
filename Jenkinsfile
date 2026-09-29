pipeline {
   agent any 
     stages {
        stage ('Practice')  {
           
          steps {
      
           script {
           def services = [ "payment-service",
                          "order-service",
                          "user-service",
                          "notification-service" ]
           def environments = [ "Development",
                              "QA",
                              "Production" ]
for (service in services) {
 for(environment in environments) {
    
   continue
   if(environment == "Production"){
      echo "deploying $service to $environment" 
      echo "${environment } requires approval"
      continue


}
}
}

           
}
}
}
}
}





