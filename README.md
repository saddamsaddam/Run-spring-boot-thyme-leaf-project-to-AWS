# Run-spring-boot-thyme-leaf-project-to-AWS

https://www.linkedin.com/posts/saddam-hossen-619a81174_alhamdulillah-deploy-spring-boot-project-activity-7315069987742760960-qjK5?utm_source=share&utm_medium=member_desktop&rcm=ACoAAClzCjUBHlifkJwMqARVRi6P_1Z20WL_FVU


ubuntu@ip-172-31-46-9:~$ cd home


ubuntu@ip-172-31-46-9:~/home$ unzip DeviceManagement.zip


Archive:  DeviceManagement.zip
   creating: DeviceManagement/
  inflating: DeviceManagement/.gitignore  
   creating: DeviceManagement/.idea/
  
ubuntu@ip-172-31-46-9:~/home$ rm -f Devicemanagement.zip

ubuntu@ip-172-31-46-9:~/home$ cd Devicemanagement

-bash: cd: Devicemanagement: No such file or directory

ubuntu@ip-172-31-46-9:~/home$ cd DeviceManagement

ubuntu@ip-172-31-46-9:~/home/DeviceManagement$ cd ..

ubuntu@ip-172-31-46-9:~/home$ cd DeviceManagement

ubuntu@ip-172-31-46-9:~/home/DeviceManagement$  docker buildx build -t userservice .

[+] Building 11.5s (8/8) FINISHED                                                                                                     docker:default
 => [internal] load build definition from Dockerfile                                                                                            0.0s
 => => transferring dockerfile: 431B                                                                                                            0.0s
 => [internal] load metadata for docker.io/library/eclipse-temurin:21-jdk-jammy                                                                 1.6s
 => [internal] load .dockerignore                                                                                                               0.0s
 => => transferring context: 2B                                                                                                                 0.0s
 => [1/3] FROM docker.io/library/eclipse-temurin:21-jdk-jammy@sha256:9fb1b4d024cb6c64fa1242d36d5f2be7b462eee1a8ecdba242a0bc5fb9937027           9.0s
 => => resolve docker.io/library/eclipse-temurin:21-jdk-jammy@sha256:9fb1b4d024cb6c64fa1242d36d5f2be7b462eee1a8ecdba242a0bc5fb9937027           0.0s                                     
 => [internal] load build context                                                                                                               0.5s
 => => transferring context: 45.72MB                                                                                                            0.5s
 => [2/3] WORKDIR /app                                                                                                                          0.1s
 => [3/3] COPY target/DeviceManagement-0.0.1-SNAPSHOT.jar app.jar                                                                               0.3s
 => exporting to image                                                                                                                          0.3s
 => => exporting layers                                                                                                                         0.3s
 => => writing image sha256:12b209d5a927a314b709721ba715ba37b92e9150f1b3bf2ac29985ca5ef71bc5                                                    0.0s
 => => naming to docker.io/library/userservice  0.0s

 
ubuntu@ip-172-31-46-9:~/home/DeviceManagement$ docker run --name snvnv1 -d -p 8080:8080 userservice

96f0976b71b736bd6c8b5d2b7ea8dd8e7a3fc5cda8790500c35a9d4667d4d8b6


ubuntu@ip-172-31-46-9:~/home/DeviceManagement$ docker ps

CONTAINER ID   IMAGE         COMMAND               CREATED         STATUS         PORTS                                         NAMES
96f0976b71b7   userservice   "java -jar app.jar"   9 minutes ago   Up 9 minutes   0.0.0.0:8080->8080/tcp, [::]:8080->8080/tcp   snvnv1


ubuntu@ip-172-31-46-9:~/home/DeviceManagement$ docker logs snvnv1

  .   ____          _            __ _ _
 /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
 \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
  '  |____| .__|_| |_|_| |_\__, | / / / /
 =========|_|==============|___/=/_/_/_/

 :: Spring Boot ::                (v3.3.0)

2025-04-07T13:47:24.678Z  INFO 1 --- [           main] c.d.D.DeviceManagementApplication        : Starting DeviceManagementApplication v0.0.1-SNAPSHOT using Java 21.0.6 with PID 1 

2025-04-07T13:47:28.025Z  INFO 1 --- [           main] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat initialized with port 8080 (http)
2025-04-07T13:47:28.046Z  INFO 1 --- [           main] o.apache.catalina.core.StandardService   : Starting service [Tomcat]

Program Are started


ubuntu@ip-172-31-46-9:~/home/DeviceManagement$ curl http://localhost:8080/


{"timestamp":1744034350956,"status":404,"error":"Not Found","path":"/"}


ubuntu@ip-172-31-46-9:~/home/DeviceManagement$ 


ubuntu@ip-172-31-46-9:~/home/DeviceManagement$ curl http://localhost:8080/login/login 


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Form</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <style>
        body {

            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            height: 100vh; /* Ensure body covers full viewport height */
        }
        .login-form {
            margin-top: 150px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            border-radius: 10px;
            overflow: hidden;
            animation: slide-up 0.5s ease;
        }
        @keyframes slide-up {
            from {
                opacity: 0;
                transform: translateY(50px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>
<div class="container">
    <div class="row justify-content-center">
        <div class="col-md-6">
            <div class="login-form bg-white p-4">
                <h2 class="text-center mb-4">Login</h2>
                <form action="/login/home" method="post">
                    <div class="form-group">
                        <label for="username">Username</label>
                        <input type="text" class="form-control" id="username" name="username" required>
                    </div>
                    <div class="form-group">
                        <label for="password">Password</label>
                        <input type="password" class="form-control" id="password" name="password" required>
                    </div>
                    <button type="submit" class="btn btn-primary btn-block">Login</button>
                </form>
            </div>
        </div>
    </div>
</div>

<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.4/dist/umd/popper.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>





Great! Here's how to figure out **which security group** is currently applied to your EC2 instance, and **where to add the port 8080 rule**:

---

### ✅ Step 1: Check which security group your EC2 is using

1. Go to the **EC2 Dashboard** in AWS Console.
2. Click on your **running EC2 instance**.
3. Scroll down to the **“Security”** section.
4. Look at the **Security Groups** — note the name (e.g. `launch-wizard-1` or `default`).

---

### ✅ Step 2: Add Inbound Rule for Port 8080

Now that you know which one is attached:

1. Click on that **Security Group name** (it’s a link).
2. Go to the **Inbound rules** tab.
3. Click **Edit inbound rules** → **Add rule**:
   - **Type**: Custom TCP
   - **Port range**: `8080`
   - **Source**: `0.0.0.0/0` *(for public access)* or just your IP for restricted access.
4. Click **Save rules**.

---

### ✅ Step 3: Try opening

Now visit:
```
http://16.171.0.77:8080/login/login   //   http://ec2-16-171-0-77.eu-north-1.compute.amazonaws.com:8080/login/login
```

---

Let me know if you're unsure which one to edit or if the page still doesn't load after this. I can walk you through with screenshots-style steps too.
