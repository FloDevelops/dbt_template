Welcome to your new dbt project!

## Installation

- Clone this repository.
- Use the same python version as .python-version with pyenv
- Create a virtual environment with `python -m venv .venv`
- Copy the .env.example file as .env and fill in the variables with the correct values.
- Export all environment variables from .env to your virtual environment by running: `echo -e "\n# Exports all variables from .env file\nset -a\nsource .env\nset +a\n" >> .venv/bin/activate`
- Activate the virtual environment with `source .venv/bin/activate`
- Install python dependencies with `pip install -r requirements.txt`
- Verify dbt is installed with `dbt --version`
- Add a service account json file under secrets/sa.json
- Install dbt dependencies with `dbt deps`
- Test the connection to Bigquery with `dbt debug`

### Using the starter project

Try running the following commands:

- dbt run
- dbt test

### Resources:

- Learn more about dbt [in the docs](https://docs.getdbt.com/docs/introduction)
- Check out [Discourse](https://discourse.getdbt.com/) for commonly asked questions and answers
- Join the [chat](https://community.getdbt.com/) on Slack for live discussions and support
- Find [dbt events](https://events.getdbt.com) near you
- Check out [the blog](https://blog.getdbt.com/) for the latest news on dbt's development and best practices
