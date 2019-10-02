# CocoaPods-Alamofire
Installing CocoaPods and using Alamofire in a project.

## Getting Started 

-> Open Terminal and enter: 

    sudo gem install cocoapods 

-> Enter the following command in Terminal: 

    pod setup --verbose

## Installing The Alamofire Dependency 

-> Open Terminal and navigate to the project directory usinf cd command: 

    cd ~/Path/...
    
-> Enter the following command to create a Podfile to the project: 

    pod init 

-> Type the following command to open the Podfile: 

    open -a Xcode Podfile 
    
-> Delete the # before platform and delete other lines starting with #

-> Make sure to explicitly include use_frameworks! 

-> Add the following to the Podfile, right after use_frameworks!:

    pod 'Alamofire', '4.4.0'
    
-> Enter the following command in Terminal:

    pod install
    
-> Open the project folder using Finder and open the newly created .xcworkspace file 

-> Navigate throught your project and add the following where you wish to use Alamofire: 

    import Alamofire
