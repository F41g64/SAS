<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:gravity="center"
    android:padding="16dp"
    android:background="@android:color/white">

    <!-- شعار SAS -->
    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="SAS"
        android:textSize="36sp"
        android:textColor="@android:color/black"
        android:layout_marginBottom="32dp"
        android:gravity="center"/>

    <!-- حقل إدخال الكود -->
    <EditText
        android:id="@+id/code_input"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:hint="أدخل الكود"
        android:inputType="text"
        android:layout_marginBottom="16dp"
        android:padding="10dp"
        android:background="@android:color/darker_gray"/>

    <!-- زر التأكيد -->
    <Button
        android:id="@+id/submit_button"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="تأكيد"
        android:background="@android:color/black"
        android:textColor="@android:color/white"/>

</LinearLayout>![20241005_070618](https://github.com/user-attachments/assets/bf73e73b-91ab-48c9-956f-ce9472e90663)
