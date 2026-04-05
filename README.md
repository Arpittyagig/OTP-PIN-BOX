OTP PIN BOX

How to Add this into your 

<img width="1080" height="2340" alt="Screenshot_1775398718" src="https://github.com/user-attachments/assets/ba11cb41-5c48-4ef6-9d55-c6e84de98dc3" />

To get a Git project into your build:

Step 1. Add the JitPack repository to your build file

gradle![Uploading Screenshot_1775398718.png…]()

gradle.kts
maven
sbt
leiningen
Add it in your settings.gradle.kts at the end of repositories:

	dependencyResolutionManagement {
		repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
		repositories {
			mavenCentral()
			maven { url = uri("https://jitpack.io") }
		}
	}
Step 2. Add the dependency

	dependencies {
	        implementation("com.github.Arpittyagig:OTP-PIN-BOX:1.0.2")
	}




  [![](https://jitpack.io/v/Arpittyagig/OTP-PIN-BOX.svg)](https://jitpack.io/#Arpittyagig/OTP-PIN-BOX)
