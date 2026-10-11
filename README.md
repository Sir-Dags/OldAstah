# 📐 Astah UML Activity Diagrams

A small collection of UML activity diagrams modeled in Astah UML, created while learning how to map out processes, decisions, and responsibilities visually before writing any code.

Proof of age:

![Proof](<Screenshot 2026-10-11 141322.png>)

---

## 🚀 Project Overview

This repository holds activity diagram work from CS1200, including individual practice diagrams and a Team 8 group project. The diagrams were used to practice:
* **Activity Flow Modeling:** Breaking real-world processes into clear, ordered action steps from an initial node to a final node.
* **Decision and Merge Nodes:** Branching a flow based on guard conditions such as `[Yes]`, `[No]`, `[Found Coffee]`, and `[No Coffee]`, then merging paths back together.
* **Fork and Join Nodes:** Modeling actions that can happen in parallel and syncing them back into a single flow.
* **Swimlanes:** Separating responsibilities between the user and the system so it is clear who performs each action.
* **Real-World System Design:** Applying UML to an online shopping experience with sign-in, guest checkout, subscriptions, payment, and order tracking.

---

## 📂 Directory Structure

```
.
├── CS1200Team8.asta                 # Team 8 project: example diagrams plus the online shopping flow
├── Example_Activity_Diagrams.asta   # Practice activity diagrams (beverage, cake, new user)
└── README.md                        # Project documentation and diagram summaries
```

---

## ⚙️ Requirements

| Requirement | Specification |
| :--- | :--- |
| **Modeling Tool** | Astah UML (files saved in Astah 9.1) |
| **File Format** | `.asta` |
| **Diagram Type** | UML Activity Diagrams |
| **License** | Astah offers a free student license for those with an academic email |

---

## 🛠️ Viewing the Diagrams

1. **Install** Astah UML (a free student license is available at astah.net/products/students).

2. **Open** any `.asta` file using File > Open.

3. **Browse** the diagrams from the Structure tree on the left side of the window.

---

## 🧭 Diagram Summaries

### Example 1: Enjoy Tasty Beverage (No Swimlanes)
A decision-based flow for making a drink.
* Look for coffee. If `[Found Coffee]`, put the filter in the coffee maker, add coffee and water, switch it on, wait for brewing to finish, and pour into a cup.
* If `[No Coffee]`, look for cola. If `[Found Cola]`, open the can. If `[No Cola]`, update the shopping list.
* Both paths end with enjoying a tasty beverage.

![BuyMeACoffee](<Screenshot 2026-10-11 141406.png>)

### Example 2: Bake A Cake (No Swimlanes)
A step-by-step process with a waiting condition.
* Gather ingredients and utensils, combine the cake mix, and pour batter into pans.
* Check if the oven is at temperature before placing the pans in the oven.
* Set a timer, wait, then remove the cake from the pan.
* Combine and spread the frosting, then place the completed cake in a box.

![TimeCake](<Screenshot 2026-10-11 141351.png>)

### Example 3: New User with Swimlanes
An account creation flow split between the user and the system.
* The user arrives at the home screen of the website as a new or returning customer.
* New users create an account by entering an email, password, address, phone number, and credit card number.
* The system checks that the information is correct, then notifies the user of their new account so they can sign in.

### Example 4: Online Shopping Flow (Team 8 Project)
A full e-commerce flow based on an Amazon-style store.
* The user starts at the home screen, browses shopping pages, and clicks on a product.
* The system checks if the user is signed in. If not, the user can sign in, create an account, or continue as a guest.
* The system checks whether the user has Amazon Prime, Kindle Unlimited, or another subscription before continuing to payment options.
* After checkout, the order number, shipping day, and delivery date are shown.
* The user can choose to track the package, view recently bought items, buy again, or go back.

![ShazamazonFlow](<Screenshot 2026-10-11 141434.png>)
---

## 📄 File Summary

| File / Folder | Purpose |
| :--- | :--- |
| `Example_Activity_Diagrams.asta` | Practice activity diagrams covering decisions, sequential processes, and swimlanes |
| `CS1200Team8.asta` | Team 8 project file containing the example diagrams plus the online shopping activity diagram |
| `README.md` | Repository documentation, viewing instructions, and diagram summaries |