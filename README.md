# ROS Modelling Assignment

In this assignment you will model a robotic system and its interactions with the environment using the *JetBrains MPS*.

## Learning Objectives

The student should be able to

- understand the concepts of Model- and Domain-Specific languages
- know how to use the *JetBrains MPS* for modelling robotic systems and specifically ROS 2.

## Task

### Outline

Assuming that you are working in a start-up company developing logistic robots and application. You receive the following message from a potential customer.

> To whom it may concern,  
> I'm the manager of a warehouse which stores and dispatches products for online retailers. With the strong increase of orders that our clients are seing due to the Corona pandemic, we would like to automate our warehouse. Particularly we are searching for a system that is able to store arriving merchandise on our shelves, dispatch an item on request by an arriving order, and to throw away old items to make room for new items on demand.  
>
> Our warehouse has three delivery ports, where new items are delivered by our customers. Those items have to be stored and carefully inventoried, such that our order management system is always aware of the current stock.  
> The items in stock are stored in multiple lines of shelfs, organized in corridors and blocks in a particular storage area of the warehouse.  
> For processing an order, there are two dispatchers present, which are manned by packaging staff. The automation should allow this staff to work a lot more efficient, since the items would be delivered to their dispatcher instead of them picking it up from the shelf.  
> From time to time it happens, that customers are chaning their range of products or simply overbook their capacities that they are renting at our facility. In such a case it is our policy to throw away the oldest items on arrival of new ones to allow for a continuation of business.
>
> Since our budget is limited, we are interested in purchasing a fleet of cheap robots and to run them in a multi robot system, as suggested on your website. Each individual robot only needs to handle one item at a time.  
> An important thing to note is, that for security reasons we want the robots to only handle items on the delivery ports, the trash, and the dispatchers when stepping on top of a marker. This problem doesn't exist with the shelves, as they can be accessed on either side. However, there are also certain *no-go* areas for the robots. For example, we have two fire doors in our warehouse that need to be free at any time. Since the robots are carrying heavy items and there being at least a 1% chance of them dropping it according to your datasheet, we do not want to take the risk of such a heavy item blocking the emergency exit and would like to restrict the robots to not go their. We also want the robots to return to their charging docs whenver they are not in use, such that they do not run out of battery during busy hours and also do not block the way for both other robots and human personell.
>
> This actually brings me to a last very important point. From time to time, there is human personell on site to perform repairs, inspections or other duties like cleaning. The security of our staff is the highest priority, so we need some way for the system to handle those situations. Shutting down the entire warehouse however, is not an option. 
>
> We hope we can make business with you.
>
> Kind regards,  
> John Smith

### Instructions

- [ ] Make yourself familiar with the *JetBrains MPS* (see resources)
- [ ] Complete the tutorial and set up your MPS environment
- [ ] Model the above scenario with the MPS toolchain and think about high-level components for both the robot and the warehouse. Reason about what kind of communication channel is required for interaction and information exchange among robots and the warehouse.
- [ ] Provide a short write-up of your ideas and modeling decisions in the `writeup.md` file.
- [ ] Provide an initial model in MPS of your ROS-based multi-robot system.
- [ ] Prepare yourself for a short (5min) in class presentation of your model.

## Resources

- [ROS-2 Documentation](https://docs.ros.org/en/rolling/index.html)
- [ROS-2 Ubuntu/Debian Installation](https://docs.ros.org/en/foxy/Installation/Ubuntu-Development-Setup.html#system-requirements)
- [MPS User's Guide](https://www.jetbrains.com/help/mps/mps-user-s-guide.html)
- 
