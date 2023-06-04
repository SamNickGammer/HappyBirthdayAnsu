# Happy Birthday Card

A Customizable Web based birthday card to wish your friends and family in a unique way.

## How to setup

Here are the methods to set it up for yourself.

### For Local Building

1. Clone the repository

   ```sh
   git clone https://github.com/SamNickGammer/HappyBirthdayAnsu.git
   ```

2. Install dependencies

   ```sh
   npm install
   ```

3. Add a pic of the receiver, in the `./local` directory. Ensure that the image is of 1:1 ratio or it might get cropped and squished.

4. Create a `.env` file in root directory, and add the following lines.

   ```env
    NAME='Name of the Receiever'
    PIC='name-of-image.extension'
   ```

5. Execute the following commands in order.

   ```sh
    npm run dev
    npm run build
   ```

6. Upon Successful execution, your built files will be ready in the `./dist` directory. Open `./dist/index.html` to see the card.


---

## Support

If you have any queries or need some help in deployment, you may contact me here

<div align="center">

<a href="https://www.instagram.com/samnickgammer/"><img src="https://cdn.cdnlogo.com/logos/i/92/instagram.svg" height="50px"></a>
<a href="https://www.linkedin.com/in/omprakashbharati/"><img src="https://cdn.cdnlogo.com/logos/l/66/linkedin-icon.svg" height="50px"></a>

Made with 💖 by Sam Nick

</div>
