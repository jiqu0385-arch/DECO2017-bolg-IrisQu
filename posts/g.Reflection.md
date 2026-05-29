---
title: Final Reflection -- Evaluation of Liminal
date: 2026-05-30
author: Jingru Qu
---
## Introduction

Liminal was developed as an anonymous room-based chat platform designed to support temporary and low-pressure conversations between strangers. The concept was inspired by the idea of liminality, which refers to a transitional space between different states. Rather than creating a traditional social media platform with profiles, follower systems, and permanent identities, the project aimed to provide a softer communication experience where users could enter rooms, interact anonymously, and leave freely.

The final prototype allows users to browse rooms, create rooms, customise room backgrounds and categories, and communicate through text, images, music, and emojis. Throughout development, the project focused on creating a temporary and anonymous space where users could connect with others without the pressure of maintaining a permanent online identity.

This reflection evaluates the final prototype through performance, user experience, functional requirements, and future improvements. My evaluation primarily focuses on user experience observations gathered during testing while reflecting on how the final system compared to the original goals established during planning.

---
## Performance Evaluation

For the scale of the prototype, the overall performance was satisfactory. Users were able to browse rooms, create rooms, enter chat spaces, and send messages without significant delays. The interface remained responsive during testing and successfully supported the main user workflow.

Because the platform was developed using HTML, CSS, and JavaScript, the pages remained lightweight and relatively fast to navigate. Most user actions provided immediate visual feedback, helping users understand whether actions had been completed successfully.

To further evaluate the system, a Lighthouse audit was conducted using Google Chrome Developer Tools. The prototype achieved a performance score of 90 and an accessibility score of 100. These results indicate that the website performs efficiently during normal use and provides a strong foundation for usability and accessibility.

![Lighthouse](/images/lighthouse.png)

The Lighthouse results also aligned with observations from testing. Users were able to navigate between pages, create rooms, and communicate without major technical issues. This suggests that the system successfully met its basic performance requirements.

The variation in response time was primarily related to the platform’s reliance on external APIs rather than limitations within the front-end implementation itself. This meant that performance could fluctuate depending on network conditions and third-party service availability. While this did not prevent task completion, it influenced how responsive the system felt from a user perspective.

Overall, the evaluation suggests that the main challenges identified by users were not technical limitations but experience-related issues. Future development would therefore benefit more from improving communication and interaction flow than from major performance optimisation.

### Accessibility Reflection

The Lighthouse audit returned an accessibility score of 100, suggesting that the overall structure and navigation of the interface supported accessible use. However, accessibility should be viewed as an ongoing process rather than a completed task. Future iterations could further improve inclusivity by providing clearer guidance for first-time users and ensuring that important privacy information is communicated more visibly throughout the platform.

---
## User Experience Evaluation

The primary goal of Liminal was to create a comfortable anonymous environment that encouraged temporary interaction between strangers. Overall, testing suggested that the platform successfully communicated this concept.

### Testing Summary

![Evaluation evidence table](/images/Table.png)

One of the strongest aspects of the experience was the room-based structure. Users could browse different rooms through visual room cards rather than a simple text-based list. The combination of room names, categories, and customised backgrounds helped create distinct identities for each room and encouraged exploration.

The room creation feature also contributed positively to the user experience. Users appreciated being able to customise room names, room types, and background images before entering a conversation. This provided a sense of ownership while still maintaining anonymity.

Despite these strengths, testing revealed several opportunities for improvement.

One issue involved the music sharing feature. The platform allows users to search for and send music through an external API, helping users communicate through more than text alone. However, users noted that after sending a music track, the music panel remained open and had to be closed manually before returning to the chat. Although the feature worked correctly, this additional step interrupted the flow of interaction and made the experience feel less seamless.

Another recurring piece of feedback involved supporting information. Several users felt that the platform could include more pages beyond the core chat experience. Future versions could include pages such as About, Privacy Information, Community Guidelines, or Safety Information to help users better understand the platform and its purpose.

A third finding related to privacy communication. Liminal was designed around temporary anonymous interactions, and chat records are not intended to be stored as personal histories. However, users were not clearly informed of this before entering conversations. As a result, some participants were uncertain about what happened to their messages after leaving a room.

This issue was not caused by missing functionality but by a lack of communication. A simple notice explaining how messages are handled would help build trust and improve transparency.

Overall, the evaluation showed that the anonymous communication model and room-based structure successfully supported the intended user experience. At the same time, testing demonstrated that clearer communication and smoother interaction flow could further improve the platform.

---
## Retrospective Assessment of Functional Requirements

Looking back at the original project goals, the final prototype successfully implemented the main functional requirements, including room browsing, room creation, anonymous communication, room customisation, and media sharing through images and music.

However, testing revealed that some supporting elements were more important than originally anticipated. While the core communication features were successfully implemented, users placed considerable value on privacy communication, supporting information, and guidance throughout the platform.

This reflection highlighted that successful user experiences depend not only on providing features but also on helping users understand how those features work. As a result, my understanding of functional requirements expanded beyond technical implementation to include communication, transparency, and user support.

---
## Critical Reflection and Future Improvements

The most significant lesson I learned from this project is that user experience extends beyond functionality and visual design.

During development, much of the focus was placed on creating an engaging atmosphere through room customisation, visual design, and expressive communication features. These decisions successfully supported the concept of temporary anonymous interaction and helped establish a unique identity for the platform.

However, user testing revealed that clarity and communication are equally important. Some of the most valuable feedback was not related to adding new features but rather improving how existing features were presented and explained.

If development continued, I would prioritise three areas for improvement.

First, I would improve interaction flow by automatically closing the music panel after a successful send action.

Second, I would introduce supporting pages such as About, Privacy, Community Guidelines, and Safety Information to provide additional context and guidance.

Third, I would improve communication surrounding privacy and anonymity by clearly informing users that conversations are anonymous and that messages are not stored as personal histories.

These improvements would not fundamentally change the concept of Liminal. Instead, they would strengthen the existing experience by making it clearer, more transparent, and more user-friendly.

---
## Conclusion

Overall, Liminal successfully achieved its goal of creating an anonymous room-based communication platform that supports temporary and low-pressure interactions between strangers.

The project demonstrated that users could communicate through multiple forms of expression while maintaining anonymity and exploring different room environments. The room-based structure and expressive communication tools were particularly successful in supporting the intended concept.

At the same time, evaluation revealed opportunities to improve communication, interaction flow, and supporting content. The project reinforced my understanding that successful user experience design is not only about providing functionality but also about helping users understand, trust, and comfortably engage with the system.
