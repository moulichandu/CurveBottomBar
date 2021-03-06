# Curve Bottom Bar

![Demo 1](screenshot1.png) ![Demo 2](demo2.gif)

# Download

#### Add it to your build.gradle with:
```gradle
allprojects {
    repositories {
        maven { url "https://jitpack.io" }
    }
}
```
and:

```gradle
dependencies {
	        implementation 'com.github.Akshay-Katariya:CurveBottomBar:1.0'
	}
```

# Usage
```
<com.akshay.library.CurveBottomBar
            android:id="@+id/curveBottomBar"
            android:layout_width="match_parent"
            android:layout_height="56dp"
            app:itemIconTint="@color/grey"
            android:layout_gravity="bottom"
            app:bottomBarColor="@color/yellow"
            app:curveRadius="25dp"/>
```

# Customization options 
```
app:bottomBarColor="@color/yellow"
app:curveRadius="25dp"
```

#### You can even set values at runtime:
```
private CurveBottomBar cbb;

cbb = findViewById(R.id.customBottomBar);

cbb.setBottomBarColor(getResources().getColor(R.color.yellow));
cbb.setCurveRadius(52);
```


Credit & Inspired by [IslamBesto](https://proandroiddev.com/how-i-drew-custom-shapes-in-bottom-bar-c4539d86afd7)

  