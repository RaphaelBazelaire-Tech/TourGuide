TourGuide is a travel planning app built using the Spring Boot framework.

It enables users to receive recommendations for tourist attractions closest to their current location,
whilst also offering them discounts on hotels and tickets for shows, as well as a rewards points scheme.

# Technologies

> Java 21  
> Spring Boot 3.X  
> JUnit 5

# How to have gpsUtil, rewardCentral and tripPricer dependencies available ?

> If you use PowerShell, run : 
- mvn install:install-file "-Dfile=libs/gpsUtil.jar" "-DgroupId=gpsUtil" "-DartifactId=gpsUtil" "-Dversion=1.0.0" "-Dpackaging=jar"


- mvn install:install-file "-Dfile=libs/RewardCentral.jar" "-DgroupId=rewardCentral" "-DartifactId=rewardCentral" "-Dversion=1.0.0" "-Dpackaging=jar"


- mvn install:install-file "-Dfile=libs/TripPricer.jar" "-DgroupId=tripPricer" "-DartifactId=tripPricer" "-Dversion=1.0.0" "-Dpackaging=jar"

> If you don't use PowerShell, run : 
- mvn install:install-file -Dfile=libs/gpsUtil.jar -DgroupId=gpsUtil -DartifactId=gpsUtil -Dversion=1.0.0 -Dpackaging=jar


- mvn install:install-file -Dfile=libs/RewardCentral.jar -DgroupId=rewardCentral -DartifactId=rewardCentral -Dversion=1.0.0 -Dpackaging=jar


- mvn install:install-file -Dfile=libs/TripPricer.jar -DgroupId=tripPricer -DartifactId=tripPricer -Dversion=1.0.0 -Dpackaging=jar
