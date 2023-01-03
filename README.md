# Whatsapp Bot for Marketing
This is a Whatsapp Bot that can send out the same message to unlimited whatsapp users at the rate of 4-5 messages/minute. It can be effectively used for marketing purposes where you can reach out to several potential customers/leads with personalized messages.

# How to run the bot?
1. Change the path of the input file
2. Write the message to be sent, seperate lines should be included as seperate strings in the list
3. For messages including images, change image path and use function 'send_mssg_with_img'
4. For messages without images, use function 'send_mssg_without_img'

# How does the bot work?
This bot uses selenium library in Python to access web WhatsApp and then simulates human behaviour to send the same message to multiple users by using the contact numbers provided in the input excel sheet.
