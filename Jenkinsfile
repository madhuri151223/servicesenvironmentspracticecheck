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
   if(environment == "Production"){
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
}





