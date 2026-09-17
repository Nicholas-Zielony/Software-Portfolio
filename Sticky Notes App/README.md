# Sticky Notes App - "sticky_notes"

## Downloading
- Download the "sticky_notes.zip" and extract to your desired directory
## Launching
> python manage.py runserver

- Make sure you have the correct directory set up!
- View the requirements.txt file to see what is needed.
## Using
- View all sticky notes in a list. Each includes a title, body text, creation / update date, author, and a #ID
- Create a note by using the "+ Create Note" in the top right corner
- Hover over a note and click it to view that note
- When viewing a non-admin note, you can update or delete its contents
- Notes with an admin author cannot be updated or deleted.
- Use the Django admin functionality to create new authors or delete admin messages
## Testing
> python manage.py test posts
- this will test 4 different functions of the sticky_notes application
- check the results at the end!