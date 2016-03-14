# BuildSystemTest

Sandbox for testing Android build flavors based on information/sample at 
http://developer.android.com/tools/building/configuring-gradle.html

1. Create sample project
2. Add in the product flavors 
    productFlavors {
        demo {
            applicationId "com.crookedsquareapps.buildsystemtest.app.demo"
            versionName "1.0-demo"
        }
        full {
            applicationId "com.crookedsquareapps.buildsystemtest.app.full"
            versionName "1.0-full"
        }
    }
3. 
