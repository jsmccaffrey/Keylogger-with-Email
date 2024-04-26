# Keylogger with Email

Keystroke Monitoring System written in C# for Windows  
When deployed, logs will be sent to email of choosing  

Created and used for _**educational purposes only**_

    Utilized IntPtr, WH_KEYBOARD_LL, WM_KEYDOWN, LowLevelKeyboardProc, wParam, and lParam to intercept keystrokes securely
    Operated stealthily by employing SetWindowsHookEx, CallNextHookEx, and UnhookWindowsHookEx functions
