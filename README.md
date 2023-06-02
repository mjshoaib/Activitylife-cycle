# Activitylife-cycle
java file-
package com.example.activitylifecycle;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;
import android.util.Log;
import android.widget.Toast;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        Log.d("ActivityLifecycle: ","onCreate() Called");
        Toast.makeText(this, "onCreate() Called", Toast.LENGTH_SHORT).show();
    }

    @Override
    protected void onStart() {
        super.onStart();
        Log.d("ActivityLifecycle: ","onStart() Called");
        Toast.makeText(this, "onStart() Called", Toast.LENGTH_SHORT).show();
    }

    @Override
    protected void onResume() {
        super.onResume();
        Log.d("ActivityLifecycle: ","onResume() Called");
        Toast.makeText(this, "onResume() Called", Toast.LENGTH_SHORT).show();
    }

    @Override
    protected void onPause() {
        super.onPause();
        Log.d("ActivityLifecycle: ","onPause() Called");
        Toast.makeText(this, "onPause() Called", Toast.LENGTH_SHORT).show();
    }

    @Override
    protected void onRestart() {
        super.onRestart();
        Log.d("ActivityLifecycle: ","onRestart() Called");
        Toast.makeText(this, "onRestart() Called", Toast.LENGTH_SHORT).show();
    }

    @Override
    protected void onStop() {
        super.onStop();
        Log.d("ActivityLifecycle: ","onStop() Called");
        Toast.makeText(this, "onStop() Called", Toast.LENGTH_SHORT).show();
    }

    @Override
    protected void onDestroy() {
        super.onDestroy();
        Log.d("ActivityLifecycle: ","onDestroy() Called");
        Toast.makeText(this, "onDestroy() Called", Toast.LENGTH_SHORT).show();
    }
}
