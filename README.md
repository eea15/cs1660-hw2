# cs1660-hw2: Emma Akbari

First container:
- URL for Docker image: https://hub.docker.com/repository/docker/eakbari/hw2
  (also in hw2_first_container_p1.txt)
- Screenshot of execution: hw2_first_container_p2.png
- Print for Dockerfile:
  FROM openjdk:7
  COPY . /usr/src/myapp
  WORKDIR /usr/src/myapp
  RUN javac HelloWorld.java
  CMD ["java", "HelloWorld"]
  
  Print for source code (HelloWorld.java):
  class HelloWorld {
    public static void main(String args[]) {
        System.out.println("Hello World");
    }
  }
  
Second container:
- Screenshot: hw2_second_container.png
