# Repository with 3rd Party Services compatible with Murano

## Validation

- Depends on json validate from: `sudo pip install json-spec`
- Depends on yaml2json from: `sudo apt install libghc-yaml-dev`
  - #On 14.04: `npm install -g yaml2json`
  - `pip install yq`
  - `cat statuspage.io/swagger.yaml | yq .`

./validate

For more descriptive error message in hard cases check: https://jsonschemalint.com/#/version/draft-04/markup/json
