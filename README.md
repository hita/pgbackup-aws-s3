pgbackup
=======

CLI for backing up remote PosgreSQL databases locally or to AWS S3.


## Usage

Pass in a full database URL, storage driver and destination.

```
$ pgbackup postgres://bob@example.com:5432/db_one --driver s3 backups
```

## Instalation From Source

To install the package after you have cloned the repository, you will want to run the following command from within the project directory:

```
$ pip install --user -e .
```

## Preparing for Development

Follow these steps to srtart developing with this project:

1. Ensure `pip`and `pipenv`are installed
2. Clone repository `git clone git@github.com:hita/pgbackup`
3. `cd`into repository
4. Activate virtualenv: `pipenv shell`
5. Install dependencies: `pipenv install`
