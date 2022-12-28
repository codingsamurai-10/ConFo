# ConFo

[Frontend repo](https://github.com/codingsamurai-10/confo-frontend) | 
[Backend repo](https://github.com/codingsamurai-10/confo-backend)

A conversational form application that allows admins to create forms and displays them in a chat interface format for a human-interaction-like form-filling experience.

The project was created as a part of a national level hackathon Flipkart Grid 3.0. Out of the 85,000+ teams that participated, my team "Eleetcoders" made it to the grand finale by ranking in the top 12 teams nationwide.

[Demo as given to Flipkart panel in finale](https://youtu.be/ZuDostnoU1Q?t=11143)

![image](https://user-images.githubusercontent.com/58487637/209807443-80a63a86-7fcc-462c-b2ad-4ded8e6fcb14.png)


## Users

The project aims to cater to two types of users
1. Admin - The user of our application who creates a form to be filled by the end users. Information like form fields, data types, etc have to be mentioned by the admin.
2. End user - The end user who fills out the forms created by the admins through our platform. They are the customers of the admins. The form they fill out is a chat interface which gives a feel of talking to an actual person rather than filling out a conventional form.

## Application Flow (admin side)

### Home page
The admin signs up on the platform and sees the this screen. They can either create forms from here or view responses of their existing forms.

![image](https://user-images.githubusercontent.com/58487637/209803494-85db44ab-bde8-485d-a319-45c7adeebd29.png)


### Creating a form
The admin can create a form by providing a name and description to the form along with choosing a theme from the preset theme options.

![image](https://user-images.githubusercontent.com/58487637/209803593-fbe80680-a412-4fc0-bf92-0fec386f97f7.png)

This is what a question adding/deleting/editing interface looks like.

![image](https://user-images.githubusercontent.com/58487637/209803720-33f81173-c4f0-4610-a943-e5fe6dfb290b.png)

The admin can choose the type of the field from the available presets. They can also choose whether this question is required or can be skipped by the end user by checking/unchcecking the "Optional" switch.

![image](https://user-images.githubusercontent.com/58487637/209803830-ca0e3933-ac73-4ef3-9f14-3c964e1eef79.png)

Creating a question allows various checks on the input such as - validating email address and phone number by regex, checking whether a number is in a given range, etc. The admin can also create radio/checkbox input types.

![image](https://user-images.githubusercontent.com/58487637/209804202-72a9f471-c9dc-4da8-a502-9598d365cc6c.png)

Once the admin is satisfied with the form, they can submit it and get a link which they can share with their users who can fill out the form.

![image](https://user-images.githubusercontent.com/58487637/209804414-31aca72a-6c12-4fb6-8997-6bbc499e893a.png)

### Viewing responses
The admin can view the various forms they created and click on any of them to view the responses submitted on it.

![image](https://user-images.githubusercontent.com/58487637/209804556-1e4e44dd-3d62-41b9-ae86-ec7c75ead516.png)

The responses are shown as key value pairs. The data can also be used for any analysis.

![image](https://user-images.githubusercontent.com/58487637/209804671-7b99eb15-6f50-48b1-bc10-ee2f8f600ce9.png)

## End user
The end user will receive a link to the form where they can go and fill the form in a chat interface.

![image](https://user-images.githubusercontent.com/58487637/209806446-a22eb8f5-0389-462c-9e6d-211f088d5fca.png)

![image](https://user-images.githubusercontent.com/58487637/209806497-29078fb6-3d9e-4009-ab04-f2bc737401ee.png)

They are shown their responses getting registered as they fill the form. This is to give the users a confirmation that the data they're entering is being recorded properly.

![image](https://user-images.githubusercontent.com/58487637/209806685-8701a939-0829-4247-a30f-9e499692bb10.png)

They can edit their responses as well!

![image](https://user-images.githubusercontent.com/58487637/209806958-6daf6bb3-cf6c-4340-9a05-48f4170bf083.png)

![image](https://user-images.githubusercontent.com/58487637/209807015-28b216cb-a603-4ba8-b4e4-22a152bb4219.png)

Editing a response doesn't lose the rest of their application data.

![image](https://user-images.githubusercontent.com/58487637/209807051-ae41763a-1c09-4c25-85b2-715ac64f89da.png)

If the user has to leave the form or close the window, they can return later and their responses would be saved. They would be prefilled for them when they return.

![image](https://user-images.githubusercontent.com/58487637/209807170-eaeeee33-7c9d-44b5-b651-5378e10a59f5.png)

# Conclusion

Thus, an end-to-end application similar to Google Forms was built with a conversational interface instead of a conventional static form. The scope of the project can be extended to file uploads, multimedia questions and answers, etc. These forms are known to increase the customer retention rate by not giving them a boring application to fill out but instead a conversation where they participate.
