# AuctionsUsingAgents
Multiagent system of english auction in Java using Jade 

Instructions for using program:
- first you need to download Jade (offical website)
- positioning in jade directory
- compiling of java classes (from command line):

      javac -classpath lib\jade.jar -d classes src\examples\Auctions\*.java
      
- running (example: agent auctioner + 2 agents buyers):

      java -cp lib\jade.jar;classes jade.Boot -gui -agents aukctioner:Auctioner("Picture Picasso",15000);buyer1:Buyer;buyer2:Buyer
