# HelloWorld
Simple Hello-World Swift App

For Vagrant:

run `vagrant up`
then `vagrant ssh`
then `cd /Project && swift build && ./build/debug/Project`


For Docker:

run `docker build -t "swiftaustin-docker-swift" .`
then `docker run -v ${PWD}:/Project "swiftaustin-docker-swift" bash -c "cd /Project && swift build && ./.build/debug/Project"`