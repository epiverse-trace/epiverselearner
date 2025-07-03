
# epiverselearner

A clean project ready to use to practice outbreak analytics tasks
using open-source packages from the 
[Epiverse-TRACE](https://epiverse-trace.github.io/),
[Epiforecasts](https://epiforecasts.io/), 
[Reconverse](https://www.reconverse.org/), and
[R Epidemics Consortium](https://www.repidemicsconsortium.org/projects/)
toolkits.

## Usage

1. Open the files `00-packages`.
2. Run the script to load all the pre-installed packages.

To read data you can simulate it using {simulist},
read stored data in R packages like {outbreaks},
or read it using link to files stored on internet or GitHub repositories.


## Posit Cloud

The Posit Cloud already have all packages and dependencies installed. 

To keep record of your edits or notes,
Click on **Save a Permanent Copy**.


## Support

Join the [Discussions on GitHub](https://github.com/orgs/epiverse-trace/discussions).


## License

[MIT](https://choosealicense.com/licenses/mit/)


## Contributing

Contributions are always welcome!

In the [GitHub repository](https://github.com/epiverse-trace/epiverselearner), 
fill issues or fork the repository to create a Pull Request. 


## Installation

Get a local copy:

1. Fork and clone the repository: <https://github.com/epiverse-trace/epiverselearner>
2. Restore the R environment running:

```r
if(!require("renv")) install.packages("renv")
renv::restore()
```

