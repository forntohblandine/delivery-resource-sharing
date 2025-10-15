# Delivery-Resource-Sharing
A cloud-based platform that enables small businesses in the same area to share delivery vehicles and resources
# Project Overview
The aim of this project is to build a platform where small business in a local community, for example in the town of Yaounde where small or medium-sized business owners can register their business as well as their delivery drivers and independent delivery drivers. This will allow businesses without a delivery driver to find and book a delivery drivers to deliver their goods.
# Problem Description
Many business today have an online presence and most customers prefer their goods to be deivered to them. Often times most business have not delivery person to hire for the delivery process and they have to do it themselves or some business have a delivery person just specific to that business.
# Proposed Solution
With this platform, business can easily find delivery personnel and businesses who already have a delivery person can share with the other business.
# System Design
This system follows a three layer architecture
  # Frontend Layer
  - HTML, CSS and Bootstrap templates integrated with Flask(Flask).
  - User interface for registration, login, posting delivery offers and viewing matches.
  # Backend Layer
  - Implemented using Flask(Python).
  - Handles all business logic, such as user authentication, saving and retrieving delivery posts, and matching nearby delivery routes.
  - Communicates with the database using Flask’s built-in tools (SQLite).
  # Database
  - Using SQLite for Data storage.
# Why it is Scalable
- This system is hosted on the cloud which allows it to scale automatically as businesses join.
# Why it is Fault-tolerant
Fault-tolerance can be achieved by using cloud redundancy
- If one server fails, traffic is rerouted to another server.
- Data is stored in multiple availabilty zones to prevent data loss
- Regular backups are done to make sure that the platform can recover from any crash
# Why it allows collaboration
- Multiple people and businesses using the platform together
- Businesses can share delivery routes, split vehicle cost and coordinate delivery schedules
- A shared dashboard and messaging allows business to communicate with ease.
# Conclusion
This cloud-based platfoem provides a scalable, fault-tolerant and collaorative solution to the delivery issues faced by small businesses by sharing delivery resources.
