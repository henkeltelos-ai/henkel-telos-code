<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/main"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#0F2027"
    android:gravity="center"
    android:orientation="vertical"
    tools:context=".MainActivity">

    <androidx.cardview.widget.CardView
        android:layout_width="330dp"
        android:layout_height="wrap_content"
        android:layout_margin="20dp"
        app:cardBackgroundColor="#1A2E35"
        app:cardCornerRadius="24dp"
        app:cardElevation="16dp">

        <TableLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:padding="28dp"
            android:stretchColumns="0">

            <!-- Logo Row -->
            <TableRow
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:gravity="center">

                <ImageView
                    android:id="@+id/imgLogo"
                    android:layout_width="100dp"
                    android:layout_height="100dp"
                    android:src="@drawable/ic_launcher_foreground" />
            </TableRow>

            <!-- Title Row -->
            <TableRow
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:gravity="center"
                android:paddingTop="12dp"
                android:paddingBottom="16dp">

                <TextView
                    android:id="@+id/tvTitle"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:text="VIDAL DASHBOARD"
                    android:textColor="#FFFFFF"
                    android:textSize="18sp"
                    android:textStyle="bold" />
            </TableRow>

            <!-- Username Input Row -->
            <TableRow
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:paddingBottom="12dp">

                <EditText
                    android:id="@+id/etUsername"
                    android:layout_width="match_parent"
                    android:layout_height="48dp"
                    android:hint="Username"
                    android:inputType="textPersonName"
                    android:textColor="#FFFFFF"
                    android:textColorHint="#88FFFFFF" />
            </TableRow>

            <!-- Password Input Row -->
            <TableRow
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:paddingBottom="16dp">

                <EditText
                    android:id="@+id/etPassword"
                    android:layout_width="match_parent"
                    android:layout_height="48dp"
                    android:hint="Password"
                    android:inputType="textPassword"
                    android:textColor="#FFFFFF"
                    android:textColorHint="#88FFFFFF" />
            </TableRow>

            <!-- Button 1: superButton (Login / Navigate) -->
            <TableRow
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:paddingBottom="8dp">

            </TableRow>

            <!-- Button 2: btnRegister (Secondary Action) -->
            <TableRow
                android:layout_width="match_parent"
                android:layout_height="wrap_content">

                <Button
                    android:id="@+id/btnRegister"
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:backgroundTint="#37474F"
                    android:text="REGISTER"
                    android:textColor="#FFFFFF" />

                <Button
                    android:id="@+id/superButton"
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:backgroundTint="#00E676"
                    android:text="LOGIN"
                    android:textColor="#000000"
                    android:textStyle="bold" />
            </TableRow>

        </TableLayout>
    </androidx.cardview.widget.CardView>
</LinearLayout>
