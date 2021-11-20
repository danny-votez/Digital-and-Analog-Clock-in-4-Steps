## Digital and Analog Clock Displays in Android Studio
- View class has key subclasses that can make one's work easier
- One is the Digital clock and the Analog clock subclasses
- In the Analog clock, it depicts numbers 1-12 with two-hands
- The shorter for hour, while the longer for minutes
- The Digital clock view, which is also a subclass of View class uses numbers
- The Digital clock displays time in the format "HH:MM"

### Steps
- Start Android studio and select empty layout, click <strong>finish</strong>
- Change layout to "RelativeLayout" layout
- Add two Views, "AnalogClock" and "DigitalClock"
- Customize layouts as desired, fix constraints, add text color and background as desired
- Run emulator to see <strong>Results</strong>
### Layout Script

<code>
  <pre>
  
<RelativeLayout    
    
    
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#D50000"
    tools:context=".MainActivity">


    <AnalogClock
        android:layout_width="265dp"
        android:layout_height="245dp"
        android:layout_centerHorizontal="true"
        android:layout_marginStart="120dp"
        android:layout_marginTop="80dp"
        android:background="#FFD600" />

    <DigitalClock
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_alignParentBottom="true"
        android:layout_centerHorizontal="true"
        android:layout_marginStart="140dp"
        android:layout_marginTop="149dp"
        android:layout_marginBottom="226dp"
        android:background="#000407"
        android:textAlignment="center"
        android:textColor="#FBFBFB"
        android:textSize="50sp"
        android:textStyle="bold" />


</ RelativeLayout>

</code>
</pre>

#### Sample Display
<img src="https://user-images.githubusercontent.com/77758884/142721872-9f2c2e8a-5af9-4202-afe6-d968e5eb482c.png" width=200px />
