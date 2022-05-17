# Mole detection

- Repository: `challenge-mole`
- Type of Challenge: `Consolidation`
- Duration: `8 days`
- Deadline: `24/05/2022 4:30` **(code)**
- Presentation: `25/05/2022 1:30 PM`
- Challenge: Solo

![AI care!](./assets/ai-care.jpg)

## Mission objectives

- Be able to apply a CNN in a real context
- Be able to preprocess data for computer vision
- Be able to evaluate your model (split dataset, confusion matrix, hyper-parameter tuning, etc)
- Be able to visualize your model results and evaluations (properly labeled, titled...)
- Be able to deploy your solution in an simple APP locally or on Heroku

## The Mission

The health care company "skinCare" hires you as a freelance data scientist for a short mission.
Seeing that they pay you an incredible amount of money you accept. Here is the mail you receive:

```text
from: sales.skincare.be@gmail.com
to:   projects@becode.org

Hi,

At skinCare we have more and more demands from companies for a tool that would be able to detect moles that need to be handled by doctors.

Your mission, if you accept it, would be to create an AI that can detect when the mole is dangerous. To be able to use your AI, we want you to create a simple web page where the user could upload a picture of the mole and see the result.

We don't have a web development department in our company, so you will need to handle the UI as well, we don't care about having something amazing on the design side, we just want a proof of concept to show our client that the product has potential. You are free in the technology you want to use.

You will also need to put your application on the internet so we can use it. I guess you know what that means.

You will find attached to this email the data you need.

If you have any questions, feel free to reply to this mail or send a mail to our department at the following email address: sales.skincare.be@gmail.com

Good luck,
skinCare sales team
```

Analyze the customer's request.
The dataset provided by the client can be found here: https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000

Possible disease states are "Melanoma", "Melanocytic nevus", "Basal cell carcinoma", "Actinic keratosis / Bowen’s disease (intraepithelial carcinoma)", "Benign keratosis (solar lentigo / seborrheic keratosis / lichen planus-like keratosis)", "Dermatofibroma", and "Vascular lesion". Approximately 10,000 images provided for training, 200 for validation, 1500 for test.
