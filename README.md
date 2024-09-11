# Warwick University Run Club

Welcome to the Warwick University Run Club website repository! This README will guide you through the process of adding new routes to the website.

## How to Add a New Route

1. Go to the `index.html` file in this repository.
2. Click the edit button (pencil icon) to edit the file.
3. Scroll down to the section where routes are added. Look for this comment:
   ```javascript
   // Add routes here
   ```
   [Click here to go directly to this line](https://github.com/yourusername/your-repo-name/blob/main/index.html#L55)

4. To add a new route, add a new line below the existing `addStravaRoute` call, following this format:
   ```javascript
   addStravaRoute('Your Route Name', 'Your-Strava-Embed-ID');
   ```
   Replace 'Your Route Name' with the name of your route, and 'Your-Strava-Embed-ID' with the Strava embed ID for your route.

5. After adding your new route, scroll down to the bottom of the page and click "Commit changes".

## How to Get the Strava Embed ID

1. Go to the Strava route you want to embed.
2. Click on the share button (usually represented by a paper airplane or arrow icon).
3. In the sharing options, look for an "Embed" option.
4. Copy the embed code provided by Strava. It should look something like this:
   ```html
   <div class="strava-embed-placeholder" data-embed-type="route" data-embed-id="2859616468185788390"></div>
   ```
5. The number in the `data-embed-id` attribute is your Strava Embed ID. In this example, it would be "2859616468185788390".

## Updating the Logo

The logo is referenced in the `index.html` file. If you need to update the logo:

1. Upload your new logo file to the repository. Make sure it's named `logo.jpeg`.
2. If you're using a different file name or format, you'll need to update the reference in the `index.html` file.
   [Click here to go to the logo reference in index.html](https://github.com/yourusername/your-repo-name/blob/main/index.html#L43)

## Need Help?

If you encounter any issues or have questions about updating the website, please open an issue in this repository, and we'll be happy to assist you!
