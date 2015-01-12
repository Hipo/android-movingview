# MovingView

MovingView is an Android library that provides endless scrolling effect for a given background image.


#Usage

You can simply add this view into your layout file. Available parameters are:

- Speed
- Src
- Direction

```
    <com.hipo.movingview.MovingView
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        app:speed="4"
        app:src="@drawable/ic_launcher"
        app:direction="y_Axis"/>
```

You can also pass these variables into a constructor:

```
    new MovingView(this,4,drawable);
```

#Installation

These steps are required for publishing aar file into your local repository. For further details see [here](https://www.linkedin.com/pulse/publishing-aar-local-repository-baris-emre-efe?trk=prof-post).

- Clone library into your workspace
- Modify build.gradle file and change the repository location
- Run
 
```
    sh ./gradlew uploadArchives
```

from Android Studio's terminal

Finally, add this dependency into your project

```
    compile 'com.hipo.movingview:library:+'
```

### Credits

MovingView is brought to you by Baris Emre Efe and the Hipo Team
