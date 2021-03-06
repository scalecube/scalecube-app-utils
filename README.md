# scalecube-app-utils

# Usage
``` java

Logo.builder().tagVersion(packageInfo.version())
        .port(String.valueOf(seed.cluster().address().port()))
        .ip(seed.cluster().address().host())
        .group(packageInfo.groupId())
        .artifact(packageInfo.artifactId())
        .javaVersion(packageInfo.java())
        .osType(packageInfo.os())
        .pid(packageInfo.pid())
        .hostname(packageInfo.hostname())
        .website().draw();
        

Logo.from(packageInfo)
        .port(String.valueOf(seed.cluster().address().port()))
        .ip(seed.cluster().address().host())
        .draw();
        
```

# Print-out:
``` java
                         .,,,,,,                          
                       .,,,,,,,,,,,,/                     
                  .,,,,,,,,,,,,,,,,,,,.                   
               .,,,,,,,,,,,,,,,,,,,,,,,,,,,.              
            .,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,.           
         ,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,        
     ,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,             ScaleCube Development is Running.
     *  ,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,*               Group: Development
     ***** /,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,/  ....            Artifact: Development
     ******** /*,,,,,,,,,,,,,,,,,,,,,,,,,,,,/  .......            Java: 1.8.0_131
     ***********, /,,,,,,,,,,,,,,,,,,,,,*  ...........            OS: Windows 10
     ***************. *,,,,,,,,,,,,,*/ ...............            PID: 4312
     ******************, /*,,,,,,/  ..................            Host Name: my-host-name
     ********************** /*/  .....................    
     ************************ ........................            http://scalecube.io
     ************************ ........................            https://github.com/scalecube
     ************************ ........................    
     ************************ ........................    
     ************************ ........................    
     ************************ ........................    
     ************************ ........................    
     ************************ ........................    
         ******************** ....................        
            ***************** .................           
                ************* .............               
                   ********** ..........                  
                       ****** ......                      
                          *** ...                         
```