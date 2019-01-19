# urlshortner
Url shortner
Most of us are familiar with seeing URLs like bit.ly or t.co on our Twitter or Facebook feeds. These are examples of shortened URLs, which are a short alias or pointer to a longer page link. For example, I can send you the shortened URL http://bit.ly/SaaYw5 that will forward you to a very long Google URL with search results on how to iron a shirt. It would be much easier to text the 20-character bit.ly URL to your son who is in college and preparing for his first big job interview.
Ads by Hooly

In this article you’ll learn how to create a fully functional URL shortener for your website that will work whether you use a front controller/framework or not. If you use a front controller, I’ll discuss you how to easily integrate this URL shortener without having to dig into the controller’s programming.

Answering Some Common Questions
So with bit.ly and many other URL shorteners like it out there and freely available, why should we bother building our own? Most of these shortening services even have an easy-to-use API so that we can programmatically generate a shortened URL, and use it within our PHP scripts.

The best reasons are for convenience, aesthetics and brand recognition. If for example your website has an application that creates a large amount of reports, a very active blog or a large photo album, there will be a lot of links. A URL shortener will allow you to programmatically create a clean, simple link that can be emailed to your readers or published on your website. The obvious advantage to having your own is that your readers have instant brand recognition with your website.

You may wonder why you always see letters mixed with numbers in shortened URL’s. By having more than ten options (0-9) per digit, we are able to have dramatically more combinations while keeping the code as short as possible.

The characters we’ll be using are the digits 1-9 along with various upper/lowercase letters. I have removed all of the vowels to prevent having links created which are unintended bad words, and I have removed any characters that could be confused with each other. This gives us a list of about 50 characters available for each digit, which means that with two characters, we have 2,500 possible combinations, 125,000 possibilities with three characters, and a whopping 6.5 million combinations with just four characters!
