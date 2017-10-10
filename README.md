![Adonis from Scratch with Nanobox](https://guides.nanobox.io/assets/quickstart-icons/adonis.png)

# Adonis from Scratch with Nanobox

Run a Adonis app locally. Install nothing besides Nanobox.

<a href="https://nanobox.io/download"><img src="https://guides.nanobox.io/assets/quickstart-icons/download.png" /></a>


## Clone the Repo

```bash
# clone the code
git clone https://github.com/nanobox-quickstarts/nanobox-adonis.git

# cd into the adonis app
cd nanobox-adonis
```

## Run the App

```bash
# Add a convenient way to access your app from the browser
nanobox dns add local adonis.dev

# Run Adonis with Nanobox
nanobox run yarn run dev
```

## Check it Out

Visit your app at <a href="http://adonis.dev:3333" target="\_blank">adonis.dev:3333</a>

## Explore

With Nanobox, you don't have to have anything installed on your machine to run your app:

```bash
# drop into a Nanobox console
nanobox run

# where node is installed,
node -v

# your packages are available,
yarn ls

# and your code is mounted
ls
```

## Clean things up _(optional)_

If you want to keep this project ignore this. If not, clean things up by removing the DNS entry:

```bash
nanobox dns rm local adonis.dev
```

## Now What?
For more details about running adonis apps with nanobox visit [guides.nanobox.io/nodejs/adonis/](https://guides.nanobox.io/nodejs/adonis/)

<a href="https://nanobox.io"><img src="https://guides.nanobox.io/assets/quickstart-icons/footer.png" /></a>
