# PgmOps

## Intro

PgmOps is a SaaS platform that offers your business with an analytical tool to maximize profit or minimize costs. It is based in the [Simplex algorithm](https://en.wikipedia.org/wiki/Simplex_algorithm) developed by George Dantzig.  

Currently, the software is planned to support the following modules:  

- Construction jobs (number of workers/output)
- Scheduling (fitting multiple people inside a work shift)
- General case (e.g. bare equations)
- HR (project management)

## History

The project was initially conceived in 2019 and the project structure was modelled in Laravel. Development work has been made mainly in marketing and usability areas and not coding or platforms.  

## Example

For a construction project, usually we want to reduce expenses, so our initial matrix of equtions would be in the form of:  

$Z = x + y + z + ... $

Where each unkown variable is an individual contribution to the total cost (Z function) and is usually associated with a resource.  

Where it gets interesting is when we consider each one of successive restrictions (e.g. conflicting schedules or resources):  

$x < 500$  
$y > 20$  

And each one of this restrictions is added to the linear equations matrix in order to be solved.

## License

The project is closed-source and because of that, only the documentation is shared here as a public resource.  

