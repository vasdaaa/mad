# <?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#BD7474"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="100dp"
        android:layout_height="50dp"
        android:text="Name"
        android:textStyle="bold"
        android:textColor="@color/black"
        android:background="@drawable/shape1"
        android:textSize="20dp"
        android:padding="15dp"
        android:layout_marginLeft="40dp"
        android:id="@+id/n1" />
    <TextView
        android:layout_width="100dp"
        android:layout_height="50dp"
        android:background="@drawable/shape1"
        android:text="Roll no"
        android:textStyle="bold"
        android:textColor="@color/black"
        android:padding="15dp"
        android:textSize="20dp"
        android:layout_marginLeft="40dp"
        android:id="@+id/n2"
        android:layout_below="@+id/n1" />
    <TextView
        android:layout_width="100dp"
        android:layout_height="50dp"
        android:text="Branch"
        android:textStyle="bold"
        android:background="@drawable/shape1"
        android:textColor="@color/black"
        android:textSize="20dp"
        android:padding="15dp"
        android:layout_marginLeft="40dp"
        android:layout_below="@id/n2"
        android:id="@+id/n3" />
    <TextView
        android:layout_width="100dp"
        android:layout_height="50dp"
        android:text="Year"
        android:textSize="20dp"
        android:textStyle="bold"
        android:background="@drawable/shape1"
        android:textColor="@color/black"
        android:padding="15dp"
        android:layout_marginLeft="40dp"
        android:layout_below="@id/rg"
        android:id="@+id/n4" />
    <EditText
        android:layout_width="200dp"
        android:layout_height="50dp"
        android:layout_toRightOf="@id/n1"
        android:background="@drawable/shape1"
        android:id="@+id/eee"
        />
    <EditText
        android:layout_width="200dp"
        android:layout_height="50dp"
        android:layout_toRightOf="@id/n2"
        android:background="@drawable/shape1"
        android:layout_below="@id/n1"
        android:id="@+id/eee1"/>
    <RadioGroup
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:id="@+id/rg"
        android:layout_toRightOf="@id/n3"
        android:layout_below="@id/n2">
        <RadioButton
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="CSE"
            android:textSize="20dp"
            android:id="@+id/rb1"/>
        <RadioButton
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="ECE"
            android:textSize="20dp"
            android:id="@+id/rb2"/>
        <RadioButton
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="CCE"
            android:textSize="20dp"
            android:id="@+id/rb3"/>





    </RadioGroup>
    <CheckBox
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="1st Year"
        android:layout_below="@id/rg"
        android:layout_toRightOf="@id/n4"
        android:textSize="20sp"
        android:id="@+id/cb1"/>
    <CheckBox
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="2nd Year"
        android:layout_below="@id/cb1"
        android:layout_toRightOf="@id/n4"
        android:textSize="20sp"
        android:id="@+id/cb2"/>
    <CheckBox
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="3rd Year"
        android:layout_below="@id/cb2"
        android:layout_toRightOf="@id/n4"
        android:textSize="20sp"
        android:id="@+id/cb3"/>
    <CheckBox
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="4th Year"
        android:layout_below="@id/cb3"
        android:layout_toRightOf="@id/n4"
        android:textSize="20sp"
        android:id="@+id/cb4"/>
    <Button
        android:id="@+id/btn"
        android:layout_width="150dp"
        android:layout_height="wrap_content"
        android:layout_below="@+id/cb4"
        android:backgroundTint="@color/black"
        android:layout_centerHorizontal="true"
        android:layout_marginTop="20dp"
        android:text="Submit" />

</RelativeLayout>
