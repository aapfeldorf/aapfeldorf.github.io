# Coding Uses

>Artifact use cases: Personal websites, simple web apps, data analysis

One common use case for Claude is generating code, without needing to know anything about programming yourself! In Artifacts, Claude can generate React code, which creates interactive interfaces that run directly in your browser. Interactive Artifacts act like mini apps that can range from calculators and visualizers to fun things like small games and personality tests.

As an example of what Claude can do with coding, we'll go over the process of creating a tool that calculates the unit prices for different products and tells you which one has the best value.

## Getting Familiar With The Tools

Before diving into a full project, try making a small Artifact to get used to the Claude interface. In the chat box, type **"Make a small tool that multiplies two numbers from my input."** Once Claude finishes generating, you should see an Artifact like the one below:
![Claude window showing the conversation that generated an Artifact](https://hackmd.io/_uploads/SJGJBKKTJx.png)
Feel free to test it out and ask follow-up questions before moving on.

## Creating a Unit Price Calculator

Let's say you're shopping and you want to buy some cookies. You have plenty of options, but you can't tell which has the cheapest price per cookie. Luckily, Claude can make you an Artifact for that exact purpose! By the end of this example, Claude will generate the code seen on the left of the image below, which corresponds to the artifact on the right.
![A screenshot of the Claude Artifact interface. The left shows the code for the artifact, and the right shows the preview of the Artifact from the code.](https://hackmd.io/_uploads/Bks7mTfCyg.png)

### 1. Single Item Calculator

In a new Claude chat, type **"Create a calculator where I can enter the quantity and price for a product and automatically get the price per item."** Including "quantity and price" tells Claude exactly what you want to put in, and "price per item" tells Claude how you want the output. With that information, it should produce an Artifact like this:
![Screenshot of the Claude interface showing an artifact titled "Price Per Item Calculator". It has fields to input quantity and total price, a calculate button, and an area where it shows the calculated price per item.](https://hackmd.io/_uploads/Bk2ejKFaJg.png)
With this Artifact, a basic web app, you can calculate the unit price of a single product.

### 2. Multiple Items

Now, we'll ask Claude to modify the Artifact to work with multiple products at the same time. In the same chat, type **"Add the ability to add more than one product and calculate the price per item for each of them."** Claude will modify the Artifact like this:
![Screenshot of the Claude interface showing the calculator artifact with multiple items and a button to add new items](https://hackmd.io/_uploads/HyAA6tKpJg.png)
In this new version, you can add and remove products like we wanted to. Claude also made it possible to change the name of products, so you know exactly which ones you're looking at. However, it still requires you to click calculate for each individual product, which can get annoying. Let's get Claude to fix that.

### 3. Removing Individual Calculate Buttons

Instead of having a calculate button for each product, it would be easier if there was one button that calculated everything. Type **"Combine the calculate buttons into one calculate button that works for every product."**
![Screenshot of the Claude interface showing the calculator artifact that has been modified with a "Calculate All Prices" button](https://hackmd.io/_uploads/rkl5Olqta1x.png)
Success! Now you only have to click the calculate button once after you change the products.

### 4. Comparing Unit Prices

For our last update, let's make the calculator highlight the product with the lowest unit so we know which one to buy.
![Screenshot of the Claude interface showing the calculator artifact with two products, "Vanilla Dream" and "Chocolate Nightmare". Vanilla Dream has a price per item of \$0.53 and Chocolate Nightmare has a price per item of \$0.50. Chocolate Nightmare is highlighted green with the label "BEST VALUE".](https://hackmd.io/_uploads/SyVdphGRyg.png)
Now we see that buying Chocolate Nightmare is the best value, since it's $0.50 per cookie compared to $0.53 per cookie.

## Next Steps

Although this unit price calculator is all we intended to create, there's no reason you have to stop here. Maybe you want the calculator to convert units so it works with weight or volume, or change the design to a cookie theme. Experiment with any ideas you think of, and you may be surprised at what you can create.