# dbt-tutorial
[https://docs.getdbt.com/guides/manual-install?step=1](https://docs.getdbt.com/guides/manual-install?step=1)

### Notes
#### Initial setup:
* Install dbt along with package.
* Create a project and set it up in GCP (credentials, load data, etc..)

#### Tutorial stes
Create repo

Activate environment, check dbt version to make sure you have it, initialize project
```
dbt_env
dbt --version
dbt init jaffle_shop
```
> Configure profile:  https://docs.getdbt.com/docs/configure-your-profile

Options selected:
* bigquery
* service_account
* entered path/to/bq/keyfile.json **must enter full path, `~` did not work** see the screenshot in [step 4](https://docs.getdbt.com/guides/manual-install?step=4)
* entered project, dataset, threads, timeout, and lcation

> Tutorial differs, you don't have to create your own `profiles.yml` file. The `init` command took care of that.