Dear candidate,

Thank you so much for accepting our challenge. We are really excited to know more about your tech skills. 

- You have 7 days after you received the email to publish your solution (including Saturday and Sunday), the sooner you publish it the better.
- Please publish your solution in a **private** repository and invite: priyanka-asati, patilyogeshp, esteban-uo

## What we will measure?
- UX / Usability 
- Code Best practices
- Knowledge specifics to the Language/Framework

------------------
## Description
ACME Corp helps airlines to deploy aircrafts world wide. The number of aircrafts flying are regulated by an institution. ACME Corp advices airlines when is the best time to do it.

Please support ACME Corp, building a solution to **visualise** the current air traffic so they know when is the best time to advice airlines to deploy an aircraft.

## Scenarios
1. As ACME Corp I want to see  on real time (every 10 secs) all aircrafts grouped by origin country so that I know at glance which countries we have available.
2. As ACME Corp I want to see how many aircrafts are currently on the air for a specific country so that I know what is the current traffic of the given country
3. As ACME Corp I want to see which aircrafts will departure in a previously selected country and in the next 20 minutes for a specific airport name so that I know how is going to be the air traffic in the next hours.
4. As ACME Corp I want to see in a map the actual location of one the selected aircraft so that I have a better understanding on where one aircraft is.


## Technical Notes:
- Use opensky free API to build your solution
https://openskynetwork.github.io/opensky-api/rest.html some API examples: ie. Get all aircrafts: https://opensky-network.org/api/states/all i.e All aircrafts arriving at Frankfurt https://opensky-network.org/api/flights/arrival?airport=EDDF&begin=1517227200&end=1517230800
- For scenario 3, the list of airports names are available here https://ourairports.com/data/airports.csv (column ident is airport code in API), please expose the data through an endpoint, so your solution can consume it
- For scenario 4, you could use google maps i.e https://www.google.com/maps/search/?api=1&query=28.6139,77.2090
- Frontend: javascript with react or vue
- Backend: python. Infrastructure in AWS is a plus
- Out of scope: the solution being deployed, authentication/authorization, no need of persistence (if you want to use it, up to you)

