# TextMate Bundle for Mongoid Development

To install with Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com/carlosbrando/mongoid.tmbundle.git Mongoid.tmbundle
    osascript -e 'tell app "TextMate" to reload bundles'


To install without Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    wget http://github.com/carlosbrando/mongoid.tmbundle/tarball/master
    tar zxf carlosbrando-mongoid.tmbundle*.tar.gz
    rm carlosbrando-mongoid.tmbundle*.tar.gz
    mv carlosbrando-mongoid.tmbundle* "Ruby on Rails.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'
