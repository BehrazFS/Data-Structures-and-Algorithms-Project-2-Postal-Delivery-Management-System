# Data-Structures-and-Algorithms-Project-2-Postal-Delivery-Management-System

This project is a university-level implementation of a **postal parcel management system** designed using **core data structures**: queue, stack, min-heap, and linked list. It was developed as part of the *Data Structures and Algorithms* course (Term 14021) under the supervision of Dr. Mirroshandel at the University of Guilan.

## 🎯 Objective

The goal of this project is to give students practical experience with data structures by designing a real-world system for managing the lifecycle of postal packages in a post office environment.

## 🛠 Features

* **Parcel Registration**: Receives parcel details, assigns a random 6-digit tracking code, and stores the parcel in a **queue** for pending deliveries.
* **Parcel Dispatching**: Supports two dispatching strategies:

  * FIFO (first-in queue)
  * Nearest destination using a **min-heap** based on distance.
* **Status Updates**: Manually update parcel status with each update stored in a **stack**. Once marked as "Delivered", no further updates are allowed.
* **Parcel Tracking**: Retrieve current and previous statuses of any parcel by tracking code.
* **Parcel Archiving**: After delivery, parcels are stored in a **linked list** archive searchable by tracking code.
* Some additional features were also implemented
