# jumper-assignment-s113809
jumper-assignment-s113809 created by GitHub Classroom



tutorial namaken project


stap 1

maak een unity wereld met een grond een cubus 
![image](https://user-images.githubusercontent.com/93989713/165235719-c80861ce-7020-4154-875c-33e00e5a141b.png)


stap 2

installeer unity mlagents(voor dit project gebruiken wij versie 2.0.1)
dit kan je doen via de package manager. deze is te vinden onder window->packagemanager
![image](https://user-images.githubusercontent.com/93989713/165236138-d05983f4-f422-451f-8016-41de0dc9a41e.png)

stap 3 script maken


3.1 agent

maak een script dat de cubeagent gaat besturen. in dit project noemt dat cube_agent_rays. in dit script nemen we over van de Agents en inporteren we mlagents

![image](https://user-images.githubusercontent.com/93989713/165236629-f2fe134d-d545-4634-aed9-48f3797ee3ae.png)


met deze code zal de agent op de begin locatie worden gezet waneer hij dood gaat

![image](https://user-images.githubusercontent.com/93989713/165236751-a3d2d5bc-1ead-4b3b-86cd-cacc7d5f9299.png)

om onze agent te kunnen bewegen moeten we dit ook kunnen doen dit gebeurt door volgende code

![image](https://user-images.githubusercontent.com/93989713/165237155-7a4c57fd-85ba-42d8-a2ca-bec0b5e1bcf4.png)

deze code word opgevangen door OnActionReceived. deze code zegt dat als vertical hoger is dan 1 dat hij moet springen.

![image](https://user-images.githubusercontent.com/93989713/165237391-7c87f3d7-1dbc-4567-89f1-1dcd4f43dc35.png)

daarna voegen we de code toe voor collision. waneer hij tegen een object bots zal het checken ofdat het een obsical is of point

![image](https://user-images.githubusercontent.com/93989713/165253377-31aa9da2-84ba-41e3-9a3e-01c31e266c48.png)


3.2 spawner

voor de obstakels te maken hebben we een script nodig. dit script noemt spawner. in dit script definieeren we een locatie voor het object te maken en een min tijd en een maximum tijd. dan zal het script een random doen om te zien hoe lang hij moet wachten om een object te maken.



![image](https://user-images.githubusercontent.com/93989713/165253813-191d3000-0a50-4b0f-92f2-6b94cb800c85.png)


4 obstakel

we moeten nog een obstakel maken deze bestaat uit een rechthoek van onder een een kleinere van boven.

![image](https://user-images.githubusercontent.com/93989713/165254329-3cbc88b7-486d-4400-9f97-ce831f3e61da.png)

om de onderste balk voegen we een script toe dat obstical.cs noemt dit script beweegt het object naar voor en verwijderd het als het tegen een muur loopt.

![image](https://user-images.githubusercontent.com/93989713/165254680-77bafea7-6187-416c-a26e-265ec69b6abc.png)







