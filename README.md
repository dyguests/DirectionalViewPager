#DirectionalViewPager

A DirectionalViewPager(VerticalViewPager + ViewPager) can work in new Support V4.

fix some code.

1.this project is base on[JakeWharton/Android-DirectionalViewPager](https://github.com/JakeWharton/Android-DirectionalViewPager).

2.some code is base on [stackoverflow](http://stackoverflow.com/questions/10720276/error-including-android-directionalviewpager-jar-in-eclipse/14268702#14268702)



#Useage

##Step1.

    compile 'com.android.support:support-v4:23.1.0'

##Step2.

copy package android.support.v4.view(with file DirectionalViewPager.java ,VerticalViewPagerCompat.java) to your project.
    
*Do not change package name!!!*

##Step3.

in xml:

       <android.support.v4.view.DirectionalViewPager
            android:id="@+id/container"
            android:layout_width="match_parent"
            android:layout_height="match_parent"/>
            
##Step4.

change orientation

    mViewPager.setOrientation(DirectionalViewPager.VERTICAL);
    mViewPager.setOrientation(DirectionalViewPager.HORIZONTAL);
    
#License

[show JakeWharton/Android-DirectionalViewPager license](https://github.com/JakeWharton/Android-DirectionalViewPager)