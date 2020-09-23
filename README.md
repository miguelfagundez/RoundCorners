# RoundCorners
Round corners examples using TextViews, EditTexts, ImageViews, Buttons, and CardViews.

## Create a Drawable file (shape): 

Include color and radius.

```
<?xml version="1.0" encoding="utf-8"?>
<shape xmlns:android="http://schemas.android.com/apk/res/android"
    android:shape="rectangle">

    <solid android:color="#4D50FF"/>
    <corners android:radius="10dp"/>
</shape>
```

## Include the drawable file in each view (TextView, Button, and EditText) using android:background attribute 

```
    <TextView
        ...
        ...
        android:background="@drawable/textview_roundcorners"
        ...
        ... />
```

## Use a CardView as constainer for ImageView

Include cardCornerRadius as attribute.

```
    <androidx.cardview.widget.CardView
        android:id="@+id/cardView"
        app:cardCornerRadius="20dp"
        ...
        ...>

        <ImageView
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:src="@drawable/code"
            android:scaleType="centerCrop"/>
            
    </androidx.cardview.widget.CardView>
```

### Checking code for details.

## Visual result:
<p align = "center">
<img src="/images/01.png" width="300">
</p>
