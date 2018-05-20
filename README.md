# CreateFileHandle
#### Консольное приложение, C++

*main.cpp*: определяет точку входа для консольного приложения.

Приложение создает текстовый файл *Hello.txt*, используя фукуцию **CreateFile()**

В текстовый файл записывается путь (место с которого выполняется запуск приложения) используя фукуции **WriteFile()** и **GetCurrentDirectory()**;

Файловые дескрипторы закрываются с помощью функции **CloseHandle()**

В случае успешного создания или открытия файла, процедура **CreateFile()** возвращает его хэндл.

В случае ошибки возвращается специальное значение **INVALID_HANDLE_VALUE**.

Подробности об ошибке выводятся с помощью функции **GetLastError()**.

-----------------------------------------------------------------------------------------------------
#### Console application, C ++

*main.cpp*: Specifies the entry point for the console application.

The application creates a text file *Hello.txt*, using the function **CreateFile()**

A text file (path from which the application is launched) is written to the text file using the functions **WriteFile()** and **GetCurrentDirectory()**;

File descriptors are closed using the **CloseHandle()** function

If the file is created or opened successfully, the procedure **CreateFile()** returns its handle.

In case of an error, a special value **INVALID_HANDLE_VALUE** is returned.

Details about the error are displayed using the function **GetLastError()**.
