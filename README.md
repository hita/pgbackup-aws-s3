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

TBD
