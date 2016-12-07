# Android2.2
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/activity_main"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:paddingBottom="@dimen/activity_vertical_margin"
    android:paddingLeft="@dimen/activity_horizontal_margin"
    android:paddingRight="@dimen/activity_horizontal_margin"
    android:paddingTop="@dimen/activity_vertical_margin"
    tools:context="com.example.pankaj.assignments.MainActivity">

    <EditText
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:inputType="textPersonName"
        android:ems="10"
        android:layout_alignParentTop="true"
        android:layout_toEndOf="@+id/textView"
        android:layout_marginStart="58dp"
        android:id="@+id/editText" />

    <TextView
        android:text="Enter Yearly Interest Rate(%)"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@+id/editText"
        android:layout_alignStart="@+id/textView"
        android:layout_marginTop="42dp"
        android:id="@+id/textView2" />

    <EditText
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:inputType="textPersonName"
        android:ems="10"
        android:layout_below="@+id/editText"
        android:layout_alignStart="@+id/editText"
        android:layout_marginTop="31dp"
        android:id="@+id/editText2" />

    <TextView
        android:text="Enter Minimum payment($)"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@+id/editText2"
        android:layout_alignStart="@+id/textView2"
        android:layout_marginTop="23dp"
        android:id="@+id/textView3" />

    <EditText
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:inputType="textPersonName"
        android:ems="10"
        android:layout_below="@+id/editText2"
        android:layout_toEndOf="@+id/textView3"
        android:layout_marginTop="12dp"
        android:id="@+id/editText3"
        android:layout_alignStart="@+id/editText2" />

    <TextView
        android:text="Final Card Balance($)"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@+id/editText3"
        android:layout_alignStart="@+id/textView3"
        android:layout_marginTop="31dp"
        android:id="@+id/textView4" />

    <EditText
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:ems="10"
        android:layout_alignBottom="@+id/textView4"
        android:layout_alignParentEnd="true"
        android:id="@+id/editText4"
        android:layout_alignStart="@+id/editText3" />

    <TextView
        android:text="Months Remaining"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@+id/textView4"
        android:layout_alignStart="@+id/textView4"
        android:layout_marginStart="11dp"
        android:layout_marginTop="50dp"
        android:id="@+id/textView5" />

    <EditText
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:inputType="textPersonName"
        android:ems="10"
        android:layout_below="@+id/editText4"
        android:layout_marginTop="37dp"
        android:id="@+id/editText5"
        android:layout_alignStart="@+id/editText6" />

    <TextView
        android:text="Intrest Paid will be($)"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@+id/editText5"
        android:layout_alignStart="@+id/textView5"
        android:layout_marginTop="11dp"
        android:id="@+id/textView6" />

    <EditText
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:inputType="textPersonName"
        android:ems="10"
        android:layout_below="@+id/editText5"
        android:layout_alignStart="@+id/editText4"
        android:id="@+id/editText6" />

    <Button
        android:text="Compute"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_below="@+id/editText6"
        android:layout_centerHorizontal="true"
        android:id="@+id/button" />

    <Button
        android:text="Clear"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_alignParentBottom="true"
        android:layout_centerHorizontal="true"
        android:layout_marginBottom="15dp"
        android:id="@+id/button2" />

    <TextView
        android:text="Enter Card Balance ($)"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:id="@+id/textView"
        android:layout_above="@+id/textView2"
        android:layout_alignParentStart="true" />
</RelativeLayout>
