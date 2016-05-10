# Alberta Compensation Transparency Toolkit
Open Source toolkit to support disclosures under Alberta's Public Sector Compensation Transparency Act

For instructions, see the implementation guide at: http://abgov.github.io/ab-compensation-transparency-toolkit/

## Project structure
```
ab-compensation-transparency-toolkit
│
│   index.html         : Documentation page.
│   template.xlsx      : Empty template Excel file for creating CSV
│   ab-compensation-transparency-toolkit-all.zip
│                      : Toolkit package for self-hosting.
│
├───pages              : Assets referenced by the documentation page.
│       ...
│
├───lib                : Source code for the toolkit.
│   │
│   ├───css            : The CSS files and images.
│   │       ...
│   │
│   └───js             : The JavaScript files.
│           ...
│
├───cdn                : Published copies of the toolkit resources, intended for access through 
│   │                    github.io. These files are updated only when new releases are prepared.
│   │
│   └───lib            : Has the same folder structure as lib/ directory above.
│           ...
│
├───demo               : Sample html referencing the most recent release versions of the toolkit.
│   │
│   │   disclosure.csv
│   │   grid-only.html
│   │   sample-page.html
│   │
│   └───attach          : Sample attachment files.
│            ...
│
└───test                : Html pages similar to demo, but uses relative URLs to reference local 
        ...               development assets.

```

## Development procedures
... Under construction ...
### Make changes to source code in lib/ directory
### Apply changes to cdn/lib/ subdirectory
### Make toolkit self-hosting package
### gh-pages branch pull from master branch

