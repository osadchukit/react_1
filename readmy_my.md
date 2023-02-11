instal react:
https://create-react-app.dev/docs/getting-started/
npx create-react-app .

<!-- ----------------------------------------- -->

instal prop-types:
https://www.npmjs.com/package/prop-types
npm install --save prop-types

import React from 'react';
import PropTypes from 'prop-types';

<!-- ----------------------------------------- -->

instal date-fns:
https://date-fns.org/v2.29.3/docs/Getting-Started#installation
npm install date-fns --save

import { format } from "date-fns";

<!-- ----------------------------------------- -->

instal React Icons:
https://react-icons.github.io/react-icons/
npm install react-icons --save

import { FaMapMarkerAlt } from 'react-icons/fa';

<!-- ----------------------------------------- -->

instal Emotion:
https://emotion.sh/docs/install
npm i @emotion/styled @emotion/react

<!-- ----------------------------------------- -->

echo "# react_1.1" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/osadchukit/react_1.1.git
git push -u origin main
