# Environmental Variable
1. Create th efile at the root of the project 
```
.env
```

2. Inside the .env file add the text:
- You must use the `NEXT_PUBLIC` or else this will not work
```
NEXT_PUBLIC_TITLE = "Digital Designa dn Development Diploma"
```

3. On the page, in between the export and return write the variable:
```
var title = process.env.NEXT_PUBLIX_TITLE
```

4. Then inbetween the main write:
```
{title}
```

5. Make sure the `.gitignore` file has the `.env` inside
- you want to prevent this secret title to be shown

## BCIT Data from Digital Design and Development Diploma
[Digital Design and Development Diploma](https://www.bcit.ca/programs/digital-design-and-development-diploma-full-time-6515dipma/#courses) 