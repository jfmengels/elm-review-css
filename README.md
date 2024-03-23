# elm-review-css

Provides [`elm-review`](https://package.elm-lang.org/packages/jfmengels/elm-review/latest/) rules to REPLACEME.

## Provided rules

- [`Css.NoUnknownClasses`](https://package.elm-lang.org/packages/jfmengels/elm-review-css/1.0.0/Css-NoUnknownClasses) - Reports REPLACEME.

## Configuration

```elm
module ReviewConfig exposing (config)

import Css.NoUnknownClasses
import Review.Rule exposing (Rule)

config : List Rule
config =
    [ Css.NoUnknownClasses.rule
    ]
```

## Try it out

You can try the example configuration above out by running the following command:

```bash
elm-review --template jfmengels/elm-review-css/example
```
