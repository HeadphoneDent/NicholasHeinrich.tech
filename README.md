# Website

> This website is live and visible at [NicholasHeinrich.tech](https://nicholasheinrich.tech). Use this repository to edit the code.

## Modify

Modifying the code requires NodeJs to be installed. Reference their [page](https://nodejs.org/) for more information.

**Install TailwindCSS**

```
npm install -D tailwindcss
```

**Run TailwindCSS**

```
npx tailwindcss -i ./src/style.css -o ./style.css --watch
```

The above code will run an instance of TailwindCSS that automatically adds and removes CSS styling to the `./style.css` file.
