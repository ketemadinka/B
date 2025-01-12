# B
XML code for student registration 
<?xml version="1.0" encoding="utf-8"?>
<ScrollView xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#FFFFFF">

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="vertical"
        android:padding="16dp"
        android:gravity="center_horizontal">
        <ImageView
            android:id="@+id/university_logo"
            android:layout_width="150dp"
            android:layout_height="150dp"
            android:src="@drawable/your_logo_image"
            android:contentDescription="University Logo"
            android:layout_marginBottom="16dp" />
        <TextView
            android:id="@+id/student_register_title"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="STUDENT REGISTER"
            android:textColor="#6A1B9A"
            android:textStyle="bold"
            android:textSize="20sp"
            android:layout_marginBottom="16dp" />
        <EditText
            android:id="@+id/name_input"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:hint="Name"
            android:drawableStart="@drawable/ic_person"
            android:padding="12dp"
            android:background="@drawable/edittext_background"
            android:layout_marginBottom="12dp" />
        <EditText
            android:id="@+id/roll_no_input"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:hint="Roll No"
            android:drawableStart="@drawable/ic_roll_number"
            android:padding="12dp"
            android:background="@drawable/edittext_background"
            android:layout_marginBottom="12dp" />
        <EditText
            android:id="@+id/class_input"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:hint="Class"
            android:drawableStart="@drawable/ic_class"
            android:padding="12dp"
            android:background="@drawable/edittext_background"
            android:layout_marginBottom="12dp" />
        <EditText
            android:id="@+id/email_input"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:hint="Email"
            android:drawableStart="@drawable/ic_email"
            android:padding="12dp"
            android:background="@drawable/edittext_background"
            android:layout_marginBottom="12dp" />
        <EditText
            android:id="@+id/password_input"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:hint="Password"
            android:drawableStart="@drawable/ic_password"
            android:padding="12dp"
            android:background="@drawable/edittext_background"
            android:inputType="textPassword"
            android:layout_marginBottom="16dp" />
        <Button
            android:id="@+id/register_button"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="REGISTER"
            android:backgroundTint="#6A1B9A"
            android:textColor="#FFFFFF"
            android:layout_marginBottom="12dp" />
        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:orientation="horizontal"
            android:gravity="center"
            android:layout_marginTop="8dp">
            <TextView
                android:id="@+id/forgot_password"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="Forget Password?"
                android:textColor="#6A1B9A"
                android:layout_marginEnd="8dp" />
            <TextView
                android:id="@+id/sign_in_link"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="Sign In"
                android:textColor="#6A1B9A"
                android:textStyle="bold" />
        </LinearLayout>
    </LinearLayout>
</ScrollView>
