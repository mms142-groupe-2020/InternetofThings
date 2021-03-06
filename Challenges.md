# Challenges with IoT

<img src="https://raw.githubusercontent.com/mms142-groupe-2020/InternetofThings/main/assets/images/privacy.jpg" alt="privacy">

On September 27, 2019, tech giant Amazon put up a blog post introducing their new Amazon Sidewalk feature. This feature allows smart devices under their brand to communicate and share network bandwidth with each other with the intended purpose of extending and strengthening the connectivity of devices at the limit of a home’s WiFi network.

> “With Amazon Sidewalk, customers will be able to place smart devices anywhere on their property and know they’ll work great, even in dead spots where Wi-Fi and Bluetooth don’t reach.”

What is not explained in the blog post, however, is that this connectivity is shared to all Amazon smart devices, even ones that are not owned by the user. This potentially means that the devices of a neighbor can connect to the Internet using a user’s ISP. Amazon later clarified that there will be an opt-out setting to this feature, but keeping it on by default ensures that a majority of these devices will have this feature turned on.

This example outlines some of the challenges of IoT: privacy, ownership, and most importantly, security.

Sidewalk allows devices to always be connected, thus always gathering data, even if your ISP is disconnected, this is a big privacy concern.

If Amazon, or any other company, can just simply flip a switch and turn on or off a feature, what else can they do? Is the user really the owner of the device? Or is it Amazon?

Neighbor’s devices connecting to the internet via a user’s ISP also means that they are connected to the home network, which presents a lot of security questions.

## Privacy

Data privacy has been at the forefront of discussion in the Internet space for the past decade. Numerous reports of companies selling the data of their users have prompted regulators in the EU and the US to pass laws like the General Data Protection Regulation (GDPR) to limit these activities. Even with these laws, however, the potential amount of data that can be collected by smart devices still lead to a lot of privacy issues. The companies might not know your name or address, but if they have enough data about you, that information will become irrelevant.

An article by Mozilla, the company behind the Firefox browser, details how Digital Fingerprinting can be used to identify a person just with the data they leave behind while browsing the web normally.

> “While trackers won’t necessarily match your activity with a face or a name, the data they derive from websites you visit, social platforms you use, searches you perform, and content you consume, can be considered personally identifiable. With this data, brokers build a general profile of who you are (age range, location, language, interests, etc.) and sell this insight to advertisers and marketers who use it to relentlessly serve you personalized ads and content recommendations across the web.”

IoT devices by their nature, have sensors built into them that can collect data. Any smart device with a microphone is usually always listening for the keyword to activate them. There are theories that some devices like smartphones or smart home speakers can identify when a product is mentioned in a conversation so they can serve the appropriate advertisement on Facebook or YouTube. Though Facebook has denied this, it is still jarring to see an advertisement about something only mentioned in conversation, not even searched for yet.

This could be a coincidence, but this could also be digital fingerprinting working as intended. Perhaps the conversation was spurred on by a previous Google search, so the ads served were for related items. There can be many explanations, but the fact remains that advertisers will use any and all data they can access to increase the chances of an ad being clicked on.

Devices without microphones or cameras can still gather information about their usage. Smart Refrigerators can determine brand preferences, Smart TVs can determine viewing habits, Smart Speakers can be used to figure out music preferences, Smart Rice Cookers can determine eating habits.

Even something as innocuous as a Smart Light Bulb, that you can turn on or off remotely, can gather data. Looking at the data of when it is turned on in a particular time frame, it can be used to see possible hours that there is a person in a specific room.

## Ownership

Indeed some companies charge fees for using their devices or services related to these devices. This is on top of the purchasing price of the actual device. If a user fails to pay for these services, or if they do something that the original manufacturer didn’t like, they could lose access to the device they paid for.

The controversy with John Deere tractors illustrates this problem. Farmers are unable to make any repairs to their tractors because the software installed on them will detect them and prevent the full use of the equipment. It’s not hard to imagine this happening with smart devices, and with the added connectivity inherent in these devices, they don’t even need to break, they just need to become unsupported by the manufacturer.

Sonos, a company known for making smart speaker systems, announced in January 2020 that unsupported devices will no longer receive firmware updates. Normally this would not be a big issue, as companies cannot be expected to support devices indefinitely. But since Sonos sells “speaker systems,” they are also restricting firmware updates for new devices connected to unsupported devices. This forces users that have otherwise working systems to upgrade if they want to continue receiving updates for their devices, which often means for those devices to continue working properly and securely.

## Security

The aspect of IoT that presents the most challenges is the security aspect. More Internet-connected devices mean more points of attack. Conversely, vulnerable devices can also be used as a mode of attack, as they are at their core, computers.

Security strategist Joshua Corman likened the security issues to “swimming with sharks” in a talk in 2013:

> “If it has software, substitute the word 'hackable'. If it has (a) connection substitute the word 'exposed'...no one is even thinking about the fact that in this digital sea and the Internet of Things, we also have apex predators.”

As the market for smart devices grows, a lot of companies have taken the initiative to fill these spaces. Though some of these are large and are fairly reputable (Samsung, Google, Amazon) there are also those that have questionable ties to foreign governments (Huawei). Even the “fairly reputable” companies do not have the best track record for security updates of their most profitable devices (smartphones), what more of smaller margin devices?

In 2015, security researchers were able to find a vulnerability in a Samsung Smart Refrigerator that allowed them to access Gmail credentials.

> “The internet-connected device is designed to download Gmail Calendar information to an on-screen display. Security shortcomings mean that hackers who manage to jump on to the same network can potentially steal Google login credentials from their neighbours.”

Though there are smaller companies, they are likely to get sold to these bigger companies (Nest to Google, Smart Things to Samsung) if not close down outright. When these companies close or get bought, there is a high chance that the devices they sell will no longer be updated, leaving them vulnerable to attack for as long as they are still in use.

Ken Munro, an Ethical Hacking Specialist, was able to demonstrate existing vulnerabilities in smart locks, smart kettles, and even smart dolls. These range from being able to open and find locks, to retrieving wifi passwords, to being able to communicate with a child.

<iframe width="560" height="315" src="https://www.youtube.com/embed/pGtnC1jKpMg" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Indeed, as more and more smart devices get connected to a network, more and more security vulnerabilities need to be taken into account. This requires a lot of work and thought, something that the average consumer probably will not even consider. This leaves security at the hands of the manufacturers some of whom do not have the best interest of the consumer in mind.

And when these vulnerabilities are exploited, smart devices can also be used as tools to aid in attacking other networks. In 2016, a number of exploited IoT devices were leveraged to mount a distributed denial of service attack (DDOS) that affected sites like Twitter, Reddit and Spotify among others.

An estimated 21.5 Billion IoT devices will become active by 2025 according to Statista.com. Contrast this with just 3 billion smartphone users by 2021 and the difference in scale that any vulnerability or attack can introduce.

## Conclusion

Of course, there are many more challenges that might be less obvious that were not mentioned here. One of them is the impact of AI integration on these smart devices, which brings about images of The Terminator movies and Skynet. Right now though, that challenge can possibly still be avoided.

The challenges of IoT mentioned above might look daunting and insurmountable, but these obstacles are not going to hinder the adoption of IoT itself. The advantages and benefits of connected devices far outweigh the negatives, at least to the companies that make and market them. 

No, these challenges are what society and the world at large will need to address. IoT is here to stay, it might not even be a choice to live with it or without it, it will just be everywhere.

## References

Goode, L. (2020, January 21). Sonos Will Soon End Software Support for Its Older Speakers. Wired. [https://www.wired.com/story/older-sonos-speakers-will-stop-receiving-updates/](https://www.wired.com/story/older-sonos-speakers-will-stop-receiving-updates/)

Kessler, D. (2019, March 20). This is Your Digital Fingerprint. Internet Citizen. [https://blog.mozilla.org/internetcitizen/2018/07/26/this-is-your-digital-fingerprint/](https://blog.mozilla.org/internetcitizen/2018/07/26/this-is-your-digital-fingerprint/)

Koebler, J. (2017, March 21). Why American Farmers Are Hacking Their Tractors With Ukrainian Firmware. Vice. [https://www.vice.com/en/article/xykkkd/why-american-farmers-are-hacking-their-tractors-with-ukrainian-firmware](https://www.vice.com/en/article/xykkkd/why-american-farmers-are-hacking-their-tractors-with-ukrainian-firmware)

Leyden, J. (2015, August 24). Samsung smart fridge leaves Gmail logins open to attack. The Register. [https://www.theregister.com/2015/08/24/smart_fridge_security_fubar/](https://www.theregister.com/2015/08/24/smart_fridge_security_fubar/)

Meyer, R. (2016, December 8). How an Internet-of-Things Botnet Took Down Twitter, Reddit, and Github. The Atlantic. [https://www.theatlantic.com/technology/archive/2016/10/how-a-bunch-of-hacked-dvr-machines-took-down-twitter-and-reddit/505073/](https://www.theatlantic.com/technology/archive/2016/10/how-a-bunch-of-hacked-dvr-machines-took-down-twitter-and-reddit/505073/)

Staff, A. (2019, September 27). Introducing Amazon Sidewalk. About Amazon. [https://www.aboutamazon.com/news/devices/introducing-amazon-sidewalk](https://www.aboutamazon.com/news/devices/introducing-amazon-sidewalk)

Statista. (2020a, September 1). Internet of Things - active connections worldwide 2015-2025. [https://www.statista.com/statistics/1101442/iot-number-of-connected-devices-worldwide/](https://www.statista.com/statistics/1101442/iot-number-of-connected-devices-worldwide/#:%7E:text=The%20total%20installed%20base%20of,such%20as%20computers%20and%20cellphones)

Statista. (2020b, December 10). Smartphone users worldwide 2016-2021. [https://www.statista.com/statistics/330695/number-of-smartphone-users-worldwide/](https://www.statista.com/statistics/330695/number-of-smartphone-users-worldwide/)

TEDx Talks. (2013, December 20). Swimming with sharks - security in the internet of things: Joshua Corman at TEDxNaperville. YouTube. [https://www.youtube.com/watch?v=rZ6xoAtdF3o](https://www.youtube.com/watch?v=rZ6xoAtdF3o)

There’s a wildly popular conspiracy theory that Facebook listens to your private phone calls, and no matter what the tech giant says people just aren’t convinced it’s not true. (2019, May 18). Business Insider Nederland. [https://www.businessinsider.nl/facebook-ads-listening-to-you-2019-5?international=true&r=US](https://www.businessinsider.nl/facebook-ads-listening-to-you-2019-5?international=true&r=US)

Williams, C. (2020, November 26). Amazon’s ad-hoc Ring, Echo mesh network can mooch off your neighbors’ Wi-Fi if needed – and it’s opt-out. The Register. [https://www.theregister.com/2020/11/24/amazon_sidewalk_opt_out/](https://www.theregister.com/2020/11/24/amazon_sidewalk_opt_out/)


