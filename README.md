# Create new input button

```
reactR::scaffoldReactShinyInput(
    "checkbox_field", 
    list(
        "@mui/material" = "^5.10.12"
    )
)
```

# 1) yarn install
# 2) yarn run webpack --mode=development
# 2.1) yarn webpack --watch --mode=development

# R console
# 1) devtools::check()
# 2) devtools::document()
# 3) devtools::load_all()

# build
1) devtools::check(); devtools::document(); devtools::load_all()

# devtools::load_all(); shiny::runApp()
