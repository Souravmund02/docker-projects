#Pull a base image which gives all requier tools and libraires
FROM eclipse-temurin:17-jdk


#Create  a Folder whre the app code will be stored
WORKDIR /app


#Copy the source code from your HOST machince to your container
COPY src/Main.java /app/Main.java


#Compline the source code
RUN javac Main.java


#Run the application
CMD ["java","Main"] 
