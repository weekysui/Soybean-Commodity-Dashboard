web: gunicorn app:app
vagrant up
vagrant ssh
sudo rm /edx/var/mongo/mongodb/mongod.lock
sudo mongod -repair --config /etc/mongodb.conf
sudo chown -R mongodb:mongodb /edx/var/mongo/mongodb/.
sudo start mongodb