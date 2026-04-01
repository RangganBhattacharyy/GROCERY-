# GROCERY-INTRODUCTION 
In an era dominated by digital convenience, e-commerce has emerged as a cornerstone 
of modern consumer behavior. The project is a full-fledged, scalable e-commerce 
platform designed to bridge the gap between sellers and buyers in a seamless, efficient, 
and secure digital environment. 
Built using the powerful MERN stack (MongoDB, Express.js, React, and Node.js), 
along with modern tools like Vite, Tailwind CSS, and Stripe, offers a lightning-fast, 
mobile-responsive, and feature-rich online shopping experience. Whether it’s product 
browsing, cart management, secure checkout, or seller-side inventory control — every 
element of this system is crafted with performance, security, and user satisfaction in 
mind. 
The project not only demonstrates strong technical foundations in full-stack web 
development but also highlights modern design principles and cloud-native 
deployment strategies using Vercel. With integrations like Cloudinary for media 
hosting and Stripe for payments, stands as a compelling example of what a modern 
digital commerce application should look like. 
is more than a college project — it's a blueprint for scalable, real-world e-commerce 
solutions. 
2 
2A.OBJECTIVE : 
The primary objective of the project is to design and implement a robust, secure, and user-friendly 
e-commerce platform that provides seamless interaction between buyers and sellers. The project 
aims to demonstrate practical knowledge of full-stack development while integrating real-world 
functionalities and third-party services to simulate a live online shopping experience. 
Below are the core objectives of the project: 
1. Full-Stack Web Development Implementation 
To develop an end-to-end application using the MERN stack (MongoDB, Express.js, React.js, 
Node.js), ensuring a clean separation between frontend and backend, along with RESTful APIs for 
seamless communication. 
2. User Authentication and Role Management 
To implement secure, cookie-based login and registration mechanisms using JWT (JSON Web 
Tokens), and manage multiple roles (User, Seller, Admin) with appropriate access control and data 
segregation. 
3. Product Lifecycle Management 
To allow sellers to add, update, and delete products, while enabling users to browse, filter, and 
search products efficiently through a modern UI. This also includes image uploads using 
Cloudinary. 
4. Shopping Cart and Checkout Flow 
To design an interactive and persistent cart system that syncs with the backend, and guides users 
through a smooth checkout experience including address selection and order review. 
5. Secure Online Payments 
To integrate Stripe for secure and PCI-compliant payment processing, with support for real-time 
order creation, payment confirmation, and webhook handling for backend order validation. 
6. Responsive and Optimized Frontend 
3 
To build a fast, responsive, and visually appealing user interface using React.js, Tailwind CSS, and 
Vite. The goal is to ensure cross-device compatibility and a superior user experience. 
7. Cloud Deployment and DevOps Integration 
To deploy both frontend and backend on Vercel with proper environment configuration, routing, 
and continuous deployment support, demonstrating an understanding of cloud-native application 
hosting. 
8. Real-World Engineering Practices 
To adopt industry-standard practices including modular code structure, component reusability, 
state management, asynchronous API handling, and code linting using ESLint. 
This objective was not only to build a functional e-commerce platform but also to gain deep 
insights into modern web architecture, scalable API design, payment gateway integration, and 
cloud deployment strategies. 
4 
2B.SCOPE : 
Our project focuses on creating a mobile and/or web-based application that 
supports a wide range of learning materials for students of various age groups 
and educational levels. 
1. User Registration & Login : 
Secure sign-up/login for students, instructors, and admins. 
2. Instructor Dashboard : 
Tools for instructors to create, upload, and manage course content. 
3. Admin Panel : 
Controls for user management, course approvals, reports, and analytics. 
4. Multiplatform Access : 
Available on Android, iOS, and web browsers. 
5. Payment Integration: 
Support for subscriptions, one-time payments, or course purchases for 
users. 
5 
3.  SYSTEM ANALYSIS 
6 
3A.IDENTIFICATION OF NEED : 
of 
The digital commerce landscape demands scalable, responsive, and user-friendly systems to handle 
thousands 
concurrent 
users. 
addresses 
key 
like: 
1. Accessibility: The platform allows users to browse and purchase products from any device, 
promoting 
needs 
remote 
shopping. 
2. User Engagement: Real-time feedback via toasts, intuitive UI with Tailwind CSS, and a seamless 
product 
browsing 
experience. 
3. Seller Enablement: Sellers can manage products and view orders via a dedicated dashboard. 
4. Secure Transactions: Integration with Stripe ensures PCI-compliant and secure payment 
processing. 
3B.FEASIBILITY STUDY 
provides 
Technical Feasibility: The MERN stack ensures modularity and scalability. The use of Vite for the 
frontend 
fast 
builds 
and 
hot 
reloads. 
Economic Feasibility: Open-source technologies like Node.js, MongoDB, and Vite reduce licensing 
costs. 
Operational Feasibility: Clean code structure, RESTful APIs, and component-based architecture 
make the system easy to maintain and expand. 
7 
3C.WORKFLOW 
uses the Iterative Waterfall Model, beginning with requirement analysis and following through 
with design, development, testing, and deployment. Each phase is revisited for feedback and 
improvements. 
Advantages: - Structured phases with clear deliverables - Easy to track and manage progress 
Disadvantages: - Less flexibility for major scope changes - Slightly more overhead for iterative steps 
Applications: - Suitable for commercial applications with defined requirements that evolve incrementally. 
The Waterfall Model was the first Process Model to be introduced. It is also referred to as 
a linear- sequential life cycle model. It is very simple to understand and use. In a waterfall 
model, each phase must be completed before the next phase can begin and there is no 
overlapping in the phases. 
The waterfall model is the earliest SDLC approach that was used for software 
development. The waterfall Model illustrates the software development process in a linear 
sequential flow; hence it is also referred to as a linear-sequential life cycle model. This 
means that any phase in the development process begins only if the previous phase is 
complete. In the waterfall model phases do not overlap. 
Waterfall Model Design: 
The waterfall approach was the first SDLC Model to be used widely in Software Engineering to ensure 
the success of the project. In “The Waterfall” approach, the whole process of software development is 
divided into separate phases. In the Waterfall model, typically, the Outcome of one phase acts as the input 
for the next phase sequentially. 
Iterative Waterfall Design: 
Definition: The Iterative Waterfall Model is a variation of the traditional Waterfall model, which is a linear 
and sequential software development methodology. In the Iterative Waterfall Model, the development 
8 
process is divided into small, manageable cycles, allowing for the revisiting and refinement of phases 
before progressing to the next stage. It combines the systematic structure of the Waterfall model with the 
flexibility of iterative development. 
The sequential phases in Iterative Waterfall model are: 
➢ Requirement Gathering and Analysis: All possible requirements of the system to be 
developed are captured in this phase and documented in a requirement specification doc. 
➢ System Design: The requirement specifications from the first phase are studied in this 
phase and system design is prepared. System Design helps in specifying hardware and system 
requirements and also helps in defining overall system architecture. 
➢ Implementation: With inputs from system design, the system is first developed in small 
programs called units, which are integrated in the next phase. Each unit is developed and 
tested for its functionality which is referred to as Unit Testing. 
➢ Integration and Testing: All the units developed in the implementation phase are 
integrated into a system after testing each unit. Post integration the entire system is tested for 
any faults and failures. 
➢ Deployment of the system: Once the functional and non-functional testing is done, the 
product is deployed in the customer environment or released into the market. 
➢ Maintenance: Some issues come up in the client environment. To fix those issues patches 
are released. Also to enhance the product some better versions are released. Maintenance is 
done to deliver these changes in the customer environment. 
All these phases are cascaded to each other in progress and are seen as flowing steadily downwards (like a 
waterfall) through the phases. The next phase is started only after the defined set of goals are achieved for 
the previous phase and it is signed off, so the name “Iterative Waterfall Model”. In this model, phases do 
not overlap. 
▪ Advantages: 
1 . Flexibility: Iterations permit adjustments based on feedback. 
2 . Early Delivery: Partial systems can be delivered incrementally. 
3 . Risk Management: Identifying and addressing issues early in the process. 
9 
▪ Disadvantages: 
1. Increased Complexity: The iterative nature can make the process more complex. 
2. Potential for Scope Creep: Frequent iterations may lead to scope changes. 
3. Resource Intensive: Continuous revisiting of phases may demand more resources. 
▪ Applications: 
The Iterative Waterfall Model is suitable for projects with evolving or unclear requirements. Suitable for 
commercial applications with defined requirements that evolve incrementally. 
3D .STUDY OF THE SYSTEM 
Modules: The modules used in this software are as follows: 
1. Register/Login: JWT and cookies for session management. 
2. Products: RESTful APIs allow for product CRUD operations by sellers. 
3. Cart: Synchronized with backend to retain state across devices. 
4. Orders: Orders are placed post-payment and stored in MongoDB. 
5. Admin: Role-based access control for user/product moderation. 
Admin Dashboard: Here the Admin can manage courses and user roles. 
3E.INPUT AND OUTPUT 
The main inputs, outputs and the major function the details are: 
INPUT: 
User credentials, product data, cart actions, and payment details. 
OUTPUT: 
Confirmation emails, payment receipts, success/failure alerts, product displays. 
10 
3F.SOFTWARE REQUIREMENT SPECIFICATIONS 
Software Requirements Specification provides an overview of the entire project. It is a description of a 
software system to be developed, laying out functional and non-functional requirements. The software 
requirements specification document enlists enough necessary requirements that are required for the 
project development. To derive the requirements we need to have a clear and thorough understanding of 
the project to be developed. This is prepared after detailed communication with the project team and the 
customer. 
The developer is responsible for: 
● Developing the system, which meets the SRS and solves all the requirements of the system. 
● Demonstrating the system and installing the system at the client’s location after acceptance testing 
is successful. 
● Submitting the required user manual describing the system interfaces to work on it and also the 
documents of the system. 
Functional Requirements: 
A. User Registration and Authentication: 
1. Users should be able to create accounts securely. 
2. The system should authenticate users and manage login sessions. 
B. Browse and Search: 
1. Users should be able to browse and search for courses. 
. 
C. Courses Display: 
1. Each Student should have detailed and up-to-date items with prices. 
2. Users should be able to view courses, helpful educational videos. 
3. High Availability 
4. Scalability 
5. Responsive UI 
Hardware Requirements: 
1 . Computer has Intel I7 Processor 4 . 
16 GB RAM 
3. 1 TB-SSD-ROM Drive 
11 
Software Requirements: 
Node.js 18+, MongoDB Atlas, React 19, Vite, Cloudinary, Stripe 
3G.SOFTWARE ENGINEERING PARADIGM APPLIED 
Software paradigms refer to the methods and steps, which are taken while designing the software. There 
are many methods proposed and are in work today, but we need to see where in software engineering these 
paradigms stand. These can be combined into various categories, though each of them is containedin one 
another. 
The programming paradigm is a subset of Software design paradigm which is further a subset of the 
Software development paradigm. 
There are two levels of reliability. The first is meeting the right requirements. A careful and thorough 
systems study is needed to satisfy this aspect of reliability. The second level of systems reliability involves 
the actual work delivered to the user. At this level, the system’s reliability is interwoven with software 
engineering and development. 
There are three approaches to reliability. 
adopts a hybrid paradigm: - MVC for backend - Component-based for frontend - RESTful APIs and separation of concerns between layers 
12 
4.  SYSTEM DESIGN 
4A. DATA FLOW DIAGRAM 
A data flow diagram (DFD) is a graphical representation of the "flow" of data through an information system, 
modeling its process aspects. A DFD is often used as a preliminary step to create an overview of the system, 
which can later be elaborated. 
DFD can also be used for the visualization of data processing (structured design). A 
DFD shows what kind of information will be input to and output from the system, where the data will come 
from and go to, and where the data will be stored. It does not show information about the timing of the process 
or information about whether processes will operate in sequence or in parallel (which is shown on a flowchart). 
This context-level DFD is next "exploded", to produce a Level 1 DFD that shows 
some of the detail of the system being modeled. The Level 1 DFD shows how the system is divided into sub- 
systems (processes), each of which deals with one or more of the data flows to or from an external agent, and 
which together provide all of the functionality of the system as a whole. It also identifies internal data stores that 
must be present for the system to do its job and shows the flow of data between the various parts of the system. 
Data flow diagrams are one of the three essential perspectives of the structured- 
systems analysis and design method SSADM. The sponsor of a project and the end users will need to be briefed 
and consulted throughout all stages of a system's evolution. With a data flow diagram, users can visualize how 
the system will operate, what the system will accomplish, and how the system will be implemented. The old 
system's data-flow diagrams can be drawn up and compared with. 
How any system is developed can be determined through a data flow diagram model. In the course of developing 
a set of leveled data flow diagrams, the analyst/designer is forced to address how the system may be decomposed 
into component sub-systems and to identify the transaction data in the data model. Data flow diagrams can be 
used in both the Analysis and Design phase of the SDLC. There are different notations to draw data flow 
diagrams. Defining different visual representations for processes, data stores, data flow, and external entities. 
DFD Notation: 
13 
Function 
DFD Example: 
File / Database 
Flow 
Input / Output 
Database  Input Output 
Steps to Construct Data Flow Diagram: 
Four Steps are generally used to construct a DFD. 
Process should be named and referred for easy reference. Each name should be 
representative of the reference. 
The destination of flow is from top to bottom and from left to right. 
When a process is distributed into lower-level details they are numbered. 
The names of data stores, sources, and destinations are written in capital letters. 
Rules for constructing a Data Flow Diagram: 
Arrows should not cross each other. 
14 
Squares, Circles, and Files must bear a name. 
Decomposed data flow squares and circles can have the same names. 
Draw all data flow around the outside of the diagram. 
● LEVEL 0 DFD OR CONTEXT DIAGRAM: 
● LEVEL 1 DFD: 
15 
4B.SEQUENCE DIAGRAM 
A Sequence diagram is an interaction diagram that shows how processes operate with one another and 
what is their order. It is a construct of a Message Sequence Chart. A sequence diagram shows object 
interactions arranged in a time sequence. It depicts the objects and classes involved in the scenario and the 
sequence of messages exchanged between the objects needed to carry out the functionality of the scenario. 
Sequence diagrams are typically associated with use case realizations in the Logical View of the system 
under development. 
16 
Sequence diagrams are sometimes called event diagrams or event scenarios. 
A sequence diagram shows, as parallel vertical lines (lifelines), different processes 
or objects that live simultaneously, and, as horizontal arrows, the messages exchanged between them, in 
the order in which they occur. This allows the specification of simple runtime scenarios in a graphical 
manner. 
A sequence diagram is the most common kind of interaction diagram, which 
focuses on the message interchange between several life lines .A sequence diagram describes an interaction 
by focusing on the sequence of messages that are exchanged, along with their corresponding occurrence 
specifications on the lifelines. 
The following nodes and edges are typically drawn in a UML sequence diagram: lifeline, execution 
specification, message, fragment, interaction, state invariant, continuation, and destruction occurrence. 
A Use case diagram at its simplest is a representation of a user's interaction with the system that shows the 
relationship between the use rand the different use cases in which the user is involved. A use case diagram 
can identify the different types of users of a system and the different use cases and will often be 
accompanied by other types of diagrams as well. 
So only static behavior is not sufficient to model a system rather dynamic behavior is 
more important than static behavior. In UML there are five diagrams available to model dynamic nature 
and a use case diagram is one of them. Now as we have to discuss that the use case diagram is dynamic in 
nature there should be some internal or external factors for making the interaction. 
17 
These internal and external agents are known as actors. So, use case diagrams consist of 
actors, use cases, and their relationships. The diagram is used to model the system/subsystem of an 
application. A single-use case diagram captures a particular functionality of a system. 
So, to model the entire system numbers of use case diagrams are used. The purpose of a 
use case diagram is to capture the dynamic aspect of a system. But this definition is too generic to describe 
the purpose. 
Because the other four diagrams (activity, sequence, collaboration, and State chart) are also having the 
same purpose. So, we will look into some specific purpose that will distinguish it from the other four 
diagrams. 
Use case diagrams are used to gather the requirements of a system including internal and 
external influences. These requirements are mostly design requirements. So, when a system is analyzed to 
gather its functionalities use cases are prepared and actors are identified. 
Now when the initial task is complete use case diagrams are modeled to present the outside view. So, in 
brief, the purposes of use case diagrams can be as follows: 
Used to gather requirements of a system. 
Used to get an outside view of a system. 
Identify external and internal factors influencing the system. 
18 
How to draw Use Case Diagram? 
Use case diagrams are considered for high level requirement analysis of a system. So, when the requirements 
of a system are analyzed, the functionalities are captured in use cases. 
So, we can say that uses cases are nothing but the system functionalities written in an organized manner. 
Now the second things which are relevant to the use cases are the actors. Actors can be defined as 
something that interacts with the system. 
The actors can be human user, some internal applications or may be some external applications. So, in a brief 
when we are planning to draw use case diagram, we should have the following items identified. 
Functionalities to be represented as a use case 
Actors 
Relationships among the use cases and actors. 
Use case diagrams are drawn to capture the functional requirements of a system. So, after identifying the 
above items we have to follow the following guidelines to draw an efficient use case diagram. 
The name of a use case is very important. So, the name should be chosen in such a way so that 
it can identify the functionalities performed. 
Give a suitable name for actors. 
Show relationships and dependencies clearly in the diagram. 
Do not try to include all types of relationships. Because the main purpose of the diagram is 
to identify requirements. 
Use note whenever required to clarify some important point 
25 
4D.SCHEMA DIAGRAM 
The schema is an abstract structure or outline representing the logical view of the database as a whole. 
Defining categories of data and relationships between those categories, database schema design makes 
data much easier to retrieve, consume, manipulate, and interpret. 
DB schema design organizes data into separate entities, determines how to 
create relationships between organized entities, and influences the applications of constraints on data. 
Designers create database schema to give other database users, such as programmers and analysts, a logical 
understanding of data. 
● SCHEMA DESIGN: 
5.  UI SNAPSHOT 
❖ FRONTEND : - 
1)  Login Page: 
import User from "../models/User.js"; 
import bcrypt from 'bcryptjs'; 
import jwt from 'jsonwebtoken'; 
// Register User : /api/user/register 
export const register = async (req, res)=>{ 
26 
try { 
const { name, email, password } = req.body; 
if(!name || !email || !password){ 
return res.json({success: false, message: 'Missing Details'}) 
} 
const existingUser = await User.findOne({email}) 
if(existingUser) 
return res.json({success: false, message: 'User already exists'}) 
const hashedPassword = await bcrypt.hash(password, 10) 
const user = await User.create({name, email, password: hashedPassword}) 
const token = jwt.sign({id: user._id}, process.env.JWT_SECRET, {expiresIn: '7d'}); 
res.cookie('token', token, { 
httpOnly: true, // Prevent JavaScript to access cookie 
secure: process.env.NODE_ENV === 'production', // Use secure cookies in production 
sameSite: process.env.NODE_ENV === 'production' ? 'none' : 'strict', // CSRF protection 
maxAge: 7 * 24 * 60 * 60 * 1000, // Cookie expiration time 
}) 
return res.json({success: true, user: {email: user.email, name: user.name}}) 
} catch (error) { 
console.log(error.message); 
res.json({ success: false, message: error.message }); 
} 
27 
} 
// Login User : /api/user/login 
export const login = async (req, res)=>{ 
try { 
const { email, password } = req.body; 
if(!email || !password) 
return res.json({success: false, message: 'Email and password are required'}); 
const user = await User.findOne({email}); 
if(!user){ 
return res.json({success: false, message: 'Invalid email or password'}); 
} 
const isMatch = await bcrypt.compare(password, user.password) 
if(!isMatch) 
return res.json({success: false, message: 'Invalid email or password'}); 
const token = jwt.sign({id: user._id}, process.env.JWT_SECRET, {expiresIn: '7d'}); 
res.cookie('token', token, { 
httpOnly: true, 
secure: process.env.NODE_ENV === 'production', 
sameSite: process.env.NODE_ENV === 'production' ? 'none' : 'strict', 
maxAge: 7 * 24 * 60 * 60 * 1000, 
}) 
28 
return res.json({success: true, user: {email: user.email, name: user.name}}) 
} catch (error) { 
console.log(error.message); 
res.json({ success: false, message: error.message }); 
} 
} 
// Check Auth : /api/user/is-auth 
export const isAuth = async (req, res)=>{ 
try { 
const { userId } = req.body; 
const user = await User.findById(userId).select("-password") 
return res.json({success: true, user}) 
} catch (error) { 
console.log(error.message); 
res.json({ success: false, message: error.message }); 
} 
} 
// Logout User : /api/user/logout 
export const logout = async (req, res)=>{ 
try { 
res.clearCookie('token', { 
httpOnly: true, 
secure: process.env.NODE_ENV === 'production', 
sameSite: process.env.NODE_ENV === 'production' ? 'none' : 'strict', 
}); 
return res.json({ success: true, message: "Logged Out" }) 
29 
} catch (error) { 
console.log(error.message); 
res.json({ success: false, message: error.message }); 
} 
} 
import jwt from 'jsonwebtoken'; 
// Login Seller : /api/seller/login 
export const sellerLogin = async (req, res) =>{ 
try { 
const { email, password } = req.body; 
if(password === process.env.SELLER_PASSWORD && email === process.env.SELLER_EMAIL){ 
const token = jwt.sign({email}, process.env.JWT_SECRET, {expiresIn: '7d'}); 
res.cookie('sellerToken', token, { 
30 
httpOnly: true, 
secure: process.env.NODE_ENV === 'production', 
sameSite: process.env.NODE_ENV === 'production' ? 'none' : 'strict', 
maxAge: 7 * 24 * 60 * 60 * 1000, 
}); 
return res.json({ success: true, message: "Logged In" }); 
}else{ 
return res.json({ success: false, message: "Invalid Credentials" }); 
} 
} catch (error) { 
console.log(error.message); 
res.json({ success: false, message: error.message }); 
} 
} 
// Seller isAuth : /api/seller/is-auth 
export const isSellerAuth = async (req, res)=>{ 
try { 
return res.json({success: true}) 
} catch (error) { 
console.log(error.message); 
res.json({ success: false, message: error.message }); 
} 
} 
// Logout Seller : /api/seller/logout 
export const sellerLogout = async (req, res)=>{ 
try { 
res.clearCookie('sellerToken', { 
httpOnly: true, 
31 
secure: process.env.NODE_ENV === 'production', 
sameSite: process.env.NODE_ENV === 'production' ? 'none' : 'strict', 
}); 
return res.json({ success: true, message: "Logged Out" }) 
} catch (error) { 
console.log(error.message); 
res.json({ success: false, message: error.message }); 
} 
} 
32 
 
8 - G,Croclf'y Home 
 
 
 
 
 
Freshness You Can 
Trust-, Savings You 
will Love! 
All Produc't Con'tact 
 
Explore deols 
 
 
Ca-tegories 
 
  
 ---  
 
 
 
"\ 
..... 
Orgonlc: veggie• 
 
 
 
Bokery &.Breod• 
f=re•h F=rvlt• 
 
 
Cold Drink• Dairy Product• 
 
 
Bes-t Sellers 
 
  
Po+ai"oSOOg 
**** 
$20 $7'5 \-?Acid 
 
Applelkg 
**** (  ) 
$42 $50 '\:?Add 
 
 
 
Amul MilklL 
. ..................................... 4) 
 
 
 
Maggie 10 packs 
. ........................................ (4) 
 
 
Pepsi lL 
. .................................... 4) 
 
$40$50 "t'.-? Add 
 
$7 ..9-0 'I;., Add $54  $66  
 
 
 
Why We Are 1-he Bes-t? 
Fast-esf' Delivery 
Freshness Guorant-eed 
Fre h prodvc  ,tralght from thQ ource 
Affordable Prices 
Ctvolity groc enes ot unbeatable pr1< es. 
Trusf'ed by Thousands 
Loved by 10.000+ hcippy u t ,mer 
 
 
Never Miss a Deal! 
Subscribe +o gei" 'the lai"esi" offers. new arrivals. and exclusive discoun+s 
 
 
 
l r er  yo  r e1nu1I Id Subscribe 
 
 
 
 
 
GGrocify 
 
Wedeliver fresh groceries ondsnacks straight to your 
d
o
o
r
. 
T
r
u
s
t
e
d 
by thousands. we oim to make 
your 
• hopping experience simple ond 
offordoble. 
Need help? 
QuickLinks 
Homo  Bost Sellars 
0-ff"or•&. Dool• Contact Us 
Dollvory lnformotion 
Return &.. Refund 
Polley Payment 
Mothods Track your 
Order Contoc:t Us 
Follow Us 
lnstogrom 
F
o
c
e
b
o
o
k 
V
o
u
T
u
b
e 
Copyright 2025 c. Team  Grocify.dev All Right Reserved, 
import Order from "../models/Order.js"; 
import Product from "../models/Product.js"; 
import stripe from "stripe" 
import User from "../models/User.js" 
// Place Order COD : /api/order/cod 
export const placeOrderCOD = async (req, res)=>{ 
try { 
const { userId, items, address } = req.body; 
if(!address || items.length === 0){ 
return res.json({success: false, message: "Invalid data"}) 
} 
// Calculate Amount Using Items 
let amount = await items.reduce(async (acc, item)=>{ 
const product = await Product.findById(item.product); 
return (await acc) + product.offerPrice * item.quantity; 
}, 0) 
// Add Tax Charge (2%) 
amount += Math.floor(amount * 0.02); 
await Order.create({ 
userId, 
items, 
amount, 
address, 
paymentType: "COD", 
}); 
return res.json({success: true, message: "Order Placed Successfully" }) 
} catch (error) { 
return res.json({ success: false, message: error.message }); 
} 
} 
// Place Order Stripe : /api/order/stripe 
export const placeOrderStripe = async (req, res)=>{ 
try { 
const { userId, items, address } = req.body; 
const {origin} = req.headers; 
if(!address || items.length === 0){ 
return res.json({success: false, message: "Invalid data"}) 
} 
let productData = []; 
// Calculate Amount Using Items 
let amount = await items.reduce(async (acc, item)=>{ 
const product = await Product.findById(item.product); 
productData.push({ 
name: product.name, 
price: product.offerPrice, 
quantity: item.quantity, 
34 
}); 
return (await acc) + product.offerPrice * item.quantity; 
}, 0) 
// Add Tax Charge (2%) 
amount += Math.floor(amount * 0.02); 
const order = await Order.create({ 
userId, 
items, 
amount, 
address, 
paymentType: "Online", 
}); 
// Stripe Gateway Initialize 
const stripeInstance = new stripe(process.env.STRIPE_SECRET_KEY); 
// create line items for stripe 
const line_items = productData.map((item)=>{ 
return { 
price_data: { 
currency: "usd", 
product_data:{ 
name: item.name, 
}, 
unit_amount: Math.floor(item.price + item.price * 0.02) * 100 
}, 
quantity: item.quantity, 
} 
}) 
// create session 
const session = await stripeInstance.checkout.sessions.create({ 
line_items, 
mode: "payment", 
success_url: `${origin}/loader?next=my-orders`, 
cancel_url: `${origin}/cart`, 
metadata: { 
orderId: order._id.toString(), 
userId, 
} 
}) 
return res.json({success: true, url: session.url }); 
} catch (error) { 
return res.json({ success: false, message: error.message }); 
} 
} 
// Stripe Webhooks to Verify Payments Action : /stripe 
export const stripeWebhooks = async (request, response)=>{ 
// Stripe Gateway Initialize 
const stripeInstance = new stripe(process.env.STRIPE_SECRET_KEY); 
35 
const sig = request.headers["stripe-signature"]; 
let event; 
try { 
event = stripeInstance.webhooks.constructEvent( 
request.body, 
sig, 
process.env.STRIPE_WEBHOOK_SECRET 
); 
} catch (error) { 
response.status(400).send(`Webhook Error: ${error.message}`) 
} 
// Handle the event 
switch (event.type) { 
case "payment_intent.succeeded":{ 
const paymentIntent = event.data.object; 
const paymentIntentId = paymentIntent.id; 
// Getting Session Metadata 
const session = await stripeInstance.checkout.sessions.list({ 
payment_intent: paymentIntentId, 
}); 
const { orderId, userId } = session.data[0].metadata; 
// Mark Payment as Paid 
await Order.findByIdAndUpdate(orderId, {isPaid: true}) 
// Clear user cart 
await User.findByIdAndUpdate(userId, {cartItems: {}}); 
break; 
} 
case "payment_intent.payment_failed": { 
const paymentIntent = event.data.object; 
const paymentIntentId = paymentIntent.id; 
// Getting Session Metadata 
const session = await stripeInstance.checkout.sessions.list({ 
payment_intent: paymentIntentId, 
}); 
const { orderId } = session.data[0].metadata; 
await Order.findByIdAndDelete(orderId); 
break; 
} 
default: 
console.error(`Unhandled event type ${event.type}`) 
break; 
} 
response.json({received: true}); 
} 
36 
// Get Orders by User ID : /api/order/user 
export const getUserOrders = async (req, res)=>{ 
try { 
const { userId } = req.body; 
const orders = await Order.find({ 
userId, 
$or: [{paymentType: "COD"}, {isPaid: true}] 
}).populate("items.product address").sort({createdAt: -1}); 
res.json({ success: true, orders }); 
} catch (error) { 
res.json({ success: false, message: error.message }); 
} 
} 
// Get All Orders ( for seller / admin) : /api/order/seller 
export const getAllOrders = async (req, res)=>{ 
try { 
const orders = await Order.find({ 
$or: [{paymentType: "COD"}, {isPaid: true}] 
}).populate("items.product address").sort({createdAt: -1}); 
res.json({ success: true, orders }); 
} catch (error) { 
res.json({ success: false, message: error.message }); 
} 
} 
import User from "../models/User.js" 
// Update User CartData : /api/cart/update 
export const updateCart = async (req, res)=>{ 
try { 
const { userId, cartItems } = req.body 
await User.findByIdAndUpdate(userId, {cartItems}) 
res.json({ success: true, message: "Cart Updated" }) 
37 
} catch (error) { 
console.log(error.message) 
res.json({ success: false, message: error.message }) 
} 
} 
import Address from "../models/Address.js" 
// Add Address : /api/address/add 
export const addAddress = async(req, res)=>{ 
try { 
const { address, userId } = req.body 
await Address.create({...address, userId}) 
res.json({success: true, message: "Address added successfully"}) 
} catch (error) { 
console.log(error.message); 
res.json({ success: false, message: error.message }); 
} 
} 
// Get Address : /api/address/get 
export const getAddress = async(req, res)=>{ 
try { 
const { userId } = req.body 
const addresses = await Address.find({userId}) 
res.json({success: true, addresses}) 
} catch (error) { 
console.log(error.message); 
res.json({ success: false, message: error.message }); 
} 
} 
38 
39 
 
GGrocify Home 
 
 
 
 
 
MY ORDERS 
All Product Contact 
 
 
 
 
Orderld: 68637539d2bl2178486ff24b 
 
 
PotatoS00g 
Category: Vegetables 
Payment: COD 
 
 
Quantity: 2 
Status: Order Placed 
Date: 7/1/2025 
Total Amount: $412 
 
 
 
Amount: $40 
 
 
 
Quantity: l 
• Coca-Cola Original Taste Soft Status: Order Amount: 
Drink PET Bottle (2.25 L) Placed $89 
Category: Drinks Date: 
7/1/2025 
 
 
Pringles Original Chips Quantity: l 
Status: Order Amount: 
(107 g) Placed $105 
Category: Instant Date:7/1/2025 
 
 
Too Yumm! Karare Noodle Quantity: l 
Status: Order Amount: 
Mascia Chips (67 g) Placed $15 
Category: Instant Date: 7/1/2025 
 
 
Lay's Tomato Tango Chips (3 Quantity: l 
Status: Order Amount: 
x82g) Placed $115 
Category: Instant Date: 7/1/2025 
 
 
Pepsi ll 
Category: Drinks 
Quantity: l 
Status: Order Placed 
Date: 7/1/2025 
 
Amount: $40 
II 
I 
 
import cookieParser from 'cookie-parser'; 
import express from 'express'; 
import cors from 'cors'; 
import connectDB from './configs/db.js'; 
import 'dotenv/config'; 
import userRouter from './routes/userRoute.js'; 
import sellerRouter from './routes/sellerRoute.js'; 
import connectCloudinary from './configs/cloudinary.js'; 
import productRouter from './routes/productRoute.js'; 
import cartRouter from './routes/cartRoute.js'; 
import addressRouter from './routes/addressRoute.js'; 
import orderRouter from './routes/orderRoute.js'; 
import { stripeWebhooks } from './controllers/orderController.js'; 
 
const app = express(); 
const port = process.env.PORT || 4000; 
 
await connectDB() 
await connectCloudinary() 
 
// Allow multiple origins 
const allowedOrigins = ['http://localhost:5173', ''] 
 
app.post('/stripe', express.raw({type: 'application/json'}), stripeWebhooks) 
 
// Middleware configuration 
app.use(express.json()); 
app.use(cookieParser()); 
app.use(cors({origin: allowedOrigins, credentials: true})); 
 
 
app.get('/', (req, res) => res.send("API is Working")); 
app.use('/api/user', userRouter) 
app.use('/api/seller', sellerRouter) 
app.use('/api/product', productRouter) 
app.use('/api/cart', cartRouter) 
app.use('/api/address', addressRouter) 
app.use('/api/order', orderRouter) 
 
app.listen(port, ()=>{ 
console.log(`Server is running on http://localhost:${port}`) 
}) 
❖ BACKEND:- 
● Database - db.js: 
import mongoose from "mongoose"; 
const userSchema = new mongoose.Schema({ 
name: {type: String, required: true }, 
email: {type: String, required: true, unique: true}, 
password: {type: String, required: true }, 
cartItems: {type: Object, default: {} }, 
}, {minimize: false}) 
const User = mongoose.models.user || mongoose.model('user', userSchema) 
export default User 
6.  CONCLUSION 
demonstrates a comprehensive implementation of a modern, scalable e-commerce 
platform. Developed using the MERN stack (MongoDB, Express.js, React, Node.js) with 
modern tooling like Vite and Tailwind CSS, the project showcases best practices in both 
frontend and backend development. 
From a backend perspective, the project encapsulates secure user authentication, RESTful 
APIs, role-based access control, and integration with third-party services like Stripe for 
payments and Cloudinary for media hosting. The frontend is designed to be responsive, 
intuitive, and efficient, ensuring a smooth user experience across devices. 
One of the key strengths of is its modular structure—each component (users, sellers, 
products, orders, payments) is cleanly separated and reusable, ensuring maintainability and 
scalability. Deployment via Vercel further highlights the use of modern DevOps practices, 
enabling CI/CD and seamless cloud integration. 
This project not only fulfills academic or training requirements but also lays the 
groundwork for real-world e-commerce solutions. It offers a strong base that can be 
extended into a production-grade application with additional features and enhancements. 
7. FUTURE SCOPE & FURTHER ENHANCEMENTS 
❖ Future Scope 
holds great potential for expansion and real-world deployment. Here are some strategic 
directions it could take: 
1. Mobile App Development: Develop a mobile-first experience using React Native, 
allowing users to shop on-the-go with native performance. 
2. Vendor Analytics: Integrate charts and data dashboards to help sellers track their 
performance, sales, and product popularity. 
3. Logistics Integration: Connect with APIs from logistics companies (e.g., Delhivery, 
Shiprocket) to enable order tracking and delivery status updates. 
4. AI Recommendations: Use machine learning models to recommend products based 
on user behavior and purchase history. 
5. Subscription Services: Implement recurring billing or membership plans for 
premium products or delivery services. 
❖ Further Enhancements 
1. User Experience Enhancements 
o Add Dark Mode and theme switching 
o Implement Voice-assisted product search and auto-complete suggestions 
2. Content & Learning Tools 
o Integrate guided tours for first-time users 
o Add tooltips, FAQs, and product comparison features 
3. Community Features 
o Add Product Reviews and User Ratings 
o Implement Q&A sections for users to engage with sellers 
4. Analytics & Progress Tracking 
o Live sales tracking dashboard for sellers and admins 
o Exportable sales reports (CSV, PDF) and order heatmaps 
5. Tech Integrations 
o Add Redis for caching frequent queries 
o Dockerize the application for container-based deployment 
o Integrate with CI/CD pipelines using GitHub Actions or GitLab CI 
o Deploy using Kubernetes for advanced scalability 
o Connect to email marketing tools like Mailchimp 
8.  BIBLIOGRAPHY 
1) www.w3schools.com 
2) www.youtube.com 
3) www.pexels.com
