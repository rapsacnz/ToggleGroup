A group of ToggleButtons - much like a RadioGroup.

Uses the RadioGroup source code, Modified to accept a ToggleButton rather than a RadioButton.

Usage:


<com.rapsacnz.ToggleGroup
    android:id="@+id/deal_detail_toolbar"
    android:layout_width="fill_parent"
    android:layout_height="60dip"
    android:layout_alignParentBottom="true"
    android:background="@drawable/bgnd_toggle_button">
    <ToggleButton
        android:id="@+id/b1"
        android:textOn="@string/tab_1_label"
        android:textOff="@string/tab_1_label"
        android:textSize="10sp"
        android:textColor="@color/tab_button_color"
        android:checked="true"
        android:layout_width="fill_parent"
        android:layout_height="60dp"
        android:layout_weight="1"
        android:drawableTop="@drawable/toggle_spotlight"
        android:drawablePadding="-5dp "
        android:gravity="bottom|center"
        android:paddingTop="10dp"
        android:paddingBottom="5dp"
        android:background="@drawable/bgnd_transparent" />
    <ToggleButton
        android:id="@+id/b2"
        android:textOn="@string/tab_2_label"
        android:textOff="@string/tab_2_label"
        android:textSize="10sp"
        android:textColor="@color/tab_button_color"
        android:checked="false"
        android:layout_width="fill_parent"
        android:layout_height="60dp"
        android:layout_weight="1"
        android:drawableTop="@drawable/toggle_browse"
        android:gravity="bottom|center"
        android:paddingTop="10dp"
        android:paddingBottom="5dp"
        android:background="@drawable/bgnd_transparent" />

    <ToggleButton
        android:id="@+id/b3"
        android:textOn="@string/tab_3_label"
        android:textOff="@string/tab_3_label"
        android:textSize="10sp"
        android:textColor="@color/tab_button_color"
        android:checked="false"
        android:layout_width="fill_parent"
        android:layout_height="60dp"
        android:layout_weight="1"
        android:drawableTop="@drawable/toggle_purchased"
        android:gravity="bottom|center"
        android:paddingTop="10dp"
        android:paddingBottom="5dp"
        android:background="@drawable/bgnd_transparent" />


</com.rapsacnz.ToggleGroup>
