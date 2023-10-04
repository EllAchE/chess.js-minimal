# chess.js

[![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/jhlywa/chess.js/node.js.yml)](https://github.com/jhlywa/chess.js/actions)
[![npm](https://img.shields.io/npm/v/chess.js?color=blue)](https://www.npmjs.com/package/chess.js)
[![npm](https://img.shields.io/npm/dm/chess.js)](https://www.npmjs.com/package/chess.js)

chess.js is a TypeScript chess library used for chess move
generation/validation, piece placement/movement, and check/checkmate/stalemate
detection - basically everything but the AI.

chess.js has been extensively tested in node.js and most modern browsers.

# My Fork

This fork strips away a ton of the cool stuff that chess.js does and focuses on reading pgn files in quickly for the purpose of generating move history.

TODO: caching common openings might save some time
