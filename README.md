# Frontend Mentor - FAQ accordion solution

This is a solution to the [FAQ accordion challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-wyfFdeBwBz). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- Hide/Show the answer to a question when the question is clicked
- Navigate the questions and hide/show answers using keyboard navigation alone
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![Desktop](/Screenshot.png)
![Mobile](/Screenshot2.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/DevouraStudio/FAQ-Accardion-Project)
- Live Site URL: [Add live site URL here](https://devourastudio.github.io/FAQ-Accardion-Project/)

## My process

### Built with

- Semantic HTML5 markup and boilerplate
- CSS custom properties
- Flexbox
- CSS media queries
- Desktop-first workflow
- [Bootstrap](https://getbootstrap.com/) - CSS framework

### What I learned

I acquired a substantial amount of valuable knowledge through this project. I gained proficiency in using modern Bootstrap accordions effectively and in customizing them in a professional and creative manner, striving to achieve a high level of expertise.

I also encountered challenges related to margins and paddings, which proved to be highly instructive and facilitated the development of responsive code. Through this experience, I enhanced my proficiency in applying CSS measurement units, such as viewport height (vh) and rem, more accurately than before.

Furthermore, I was able to effectively manage and refine the responsiveness of the code, successfully navigating the complexities of this project as a beginner.


```html
<button class="accordion-button bg-transparent" type="button" data-bs-toggle="collapse"
						data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
```
```css
@media (min-width: 375px) and (max-width: 1200px) {
	body {
		background-image: url(background-pattern-mobile.svg);
		background-size: contain;
		background-repeat: no-repeat;
		background-position: top center;
		margin: 10rem 2rem;
		height: max-content;
		padding: 0;
	}
}
.accordion-button.collapsed::after {
	background-image: url(icon-plus.svg);
	background-size: 30px;
	padding-left: 2rem;
	padding-bottom: 2rem;
	margin-left: auto;
}

.accordion-button:not(.collapsed)::after {
	background-image: url(icon-minus.svg);
	background-size: 30px;
	padding-left: 2rem;
	padding-bottom: 2rem;
	margin-left: auto;
}
```

### Continued development

"Moving Forward, I Aim To Advance My Expertise In Bootstrap, Enabling Me To Develop Projects Independently Without Relying On Documentation, And To Deliver Work Of Higher Quality And Sophistication.

Furthermore, Mastering Code Responsiveness Remains A Crucial Objective. By Enhancing My Skills In Both CSS And Bootstrap, I Intend To Implement Responsive Designs With Greater Efficiency And Precision.

Finally, Achieving A Comprehensive Understanding Of CSS Measurement Units Is Essential For Writing Accurate And Maintainable Code. I Plan To Deepen My Knowledge In This Area To Apply These Concepts More Effectively In Future Projects."

### Useful resources

- [MDN](https://developer.mozilla.org/en-US/) - "During This Project, I Frequently Referred to the Mozilla Developer Network (MDN) Website as a Trusted Resource for Learning and Clarifying HTML, CSS, and JavaScript. MDN Provided Clear Documentation, Practical Examples, and Best Practices That Helped Me Solve Challenges More Efficiently. Using MDN Not Only Improved My Technical Accuracy but Also Strengthened My Confidence in Applying Modern Web Standards to My Work."

- [ChatGPT](https://www.chatgpt.com/) - "Throughout This Project, I Benefited Greatly From the Guidance and Support Provided by ChatGPT. From Explaining Complex HTML, CSS, and Bootstrap Concepts to Offering Practical Code Examples and Debugging Advice, ChatGPT Helped Me Overcome Challenges More Efficiently. It's Clear Explanations and Creative Suggestions Played a Key Role in Improving My Skills, Building My Confidence, and Ensuring the Project’s Overall Quality."

- [Bootstrap](https://getbootstrap.com/) - "In This Project, I Utilized Bootstrap to Streamline the Design Process and Enhance the Visual Appeal of My Pages. By Leveraging Bootstrap’s Pre-Built Components, Utility Classes, and Customization Options, I Was Able to Maintain Consistent Styling, Organize Content Effectively, and Apply Modern Web Design Techniques More Efficiently. Using Bootstrap Helped Me Focus on Creativity and Attention to Detail While Building the Project."

- [Gemini](https://gemini.google.com/) - "Google Gemini greatly assisted me in this coding project by providing guidance on Bootstrap and CSS. It helped me troubleshoot issues, explore creative customization options for accordions, and apply measurement units like vh and rem effectively, making my code more responsive and professional."

## Author

- Website - [DevouraStudio](https://www.devoura.ir)
- Frontend Mentor - [@DevouraStudio](https://www.frontendmentor.io/profile/DevouraStudio)
- Dribble - [@DevouraStudio](https://www.dribbble.com/DevouraStudio)
- Github - [@DevouraStudio](https://www.github.com/DevouraStudio)
- Codepen - [@DevouraStudio](https://www.codepen.io/DevouraStudio)
