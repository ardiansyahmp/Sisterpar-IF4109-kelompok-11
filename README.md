# Sisterpar-IF4109---kelompok-11

1. Install microsoft MPI
https://msdn.microsoft.com/en-us/library/bb524831(v=vs.85).aspx
https://www.microsoft.com/en-us/download/details.aspx?id=55991
Sudah benar terinstall jika di command prompt dapat menampilkan:
C:>mpiexec.exe

2. Install mpi4py
pip install mpi4py

3. Jalankan 
mpiexec.exe -n 5 python hello_mpi.py

Lima buah proses akan berjalan secara paralel masing-masing menjalankan hello_mpi.py
