#Kavach

Citizen Portal/ App for Mitigating Road Safety Issues!

Objectives:-
 - A person can **raise an issue or report any violation** through the app.
 - In case of an **accident**, the app shall **send message to police, ambulance, and nearby hospital.**
 - In case of any **violations, police and other stakeholders may take an action** on to the issue raised by the app.
 - The solution should **help to prevent accidents** as well.

Usage of Kavach:-

For User:
 - Allows users to **report accidents easily and without hassle.**
 - Offers a **bounty program** for reporting voilations of law.
 - Assistance to users by **identifying nearby facilities such as hospitals, police stations, and tow trucks.**
 - Integrated with **emergency services** for quick and efficient response **in case of an accident**.
 - **Revolutionize the way we approach road safety** and make a significant impact on **saving lives.**

For Admin:

Using Rollbased Access Control (RABC) Mechanism
 ```mermaid
graph TD;
    RABC-->ADMIN;
    RABC-->POLICE;
    RABC-->HOSPITAL;
    ADMIN-->NAGAR_NIGAM;
    ADMIN-->FIRE_BRIGADE;
    ADMIN-->TOW_TRUCK;
```  
