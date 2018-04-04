# 
# Inventário de dados abertos da Hackatona de Mobilidade Urbana (HackEMTU)
#
# Fork do projeto [Unicamp Open Data Project](https://maronato.github.io/transparencia-data-catalog/)
#

## Running the website

To set up our website, run the following in your terminal. You'll need to have Ruby installed (it's pre-installed on macOS and most Linux distributions.)

```
git clone https://github.com/jmfly/hackemtu-data-catalog.git
cd hackemtu-data-catalog
sudo gem install bundler
bundle install
```

To run:

```
bundle exec jekyll serve
```

Or, as a shortcut, just do `chmod +x run.sh` once, then run

```
./run.sh
```

Anytime you want to start the app.
