# Editable profile — complete or change only this block

- **Age:** [e.g., 30]
- **Sex:** [e.g., female / male / prefer not to say]
- **Height:** [e.g., 165 cm]
- **Current weight:** [e.g., 72 kg]
- **Goal:** [e.g., maintain weight / gradual fat loss / gradual weight gain / improve energy]
- **Target weight (if applicable):** [e.g., 65 kg]
- **Activity level:** [e.g., sedentary / lightly active / active]
- **Exercise days per week and type:** [e.g., 3 days: walking and strength training]
- **Work or study schedule:** [e.g., office, 9:30 am–6:30 pm]
- **Usual wake time / sleep time:** [e.g., 6:30 am / 10:30 pm]
- **Allergies or medical conditions:** [e.g., none; list diagnosed conditions]
- **Foods to avoid / dislikes:** [e.g., no bitter gourd; dislikes mushrooms]
- **Dietary restrictions:** [e.g., lacto-vegetarian; no eggs; Jain restrictions]
- **Budget:** [e.g., economical / moderate / flexible]
- **Location and local availability:** [e.g., Chennai, Tamil Nadu; standard local grocery market]
- **Cooking access and time:** [e.g., gas stove and mixer; 30 minutes on weekdays]
- **Household / serving preference:** [e.g., cooking for one; leftovers acceptable]
- **Other preferences:** [e.g., prefer millets twice weekly]

---

## RTCFR prompt

### Role

Act as a qualified, evidence-informed nutrition professional specialising in practical South Indian vegetarian meal planning. Give general nutrition education, not medical diagnosis or treatment.

### Task

Create a safe, realistic 7-day vegetarian South Indian meal plan that supports gradual, sustainable weight loss when that is the goal in the profile.

### Context

Use the editable profile above as the source of truth. Tailor dishes, portions, timing, shopping choices, cooking effort, and substitutions to it. If a field is blank, make a modest, clearly stated assumption rather than asking questions.

### Format

Return the answer in this exact order and structure:

1. **Assumptions and safety note** — 2–5 concise bullets, including any assumptions made for blank profile fields and any appropriate professional-referral note.
2. **7-day meal-plan table** — one Markdown table only, with these exact columns:

   | Day | Meal | Dish | Portion |
   |---|---|---|---|

   Include exactly four rows for each Day 1 through Day 7: Breakfast, Lunch, Snack, and Dinner, in that order. Each row must name a real dish or dishes and state the portion size. Do not add extra meal occasions or replace a meal with a generic instruction.
3. **Practical notes** — 3–6 concise bullets covering hydration, simple preparation or batch-prep ideas, and sensible substitutions that still meet the restrictions.

### Rules and constraints

1. Make the plan vegetarian and recognisably South Indian. Name specific real dishes—not vague labels such as “healthy breakfast.” Suitable examples include idli with sambar, vegetable upma, pongal, pesarattu, adai, vegetable kootu, rasam, poriyal, avial, curd rice, lemon rice, millet dosa, and sundal. Adapt dishes to the dietary restrictions and preferences in the profile.
2. Provide exactly 7 days. Every day must include exactly four eating occasions: **Breakfast**, **Lunch**, **One snack**, and **Dinner**—for a total of 28 meal rows.
3. Use ordinary household portions for the individual: cups, number of idlis/dosas/chapatis, ladles, bowls, or grams where helpful. State portions directly beside each dish.
4. Keep meals balanced across the day. Include reliable vegetarian protein sources regularly (for example dal, legumes, curd/paneer if permitted, milk, soy, peanuts, sesame, or other locally appropriate foods), vegetables, fibre-rich grains or millets, and adequate fluids. Avoid repetitive meals where practical.
5. Match the goal sensibly. Do not prescribe extreme calorie restriction, fasting, detoxes, crash dieting, purges, or unsafe supplements. Use gradual, sustainable changes and normal meals.
6. Prefer affordable, seasonal ingredients and foods commonly obtainable in the stated South Indian location. Keep weekday preparation compatible with the available cooking time and equipment; suggest batch-prep only when it is practical.
7. Respect all allergies, dislikes, dietary restrictions, budget, and schedule. Never recommend an allergen listed in the profile.
8. Do not make diagnoses, promise medical outcomes, or present the plan as medical treatment. For pregnancy, breastfeeding, eating-disorder history, diabetes, kidney disease, gastrointestinal disease, serious allergies, other medical conditions, or medication-related dietary needs, add a concise note advising review by a qualified clinician or registered dietitian.

Do not include calorie totals unless the editable profile explicitly requests them. Keep the tone supportive, practical, culturally familiar, and non-judgmental.
