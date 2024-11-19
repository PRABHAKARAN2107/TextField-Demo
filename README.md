package com.coding.meet.inputvalidationjc

import android.os.Bundle
import androidx.activity.ComponentActivity
import androidx.activity.compose.setContent
import androidx.activity.enableEdgeToEdge
import com.coding.meet.inputvalidationjc.ui.theme.InputValidationJCTheme

class MainActivity : ComponentActivity() {
    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        enableEdgeToEdge()
        setContent {
            InputValidationJCTheme {
                InputScreen()
            }
        }
    }
}






Final result demo video drive link :https://drive.google.com/file/d/1IZXdfVLAuEAgivRx5yK9VEFczABUKAje/view?usp=drive_link








