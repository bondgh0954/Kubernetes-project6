<h1>Kubernetes Demo Project6</h1>
<h2>Technologies used</h2>

- <b>Kubernetes</b> 
- <b>Helm</b>



<h2>Detailed Description of Project </h2>
1. Create 1 shared Helm Chart for all microservices to reuse common deployment and Service configuratons for the services<br/>



   <p align="">
   <h2>step1</h2>
   Create a Helm chart with chart name "microservice"<br/>
   "helm create microservice"
   Create "deployment.yaml" and "service.yaml" configuration files in the template repository
   Create "values.yaml" file and define all the default values for the configuration files
   <img src='./cam/m1.png' height="80%" width="80%" alt="Disk Sanitization Steps">

   Create values configuration files for each of the services to overide the default values
   
 
  
   From the above information, a connection graph is generated 
   <img src='./cam/m1.png' height="80%" width="80%" alt="Disk Sanitization Steps">



   <h2>step2</h2>
   Create a kubernetes cluster in linode<br/>
   change permission on kubeconfig.yaml file<br/>
   connect to the cluster<br/>
   
  
  
  

   <h2>step3</h2>
 
  Create Deployment and Service for all microServices in the created cluster
   <img src='./cam/m3.png' height="80%" width="80%" alt="Disk Sanitization Steps">
   

 <h2>step4</h2>
 All pod are running and application can be accessed in the browser using the node IP and <br/>
 configured external service IP with the frontend service<br/>
 <img src='./cam/m2.png' height="80%" width="80%" alt="Disk Sanitization Steps">
     

</p>
