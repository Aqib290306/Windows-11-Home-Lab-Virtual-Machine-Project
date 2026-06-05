# Troubleshooting Log

## Issue 1 - No Internet Connection
<img width="1908" height="1079" alt="image" src="https://github.com/user-attachments/assets/badaba8d-b2fb-4f8c-a2f6-283f32a8e150" />


### Problem

No internet access.

### Investigation

Checked network settings.

### Cause

Network adapter disabled.
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/740042a5-91ce-4471-a2bd-dc977dc3e675" />


### Resolution

Re-enabled adapter.
<img width="1911" height="1079" alt="image" src="https://github.com/user-attachments/assets/62bbcbb7-8bfe-4db6-82ad-78e08af749f3" />


### Verification

Successfully pinged google.com.
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/93f715da-c58f-4626-b887-6d3a497e2c58" />

This pinging command shows that the internet connection is actually working.

### Lessons Learned

Network adapter status should be checked early when diagnosing connectivity issues.



## Issue 2 - Software Installation Failure

### Problem

User was unable to install software.
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/99e1cf8a-4f15-4f96-a3cf-5c038f865f07" />


### Investigation

Checked account permissions and user type.
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/82ff0511-3fd6-479a-b726-74bc76361da7" />


### Root Cause

The user account did not have administrator privileges and was only considered a standard local account, therefore cannot download anything.

### Resolution

Installed software using an administrator account.
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/94389554-6a03-4d84-9a64-94734cb8b4de" />


### Verification

Software installed and launched successfully.
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/8d79ee45-516e-4bd9-b43b-f9d748109233" />


### Lessons Learned

Administrative permissions are required for many software installations.



## Issue 3 - Application Unexpectedly Closed

### Problem

Application (Notepad) closed unexpectedly during use.

### Investigation

Reviewed running processes using Task Manager. (Notepad not running)
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/d63d8f52-367e-4c5d-bcc6-f0867a0d7563" />


### Root Cause

The application process had terminated.

### Resolution

Restarted the application.

### Verification

Application opened and operated normally.
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/3665e627-39ce-4d23-96a9-ef32cc029396" />

### Lessons Learned

Task Manager is useful for investigating application-related issues.




## Issue 4 - Incorrect System Date and Time

### Problem

System displayed an incorrect date and time.
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/0580ef89-4de2-41b3-bfd6-aee4963c3aa6" />


### Investigation

Reviewed date and time settings.
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/0883411c-cdaf-4c6c-9f01-55dfe64003b8" />


### Root Cause

Automatic time synchronisation was disabled.
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/fcf85cb1-d8f1-42f3-b16f-c7082359a90c" />


### Resolution

Re-enabled automatic date and time settings.
<img width="1913" height="1079" alt="image" src="https://github.com/user-attachments/assets/c298f9b5-42e7-4eda-8f06-6f83f83c138b" />


### Verification

System time updated correctly.
<img width="1918" height="1079" alt="image" src="https://github.com/user-attachments/assets/2872fac8-5a22-44c0-a3ac-a38d89f2919c" />


### Lessons Learned

Incorrect system time can be misleading and confuse users.
