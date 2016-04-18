[![Codeship Status for natuelabs/jobs](https://www.codeship.io/projects/0b0b6140-3cfb-0132-78d8-524bbe6961f6/status)](https://www.codeship.io/projects/43138)

Natue's IT jobs page
====

The jobs page is a simple [Jekyll](http://jekyllrb.com/) blog, the form data is
posted into [Typeform](https://typeform.com) and the blog uses
[CodeShip](https://www.codeship.io) to continuous deploy the generated static
website into [Amazon's S3](http://aws.amazon.com/s3/).

## Working on it

Run this commands to start your local copy of the website:

````
git clone git@github.com:natuelabs/jobs.git
cd jobs
bundle
jekyll serve
open http://localhost:4000
````

Any changes on the files are automatically reloaded so you don't need to
re-start the server unless you make changes on the configuration files.

Any push to master is automatically deployed into production, so please, work
on branches.
