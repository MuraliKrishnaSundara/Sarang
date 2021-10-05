# Sarang
With Sarang, you can listen to millions of songs and podcasts for free! Listen to artists you love and enjoy music and playlists in Hindi, English, Tamil, Telugu, and many more languages.


# Links 

* Blog-Post :- 

# 🔗Open-Source Library

* [Glide](https://github.com/bumptech/glide)
* [Retrofit](https://square.github.io/retrofit/)
* [Firebase](https://firebase.google.com/docs/auth)
* [AutoImageSlider](https://github.com/smarteist/Android-Image-Slider)
* [Jetpack](https://developer.android.com/jetpack)
* [NotificationBadge](https://github.com/nex3z/NotificationBadge)

# Things we used while making this application

* GitHub
* Firebase
* Recycler View
* Retrofit Library
* API
* Videoview
* Fragments
* Navigation

# Tech Stack ✨

* [Android Studio](https://developer.android.com/studio)
* [Java](https://www.java.com/en/)

# Clone this Repo To Your System Using Android Studio✨

* Step 1: Open your Android Studio then go to the File > New > Project from Version Control as shown in the below image.
* Step 2: After clicking on the Project from Version Control a pop-up screen will arise like below. In the Version control choose Git from the drop-down menu.
* Step 3: Then at last paste the link in the URL and choose your Directory. Click on the Clone button and you are done.

# Clone this Repo To Your System Using GitBash✨

* Open Git Bash

* If Git is not already installed, it is super simple. Just go to the Git Download Folder and follow the instructions.

* Go to the current directory where you want the cloned directory to be added.

* To do this, input cd and add your folder location. You can add the folder location by dragging the folder to Git bash.

* Go to the page of the repository that you want to clone

* Click on “Clone or download” and copy the URL.

* Use the git clone command along with the copied URL from earlier. $ git clone https://github.com/MuraliKrishnaSundara/BookMyShow.git

* Press Enter. $ git clone https://github.com/MuraliKrishnaSundara/BookMyShow.git Cloning into Git … remote: Counting objects: 13, done. remote: Compressing objects: 100% (13/13), done. remove: Total 13 (delta 1), reused 0 (delta 1) Unpacking objects: 100% (13/13), done.

Congratulations, you have created your first local clone from your remote Github repository.

Open Android Studio. Go to File > New > Project From Version Control. Copy the link of this repositary. Paste the link in Url Box of Android Studio window and click on "Clone" button.

# Dependencies 
    //General Dependencies
    implementation 'androidx.legacy:legacy-support-v4:1.0.0'
    implementation 'androidx.navigation:navigation-fragment-ktx:2.3.5'
    implementation 'androidx.navigation:navigation-ui-ktx:2.3.5'
    def anko_version = '0.10.0'
    def arch_version = '2.2.0-alpha01'

    implementation 'androidx.core:core-ktx:1.6.0'
    implementation 'androidx.appcompat:appcompat:1.3.1'
    implementation 'com.google.android.material:material:1.3.0-alpha02'
    implementation 'androidx.constraintlayout:constraintlayout:2.1.0'
    testImplementation 'junit:junit:4.+'
    androidTestImplementation 'androidx.test.ext:junit:1.1.3'
    androidTestImplementation 'androidx.test.espresso:espresso-core:3.4.0'

    //Anko
    implementation "org.jetbrains.anko:anko-commons:$anko_version"

    //Room
    implementation 'androidx.room:room-ktx:2.1.0'
    kapt 'androidx.room:room-compiler:2.1.0'

    // ViewModel and LiveData
    implementation "androidx.lifecycle:lifecycle-extensions:$arch_version"
    implementation "androidx.lifecycle:lifecycle-viewmodel-ktx:$arch_version"
    implementation "androidx.lifecycle:lifecycle-livedata-ktx:$arch_version"
    implementation "androidx.lifecycle:lifecycle-runtime-ktx:$arch_version"

    //Retrofit
    def retrofit2_version = "2.9.0"
    def okhttp3_version = "4.9.0"

    //retrofit
    implementation "com.squareup.retrofit2:retrofit:$retrofit2_version"
    implementation "com.squareup.retrofit2:converter-gson:$retrofit2_version"

    //Okhttp3
    implementation "com.squareup.okhttp3:okhttp:$okhttp3_version"
    // GSON library which is used to convert POJO to JSON and vice versa
    implementation 'com.squareup.retrofit2:converter-gson:2.6.1'
    // okhttp library used to observe the api call logs on LogCat
    implementation 'com.squareup.okhttp3:logging-interceptor:4.9.0'

    //hilt
    implementation("com.google.dagger:hilt-android:2.38.1")
    kapt("com.google.dagger:hilt-android-compiler:2.38.1")

    // material UI
    implementation 'com.google.android.material:material:1.5.0-alpha03'

    // Image Slider
    implementation 'com.github.smarteist:autoimageslider:1.4.0'

    //Circular Image View
    implementation 'de.hdodenhof:circleimageview:3.1.0'

    // glide
    implementation 'com.github.bumptech.glide:glide:4.12.0'
    annotationProcessor 'com.github.bumptech.glide:compiler:4.12.0'

    // Architectural Components
    implementation "androidx.lifecycle:lifecycle-viewmodel-ktx:2.2.0"

    // Lifecycle
    implementation "androidx.lifecycle:lifecycle-extensions:2.2.0"
    implementation "androidx.lifecycle:lifecycle-livedata-ktx:2.2.0"
    implementation "androidx.lifecycle:lifecycle-runtime:2.2.0"
    implementation "androidx.lifecycle:lifecycle-runtime-ktx:2.2.0"

    // Coroutines
    implementation 'org.jetbrains.kotlinx:kotlinx-coroutines-core:1.3.9'
    implementation 'org.jetbrains.kotlinx:kotlinx-coroutines-android:1.3.9'

    // Coroutine Lifecycle Scopes
    implementation "androidx.lifecycle:lifecycle-viewmodel-ktx:2.2.0"
    implementation "androidx.lifecycle:lifecycle-runtime-ktx:2.2.0"

    // Navigation Component
    implementation "androidx.navigation:navigation-fragment-ktx:2.3.0"
    implementation "androidx.navigation:navigation-ui-ktx:2.3.0"

    // Glide
    implementation 'com.github.bumptech.glide:glide:4.11.0'
    kapt 'com.github.bumptech.glide:compiler:4.11.0'

    // Activity KTX for viewModels()
    implementation "androidx.activity:activity-ktx:1.1.0"

    //Dagger - Hilt
    implementation "com.google.dagger:hilt-android:2.28-alpha"
    kapt "com.google.dagger:hilt-android-compiler:2.28-alpha"
    implementation "androidx.hilt:hilt-lifecycle-viewmodel:1.0.0-alpha02"
    kapt "androidx.hilt:hilt-compiler:1.0.0-alpha02"

    // Timber
    implementation 'com.jakewharton.timber:timber:4.7.1'

    // Firebase Firestore
    implementation 'com.google.firebase:firebase-firestore:23.0.3'

    // Firebase Storage KTX
    implementation 'com.google.firebase:firebase-storage-ktx:20.0.0'

    // Firebase Coroutines
    implementation 'org.jetbrains.kotlinx:kotlinx-coroutines-play-services:1.1.1'

    // ExoPlayer
    api "com.google.android.exoplayer:exoplayer-core:2.11.8"
    api "com.google.android.exoplayer:exoplayer-ui:2.11.8"
    api "com.google.android.exoplayer:extension-mediasession:2.11.8"

    // circular imageview
    implementation 'de.hdodenhof:circleimageview:3.1.0'

    // Gif ImageView
    implementation 'pl.droidsonroids.gif:android-gif-drawable:1.2.23'

    // otp pin view
    implementation 'com.chaos.view:pinview:1.4.3'

    //fire base
    implementation 'com.google.firebase:firebase-auth:21.0.1'

    //google authentication
    implementation 'com.google.android.gms:play-services-auth:19.2.0'

    //Razorpay
    //implementation 'com.razorpay:checkout:1.6.12'

    // GooglePay
    implementation 'com.google.android.gms:play-services-wallet:18.1.3'

# Lessons Learnt📚
