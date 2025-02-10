# MCD_sentiment-analysis
Took the reviews from the mcd store across USA to understand the sentiments of the customers posting their reviews and positioning the product in the menu
Word Cloud Obtained after second iteration from python 



 


Table deriving the sentiment, interpretation and the insights from the Word Cloud.

Word	Sentiment	Descriptive Interpretation & Insights
food	Neutral/Negative	The word "food" is the most prominent, indicating that it is the primary concern for customers. If the sentiment is negative, it could point to issues with taste, freshness, portion sizes, or quality inconsistencies across outlets. If neutral, it suggests that customers are discussing food generally, without strong opinions.
look	Neutral	"Look" suggests that customers focus on visual appeal. This could relate to the presentation of meals, the cleanliness of the restaurant, or even the employees' appearance. A positive mention could indicate well-presented food, while a negative one might highlight unappetizing meals or unclean packaging.
spit	Negative	This word is alarming in the context of food service. It may refer to serious concerns about food hygiene, contamination fears, or extreme dissatisfaction. If customers are mentioning "spit," it could indicate mistrust in food handling practices and needs urgent investigation.
normal	Neutral/Negative	If customers describe food as "normal," it suggests a lack of excitement or innovation in the menu. While some may appreciate familiarity, others might find the food unremarkable and not worth returning for. This could indicate the need for occasional limited-time offers or creative menu enhancements.
someone	Neutral/Negative	Mentions of "someone" likely refer to interactions with staff members. If the sentiment is negative, it might imply complaints about rude or inattentive service. If neutral, it may indicate a discussion about a specific incident without strong feelings. Training in customer service may help improve this aspect.
everyone	Neutral/Positive	This word might refer to inclusivity and accessibility. Positive mentions could mean McDonald's is seen as a welcoming place for all. If neutral, customers may be referencing experiences that apply to all visitors, such as wait times or seating availability.
chill	Positive	This word indicates that some customers find McDonald's a relaxing or comfortable place to dine. It suggests that the atmosphere, seating, and overall environment may be conducive to casual dining, which is a positive aspect for retaining customers who enjoy socializing.
eat	Neutral	This generic term suggests discussions about the act of eating at McDonald's. If mentioned alongside positive words, it may indicate satisfaction. If used with negative terms, it could point to issues like difficulty enjoying meals due to food quality or ambiance.
transaction	Neutral/Negative	Customers referencing "transaction" may be discussing their payment experience. A negative mention could highlight slow service at the counter, malfunctioning payment systems, or issues with mobile ordering. Improving checkout speed and digital payment options may help.
polite	Positive	This word suggests positive customer service experiences. Customers likely appreciate courteous staff, and this could be a key factor in positive reviews. Reinforcing polite behavior through staff training may further enhance the customer experience.
think	Neutral	The word "think" suggests contemplation or mixed opinions. Customers may be reflecting on their experience, weighing pros and cons before forming a firm opinion. Encouraging customer feedback and acting on it could convert hesitant customers into loyal ones.
want	Neutral/Negative	This word suggests unmet expectations. Customers might be expressing desires for better food quality, improved service, healthier menu options, or specific promotions. Understanding what they "want" through surveys and reviews could guide business improvements.
dont	Negative	The presence of "dont" suggests dissatisfaction, as it often appears in negative statements (e.g., "don't like," "don't recommend"). This indicates that customers are vocal about their complaints, making it crucial for McDonald's to address common pain points.
milky	Neutral	This term likely refers to the texture or taste of drinks like milkshakes or coffee. Positive mentions could mean customers enjoy creamy textures, while negative ones might indicate dissatisfaction with consistency or overly diluted beverages.
white	Neutral	"White" may refer to the color of food items, packaging, or the restaurant interior. It could also relate to concerns about food quality (e.g., undercooked chicken). Contextual analysis of reviews is needed for deeper insights.
clear	Neutral/Positive	This word might be used in the context of clarity in menu options, order accuracy, or cleanliness. Positive mentions suggest that customers find McDonald's well-organized and hygienic, which is a good sign.
substance	Neutral	Customers mentioning "substance" might be discussing the texture, quality, or portion sizes of food items. Negative mentions could indicate dissatisfaction with overly processed food or lack of nutritional value.
trying	Neutral/Negative	If customers mention "trying," they could be giving McDonald's another chance after a past bad experience or struggling to enjoy a particular menu item. This suggests fluctuating satisfaction levels, meaning consistency in food and service is crucial.


Overall Insights:
Food Quality & Appearance Are Key:
"Food," "look," and "spit" indicate that food presentation and hygiene are major concerns. Customers expect visually appealing and well-prepared meals.
"Milky" and "substance" suggest specific feedback on texture and consistency, particularly for beverages.

Customer Service Plays a Role:
"Polite" is a positive word, showing appreciation for courteous staff.
"Someone" and "transaction" may point to service issues, suggesting a need for improved training and payment efficiency.

Ambiance and Experience Matter:
"Chill" and "everyone" indicate that McDonald's provides a welcoming and relaxed atmosphere for some customers.
"Clear" suggests an appreciation for cleanliness and organization.

Expectation vs. Reality:
"Want" and "don’t" imply gaps between what customers expect and what they receive.
"Trying" indicates that some customers are reconsidering their opinion, meaning their experiences need to be consistently good to retain them.

Actionable Recommendations:
•	Enhance Food Presentation & Hygiene: 
Ensure visually appealing and fresh food. Address any hygiene concerns promptly.

•	Improve Customer Service:
Train staff to be attentive and efficient to reduce negative mentions of "someone" and "transaction."

•	Maintain a Comfortable Environment: 
Continue fostering a "chill" atmosphere while ensuring cleanliness remains a priority.

•	Listen to Customer Desires:
Analyze "want" statements in reviews to align the menu with customer expectations.




Interpretation Table for the Given TF-IDF Matrix

TF-IDF
    another   content  document   example    sample      text
0  0.000000  0.000000  1.405465  0.000000  1.405465  0.000000
1  1.405465  1.405465  0.000000  1.405465  0.000000  1.405465

Word	TF-IDF Meaning	Interpretation & Insights for McDonald's Reviews
another	1.405465 in Doc 1 (absent in Doc 0)	This word appears to be more significant in one document only. It may indicate comparisons between different visits, products, or experiences (e.g., "another bad experience" or "another good burger").
content	1.405465 in Doc 1 (absent in Doc 0)	If this term appears in McDonald's reviews, it may refer to digital content, customer expectations, or online engagement (e.g., app content, menu descriptions, or promotional materials).
document	1.405465 in Doc 0 (absent in Doc 1)	The word "document" might not be a typical review term unless referring to receipts, policies, or issues related to orders and transactions. High importance in one document suggests a unique case of customer complaints regarding official records.
example	1.405465 in Doc 1 (absent in Doc 0)	This term suggests that customers might be using specific examples to illustrate their experiences, such as mentioning particular menu items, service incidents, or hygiene concerns.
sample	1.405465 in Doc 0 (absent in Doc 1)	"Sample" could be related to food samples, promotional tastings, or product trials. If highly weighted in one review, it might indicate a discussion on free samples, testing new items, or quality inconsistencies.
text	1.405465 in Doc 1 (absent in Doc 0)	This term could relate to text-based communication from McDonald's (e.g., app notifications, digital menus, or customer support responses). A high TF-IDF score suggests a unique discussion related to messages received by customers.






Key Insights & Recommendations:

Comparative Reviews & Customer Experience:
The word "another" indicates that customers are comparing between different visits or experiences.
McDonald's should look into repeated complaints and work on consistency in service quality.


Customer Interaction with Digital & Physical Content:
The words "content", "text", and "document" indicate that customers are interacting with digital interfaces such as menus, apps, promotions, receipts, or policies.
This indicates the need for better communication, improved app UI/UX, and better transparency in policies.

Promotions & New Product Testing:
"Example" can be related to free sampling, new menu experiments, and promotions.
McDonald's may increase sampling with the help of customers for new products and monitor their reaction to new releases.

Customers Quoting Examples in Reviews:
The word "example" prominent in one document reflects that customers quote certain examples to support their reviews.
This reflects that analyzing real cases of customers would effectively help to bring pain points into recognition.

Final Takeaways: 
•	Monitor customer comparisons to improve consistency in food and service.

•	Enhance digital content & communication across apps, menus, and customer support.

•	Use customer feedback effectively by identifying real-life examples of complaints or praise.

•	Consider increasing product sampling to encourage customer engagement and feedback.

Conclusion: Key Focus Areas
•	Hygiene & food presentation – Reinforce trust with quality control measures.

•	Faster, friendlier service – Improve transaction speed and train staff on politeness.


•	More exciting menu options – Introduce limited-time offers and customizable meals.

•	Enhance ambiance & comfort – Make dining in more enjoyable with clean, relaxed spaces.


•	Rebuild brand trust – Use transparency, customer engagement, and incentives to retain customers.
![image](https://github.com/user-attachments/assets/33106377-6b53-4200-8ef3-09ef7cc5eb2e)
