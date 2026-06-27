# AWS Virtualization Basics

## Cloud Computing

**Definition:**  
Cloud Computing is the use of remote servers on the Internet to store, manage, and process data, instead of using our own local servers or personal computers.

### What is Cloud Computing?
It is a service provided by Cloud Vendors (like Amazon, Google, Microsoft, etc.).  
Instead of buying our own servers, building racks, setting up networks, and managing everything ourselves, we simply rent the computing resources and services from cloud vendors.

### Main Advantages (Why we use Cloud):
1. Reduces cost (no need to buy expensive hardware)
2. Saves storage space on our local devices
3. Saves time (no need to set up and maintain servers)
4. Reduces power consumption
5. Less maintenance work
6. Easier monitoring and management

## AWS (Amazon Web Services)

AWS is the world's largest and most popular Cloud Computing platform provided by Amazon. It offers hundreds of services (like storage, computing power, databases, security, etc.) over the internet.  
Instead of buying and managing your own servers, we can rent powerful resources from AWS and pay only for what we use.

**Before AWS:** Companies had to buy their own servers, set up data centers, manage hardware, and spend a lot of money and time. It was very costly, difficult to maintain, and hard to scale.

### Why Companies Use AWS? (Main Advantages)

1. **Pay-as-you-go (Cost Effective)**
   - We pay only for the resources we actually use.
   - No need to buy expensive servers or hardware upfront.
   - Saves a lot of money.

2. **Scalability (Easy to Grow)**
   - We can increase or decrease resources as per we need.
   - Handles sudden traffic spikes easily.

3. **High Flexibility & Agility**
   - AWS provides a wide range of tools and services.
   - You can quickly launch new applications, test ideas, and innovate faster.
   - Access services from anywhere in the world.

4. **Low Maintenance**
   - AWS takes care of all server maintenance, updates, repairs, and management.
   - You don’t have to worry about hardware problems or upgrades.

5. **Strong Security**
   - AWS provides very high-level security by default.
   - Advanced security tools and services are available.
   - Often more secure than managing security on your own servers.

6. **Global Reach & Reliability**
   - AWS has data centers all over the world.
   - Your applications run faster for users anywhere (low latency).
   - High reliability – your services stay up even if there is a problem in one location.

## AWS Regions and Availability Zones

### Regions
A Region is a collection of Availability Zones (data centers) located in a specific geographic area.  
Each Region is isolated from other Regions.  
Most AWS services are Region-specific and some are Global (e.g., IAM, Route 53, CloudFront).

- **39 geographic Regions** and **123 Availability Zones (AZs)** worldwide.

**Purpose:**
- High availability
- Disaster recovery
- Low latency for customers in that area
- Compliance with local laws

**Example:**
1. Mumbai Region (`ap-south-1`)
2. Hyderabad Region (`ap-south-2`)
   - These two are different Regions in India.

### Availability Zone (AZ)
- An Availability Zone is a physical data center (or group of data centers) inside a Region.
- You can have multiple data centers in one Availability Zone.
- One Region usually has 2 to 6 Availability Zones.
- AZs inside the same Region are connected with high-speed, low-latency links.
- AZs are isolated from each other so that if one AZ fails due to disaster (power failure, flood, fire, etc.), the other AZs in the same Region continue to work.
- Designed for high availability (24/7 service).
- There is usually at least 100 miles distance between two AZs in the same Region.

## Cloud Computing Service Models (AWS Focus)

... (full detailed content as before)