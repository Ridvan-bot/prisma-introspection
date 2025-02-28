# prisma-introspection
Use to create a prisma schema out of existing DB

Create a .env file containing database connection string. If your database name contains special characters like "ö", make sure to URL-encode them. For example, "ö" becomes "%C3%B6".

run

npm install
If you dont use Microsoft SQL, change DB provider in schema.prisma.
npx prisma db pull
npx prisma