## File -Manipulation-System.IO
File and stream I/O in .NET is the process of reading from and writing to files and data streams. 

## Files and Directories:
- The File class provides static methods for creating, copying, deleting, moving, and opening files.
- The FileInfo class provides instance methods for working with files and retrieving file properties.
- The Directory class offers static methods for working with directories, such as creating, moving, and enumerating through directories and subdirectories.

## Streams:
- The Stream class is an abstract base class that represents a sequence of bytes. All stream classes inherit from this base class.
- IsolatedStorageFileStream is used for reading from and writing to a file in isolated storage.
- FileStream is used for reading from and writing to files.

## Readers and Writers:
- The System.IO namespace provides classes for reading encoded characters from streams and writing them to streams.
- BinaryReader and BinaryWriter are used for reading and writing binary data types.
- StreamReader and StreamWriter are used for reading and writing characters using an encodin

## Asynchronous I/O operations:
- Asynchronous operations are recommended when performing resource-intensive I/O tasks to keep the application responsive.
- Asynchronous methods, marked with "Async" in their names, are available for reading, writing, copying, and flushing streams.

## Compression:
- The System.IO.Compression namespace contains classes for compressing and decompressing files and streams.
- The ZipArchive, ZipArchiveEntry, and ZipFile classes are commonly used for working with zip archives.

## Isolated Storage:
- Isolated storage provides a mechanism for storing application-specific data in a controlled and isolated manner.
- IsolatedStorageFile and IsolatedStorageFileStream classes are used for working with isolated storage.
