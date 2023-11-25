# namastereact
npm install -D parcel
here -D means dev dependencies

when we execute this command npm will fetch all the code of parcel and place it in node_modules
Now lot of things will will come up with parcel
we only installed parcel but even then , brcausen parcel also has its dependencies and so on

All the dependencies can be checked inside the package.json
"devDependencies": {
    "parcel": "^2.10.3"
  }

  here carat symbol ^ can also be replaced by ~
  ^ = update if the next minimal version comes like 2.10.4
  ~ = update to major versions if it comes like 3.0


  pacakge-lock.json will keep track of all the curent versions getting used if updates happens
  it has exact details about the version
