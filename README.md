# Flight-Diversion-Strategy-Simulation-ARENA


## Demo Run 
https://user-images.githubusercontent.com/83858671/161437282-9d672d2c-9c9b-4f80-8591-fa40c70c3663.mp4

## Problem Statement
During the winter season there is a huge fog situation in Delhi due to which flights could not land in the Delhi Airport. The Airport authority has decided to divert the flights to other nearby Airports. Create a Simulation model and simulate the airport operations and record arrival times for comparison.

## Introduction
Our project deals with airlines’ diversion management, which entails a complex decision-making process that comes into action during adverse events, preventing the execution of the regular flight operations. Diverting from the intended route can be caused by several reasons, the most frequent of which are: repugnant weather that prohibits aircraft from taking off and landing, medical emergencies or technical faults such as Unexpected aircraft delays, Maintenance problems of aircraft, Crew unavailability. A flight diversion can severely disrupt the passenger’s comfort, jeopardize the fleet or the crew planning and is generally accompanied with significant expenses. The intention of every airline in the case of a diversion is to assure the fastest turnaround time and/or provide the passengers with the highest level of services to mitigate the negative effects. A wrong selection of an alternate airport that is not having enough capacity, personnel or material resources to handle a flight diversion in a timely manner can negatively influence the airline in several ways. Both strategic and tactical diversion management process is a collaborative decision-making procedure, heavily dependent on the base of the information available, where the main actors are not only flight crew and the airline Operational Control Center but also the Air Traffic Controller, airport operators and the local service providers.

Occurrence of fog during late night or early morning over the northern plains of India is common in winter. Fog is defined as an obscurity near the surface layer of the atmosphere which is caused by a suspension of water droplets and is associated with visibility less than 1000 m. More than 900 aircrafts on an average depart and arrive daily from Indira Gandhi International (IGI) Airport,New Delhi, with the maximum number at night and morning hours when chances of dense fog are high during the peak winter months of december and january; due to this many flights are either cancelled or diverted. Due to the availability of only one full-time run way (RW-28) during low visibility period because of fog,air traffic operation over IGI further aggravates, with high holding period and severe
congestion.Also,IGI is one of India’s airports where sophisticated CAT-III ILS has been installed to assist pilots to operate aircraft under dense fog condition with visibility up to 50 m but still the need for diversion to alternate airports comes into play.


## Strategies to choose diversion airport:
There is no given methodology for the diversion airport selection that would be determining and mandating to use the alternate airport as per given set of hard rules. Therefore, for every flight a flight planner can select an alternate airport as per the current requirements of dedicated flight or preferences of the airline operator. Especially for small airlines, only basic characteristics of the airport are examined such as the opening hours and physical characteristics. As a best practice, various factors playing a role in the diversion location selection are evaluated and can be divided into two groups:


## Basic factors (determining if an aircraft can land on an airport):
•	Airport operational, physical and technical characteristics to accept the aircraft type at given time (runway length, equipment, opening hours, curfews etc.)
•	Weather conditions

•	Distance from the intended route and destination (fuel planning)

•	Other (pilot licenses, etc.)

Commercial factors (influencing the diversion recovery):

•	Relative proximity of the diversion location as a passenger wellbeing factor

•	Level of airport infrastructure (airport size)

•	Airline’s own infrastructure (own or contracted airline staff present on the location)

•	Existence of agreements with the handlers, fueler and other stakeholders

•	Experiences with the given location

•	Other commercially important and detailed factors (hotels availability, transportation possibilities, etc.)

Based on the evaluation of the above, the flight planner decides about the alternate locations, files them in the flight plan and provides them to the crew at the time of the pre-flight briefing. At least two scenarios consequent to the diversion landing shall be assessed:

•	Technical stop - the aircraft is refueled and dispatched as soon as possible, the passengers are often remaining on board

•	Full termination of the flight – when an aircraft is forced to stay on the diversion airport for an extended period of time.

## Diversion Risk Index :
The airport diversion risk index is a new proposed attribute that is assigned to the aircrafts that were unable to land in Delhi Airport. The flights choose the alternate airport to land , based on the Risk Diversion Index (DRI) and other constraints like Runway Utilization, Available Parking Space at airport, etc.
There are many scenarios that determine how long an airplane will be delayed in an event of a diversion and many elements that do play a role in the delay estimation. The most important factors contributing to the delays that need to be looked at, are mostly associated with ground resources availability. As the evaluation of all the ground resources in a diversion event might be complicated, it is beneficial to assign every flight with the current Risk Diversion Index (DRI) based on the possible impact it might have on landing on any of the alternate airports. This index shall be used as a standard across the network to ensure consistency and credibility of calculated values based on which ultimate tactical decisions are made.
RDI is calculated for each airport and assigned to the flight. The flight diverts its route to the airport with least RDI .

### RDI Formula:
RDI = 1/(c + available flight parking spaces – parking spaces in use )
c = constant added to avoid zero division error


