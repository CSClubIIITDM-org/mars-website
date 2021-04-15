# How to configure the website
The entire website is configured through the `yaml` files in `data` folder and through `config.yaml`. The images are stored in `assets/images` and their paths are mentioned relative to `assets` in the `yaml` files stored in `data`.

# How to test the website
Ensure you have the following software in your environment.
- Hugo
- Go
- NPM
  
## Commands
```sh
# Fetch Hugo dependencies
hugo mod get -u

# Fetch NPM dependencies
hugo mod npm pack
npm i

# Run local server
hugo server                             # for development, or
hugo server -e production -d public     # for testing production builds 
```
