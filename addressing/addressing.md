# Addressing Unplugged

This activity focuses on the problem of specifying a packet's intended destination. Through this activity, students "discover" the benefits, limitations, and relationships between different network addressing systems.

**Activity Duration:** ~10 minutes

**Group size:** 2+ students

**Materials required:** None

**Student background knowledge:** Students should be introduced to packet-switching before completing this activity.

## Introduce the activity to students
Pose the following question to students: _If you wanted a taxi driver to take you to a particular restaurant, how would you specify your destination? What are the advantages/disadvantages of different approaches?_

## Students complete the activity
💡 **Tip:** Ask students to come up with at least three different approaches.

## Discuss students' ideas
Ask groups to share their ideas with the class.

Students' ideas, and their networking equivalents, typically include: 

* a street address ≈ [Internet Protocol (IP) addresses](https://en.wikipedia.org/wiki/IP_address) — both are hierarchical
* the restaurant's name ≈ [domain names](https://en.wikipedia.org/wiki/Domain_name) — both are easy for humans remember
* a restaurant type ≈ [top-level domains (TLDs)](https://en.wikipedia.org/wiki/Top-level_domain) or [anycast](https://en.wikipedia.org/wiki/Anycast)
* step-by-step directions ≈ [source routing](https://en.wikipedia.org/wiki/Source_routing)
* latitude and longitude coordinates ≈ [MAC addresses](https://en.wikipedia.org/wiki/MAC_address) — GPS coordinates are tied to a physical location in the same way MAC addresses are tied to physical hardware

⚠️ **Note:** Another common idea is to provide a nearby landmark, but we have not identified a networking equivalent for this approach.

💡 **Tip:** These analogies can continue to be used when explaining addressing and routing in detail, such as:

* class-based addressing—e.g., a street address without a house number is like a class C address
* DNS records—e.g., a restaurant with multiple locations is like a domain name with multiple A records
* Address Resolution Protocol (ARP)—e.g., a street address can be converted to latitude and longitude coordinates like an IP address can be resolved to a MAC address
* port numbers—e.g., apartments or suites within a building are like processes within a host
* autonomous systems (ASes)—e.g., major cities each have their own public transit system like each AS manages its own intra-domain routing
* routing entries—e.g., highway signs indicate where exits lead to like routing entries map subnets to next hops
