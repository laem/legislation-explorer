# OpenFisca Legislation explorer

## Presentation

[OpenFisca](http://www.openfisca.fr/) is a versatile microsimulation free software.

This application allows to explore the legislation with its parameters and formulas.

See http://legislation.openfisca.fr/

## Run the server

The following `npm run` commands are declared in `package.json`.

### Development server

    npm install
    npm run assets
    npm run dev

> The "assets" command must be run the first time only (it just copies some files).

Open http://localhost:2030/

### Production server

    npm install
    npm run clean
    npm run assets
    npm run build
    npm start

Open http://localhost:2030/

## OpenFisca Documentation

Please consult http://doc.openfisca.fr/

## Contribute

OpenFisca is a free software project.
Its source code is distributed under the [GNU Affero General Public Licence](http://www.gnu.org/licenses/agpl.html)
version 3 or later (see COPYING).

Feel free to join the OpenFisca development team on [GitHub](https://github.com/openfisca) or contact us by email at
contact@openfisca.fr

## Inspiration

Thanks to the [isomorphic500](https://github.com/gpbl/isomorphic500) project for inspiration
about the JavaScript build system and React server-side rendering!
