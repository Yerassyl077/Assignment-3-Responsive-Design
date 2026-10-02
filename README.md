# Assignment 3: Responsive Web Design

**Name:** Nauryzgali Yerassyl
**Group:** IT-2513

---

## Part 1. Media Queries

### Task 0: Responsive Typography

**Description:** I created a section with a heading and a paragraph. Using pure CSS `@media` queries, I set different `font-size` values for mobile, tablet (`min-width: 768px`), and desktop (`min-width: 992px`) screens to ensure the typography is readable on any device.
<img width="1919" height="913" alt="photo_5332276849918287539_w" src="https://github.com/user-attachments/assets/fa6b115e-8561-427e-b1ab-3905ce9eac20" />


### Task 1: Responsive Layout with Media Queries

**Description:** I built a layout with three boxes using Flexbox. Without using any external frameworks, I applied CSS media queries to change the layout dynamically: the boxes stack vertically on mobile screens (100% width), display two in a row on tablets (50% width), and stand side-by-side on desktop screens (33.3% width).
<img width="1191" height="883" alt="photo_5332276849918287538_y" src="https://github.com/user-attachments/assets/3601328e-325a-469a-9b8e-fce7a0444e34" />


## Part 2. Bootstrap Grid System

### Task 2: Bootstrap Responsive Columns

**Description:** For this task, I used the Bootstrap 12-column grid system. By assigning classes like `col-12` (for mobile), `col-md-6` (for tablets), and `col-lg-4` (for desktops), the columns automatically rearrange themselves correctly without writing custom CSS media queries. 
<img width="800" height="743" alt="photo_5332276849918287537_x" src="https://github.com/user-attachments/assets/43f0d486-1f83-4286-9fec-932ce23d4737" />

### Task 3: Bootstrap Navigation Bar

**Description:** I implemented a responsive navigation bar using Bootstrap's `navbar` component. It features a logo on the left and navigation links on the right. On smaller screens, the links automatically hide and collapse into a toggleable hamburger menu, optimizing space for mobile users.
<img width="1144" height="926" alt="photo_5332276849918287534_y" src="https://github.com/user-attachments/assets/321bcef4-4658-4ac9-b9a2-251c6a90f0de" />


## Part 3. Combined Project

### Task 4: Responsive Portfolio Page

**Description:** I built a complete portfolio section combining both Media Queries and the Bootstrap Grid. The macro-layout uses the grid (`col-lg-8` for projects, `col-lg-4` for the sidebar) to arrange elements side-by-side on large screens and stack them on mobile. Additionally, I wrote custom media queries to hide the contact information entirely on screens smaller than 768px, ensuring the mobile view remains clean and uncluttered.
<img width="1919" height="930" alt="photo_5332276849918287535_w" src="https://github.com/user-attachments/assets/103f06a2-8e7b-482d-9210-457747789372" />


## Summary of Work Process
In this assignment, I successfully learned how to make web pages responsive. I practiced two different approaches: manually writing CSS Media Queries and utilizing the pre-built Bootstrap Grid system. I realized that Media Queries give precise control over specific elements (like typography or hiding particular blocks), while Bootstrap is incredibly fast and efficient for setting up overall page structures and complex components like collapsible navigation bars. Combining both techniques allowed me to create a highly adaptable and user-friendly portfolio layout.
