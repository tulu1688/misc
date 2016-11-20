# Install R and Rstudio

## Get the latest R version
~~~~~~
sudo apt-key adv –keyserver keyserver.ubuntu.com –recv-keys E084DAB9
sudo add-apt-repository ‘deb http://star-www.st-andrews.ac.uk/cran/bin/linux/ubuntu trusty/’
sudo apt-get update
sudo apt-get install r-base
~~~~~~

## Download and install RStudio
~~~~~~
wget http://download1.rstudio.org/rstudio-0.98.1062-amd64.deb
sudo dpkg -i *.deb
rm *.deb
~~~~~~

* Note: fix bug of installing rstudio "sudo apt-get install libgstreamer-plugins-base0.10-dev"
