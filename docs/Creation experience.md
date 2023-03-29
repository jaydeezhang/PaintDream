# How to make a better creation experience for a data service SaaS product

Type: Case study

![Untitled](/Users/bytedance/my-website/docs/creation-img/How to make a better creation experience for a dat e0a3d70246de416387338c361fc8633b/Untitled.png)

<img src="static/img/fjord-Norway-hero.jpeg" />
![Example banner](/Users/bytedance/my-website/static/img/fjord-Norway-hero.jpeg)
<img
  src={require('/Users/bytedance/my-website/static/img/fjord-Norway-hero.jpeg').default}
  alt="Example banner"
/>

# Background

****What are we creating in a SaaS product?**** 

Creation experience in a SaaS product often means **creating objects and their properties**, which is always a key module of almost any SaaS product.

![Untitled](docs/creation-img/How to make a better creation experience for a dat e0a3d70246de416387338c361fc8633b/Untitled 1.png)

**This design case study is related to a SaaS product named `Edison`**

Edison is TikTok’s data service platform to store features for the entity(video, comment, user…), the main user groups for Edison are the back-end engineer, algorithm engineer, and data scientist.

 

![Untitled](docs/creation-img/How to make a better creation experience for a dat e0a3d70246de416387338c361fc8633b/Untitled 2.png)

# Insights: The key points for the Creation experience

The main component of a creation page is the `form`. There is a saying that goes well — **every user hates form**. Forms can be tedious and time-consuming for users, especially if they are long or complex. So as a user experience designer, I hope to make a creation experience easier to understand and straightforward. 

To design a form, it is important to keep the following points in mind:

1. **Avoid long forms**: long forms can be tedious and time-consuming for users.
2. **An orderly arrangement of information:** make it easier to understand and navigate.
3. **Simple logic:** Use simple logic to make the form straightforward and intuitive.
4. **Guide and feedback:** Provide users with guidance and feedback to help them understand the purpose of the form and how to complete it.

# Let’s get started designing a creation page for Edison

### Figure out the user flow of creating a feature

It is important to first figure out the user flow of creating a feature in order to design an effective creation page. By understanding the steps that users need to take to create a feature, designers can ensure that the form is organized in a logical and intuitive way. This can help to prevent users from becoming frustrated or confused, and can ultimately lead to a better user experience.

![Untitled](docs/creation-img/How to make a better creation experience for a dat e0a3d70246de416387338c361fc8633b/Untitled 3.png)

### **The first version was designed by RD and the optimized version**

The MVP version for the creation process is designed by RD. I found some interaction and UI issues and optimize them. 

![Untitled](docs/creation-img/How to make a better creation experience for a dat e0a3d70246de416387338c361fc8633b/Untitled 4.png)

**What did I do for this new version?**

1. Optimize the feature source selection page, the information utilization rate is extremely low on this page, so I `tile content options for the feature source selection page`.
2. Both `forward and reverse operations` can be satisfied.
3. Create `information hierarchy` and optimize UI quality

![Untitled](docs/creation-img/How to make a better creation experience for a dat e0a3d70246de416387338c361fc8633b/Untitled 5.png)

### Second round iteration for creation page — improve the usability

1. Avoid unnecessary steps, and shorten steps —— **Finally, we remove the steps component**
2. Cause the number of users has grown, we introduce a new editing mode, which could provide the user with two kinds of creative options —— **standard mode and SQL mode**. 
3. **Improve guidance** and consider the error states to provide feedback for users. 
4. **Create a productivity tool for inputting prefixes or suffixes**, in order to decrease the time cost of naming each feature. 

![Untitled](docs/creation-img/How to make a better creation experience for a dat e0a3d70246de416387338c361fc8633b/Untitled 6.png)

The iteration will continue…

# Extended Thinking

<aside>
💡 When I design the feature creation page, I also explored the design template for the creation page. Here I list three extended ideas about designing a great creation page for SaaS products.

</aside>

### Extended 1: Batch object creation `vs` single object creation

As I said at the beginning part, the essence of a creation page is creating an object and its attributes. There are two scenarios about the users’ daily tasks that we need to consider first before we start to design:

1. Users need to complete the configuration for several objects at the same time. In this case, it’s better to design a `batch object input interaction`. 
2. Users complete a single object or a few objects each time. In this case, we would better design a `form within a modal window`

![Untitled](docs/creation-img/How to make a better creation experience for a dat e0a3d70246de416387338c361fc8633b/Untitled 7.png)

For Edison’s use case, 

the users often **create multiple features each time**. Considering the behavior, I compare the two kinds of interaction ways and find the most suitable solutions for the users. 

![Untitled](docs/creation-img/How to make a better creation experience for a dat e0a3d70246de416387338c361fc8633b/Untitled 8.png)

![Untitled](docs/creation-img/How to make a better creation experience for a dat e0a3d70246de416387338c361fc8633b/Untitled 9.png)

### Extended 2: Use `Modal or drawer` as the container for the creation page

**The modal** could be used in these situations:

1. Form-like creation page with fewer steps and fewer form fields
2. Do not want to make a strong user interruption

**The drawer** could be used in these situations:

1. The creation page included some complicated input components, like a code editor, and an inline edit table.
2. Form-like creation page with multiple steps and a lot of form fields to fill in.
3. Includes an in-line edit table.

![Untitled](docs/creation-img/How to make a better creation experience for a dat e0a3d70246de416387338c361fc8633b/Untitled 10.png)

![Untitled](docs/creation-img/How to make a better creation experience for a dat e0a3d70246de416387338c361fc8633b/Untitled 11.png)

### Extended 3: Research the keyboard interaction for the inline edit table

Microsoft's official guidelines define the keyboard as such, designing a great keyboard experience allows users to efficiently navigate an application's UI and combine all its functions without having to have a built-in keyboard. In the user's focus on a certain process, the ability to access allows the user to concentrate, and does not need to install the task of using the keyboard separately, I think it is the perfect keyboard experience, so I think it is perfect keyboard usage habit on the desktop scene, is an important task for the employer.

Additionally, it is important to consider keyboard interactions when designing a form. Designing a great keyboard experience allows users to efficiently navigate an application's UI and combine all its functions without having to have a built-in keyboard. In the user's focus on a certain process, the ability to access allows the user to concentrate and does not need to install the task of using the keyboard separately, making it an important task for the employer.

[data:image/svg+xml,%3csvg%20xmlns=%27http://www.w3.org/2000/svg%27%20version=%271.1%27%20width=%27960%27%20height=%27600%27/%3e](data:image/svg+xml,%3csvg%20xmlns=%27http://www.w3.org/2000/svg%27%20version=%271.1%27%20width=%27960%27%20height=%27600%27/%3e)

[https://jz-design-space.super.site/_next/image?url=https%3A%2F%2Fsuper-static-assets.s3.amazonaws.com%2F32cd1b78-6935-48f5-817b-c49d58a0313c%2Fimages%2Fdfe99273-0e77-429f-a029-caaccdb14212.png&w=1920&q=80](https://jz-design-space.super.site/_next/image?url=https%3A%2F%2Fsuper-static-assets.s3.amazonaws.com%2F32cd1b78-6935-48f5-817b-c49d58a0313c%2Fimages%2Fdfe99273-0e77-429f-a029-caaccdb14212.png&w=1920&q=80)

# The benefits for the business team

The 1.0 version of Edison’s “Feature creation function” was launched on 11/2022

The 2.0 version was launched on 02/2023. 

Feature creation is only a small part of Edison's functions. The launch of this feature provides algorithm engineers with an efficient registration system for feature management, so as to realize the uniformity of feature caliber and various attribute fields, thereby improving their work efficiency.

![Untitled](docs/creation-img/How to make a better creation experience for a dat e0a3d70246de416387338c361fc8633b/Untitled 12.png)