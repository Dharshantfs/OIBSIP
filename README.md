<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/activity_main"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:paddingBottom="@dimen/activity_vertical_margin"
    android:paddingLeft="@dimen/activity_horizontal_margin"
    android:paddingRight="@dimen/activity_horizontal_margin"
    android:paddingTop="@dimen/activity_vertical_margin"
    tools:context="abhiandroid.com.calculater.MainActivity"
    android:orientation="vertical"
    android:gravity="top"
    android:textAlignment="center"
    android:background="@android:color/holo_blue_bright"
    android:weightSum="1">

    <TextView
        android:text="@string/enter_two_numbers"
        android:layout_width="match_parent"
        android:id="@+id/textView"
        android:layout_height="30dp"
        android:gravity="center_horizontal"
        android:textColorLink="?android:attr/editTextColor"
        tools:textStyle="bold|italic"
        android:textStyle="bold|italic"
        android:fontFamily="serif"
        android:visibility="visible"
        android:textSize="24sp"
        android:layout_weight="0.07" />

    <EditText
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:inputType="number"
        android:ems="10"
        android:id="@+id/editOp1"
        android:textSize="18sp"
        android:gravity="center_horizontal"
        android:layout_marginBottom="5dp"
        android:visibility="visible" />
    
   <EditText
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:inputType="number"
        android:ems="10"
        android:id="@+id/editOp2"
        android:textSize="18sp"
        android:gravity="center_horizontal"
        android:elevation="1dp" />
</LinearLayout>
