# Tugas 1

Jawablah pertanyaan berikut ini dengan singkat dan jelas
1. Sebutkan 3 jenis tipe variabel di dalam Python
    * Jawab: 1. Tipe data string
             2. Tipe data integer
             3. Tipe data boolean
2. Jelaskan mengapa di Python ada aturan Indentation?
    * Jawab: Karena jika tidak sesuai aturan Indentation, maka akan terjadi error. Contoh :
Here is an example of a correctly (though confusingly) indented piece of Python code:

    def perm(l):
      if len(l) <= 1:
    return [l]
    r = []
    for i in range(len(l)):
             s = l[:i] + l[i+1:]
             p = perm(s)
             for x in p:
             r.append(l[i:i+1] + x)
    return r

The following example shows various indentation errors:

     def perm(l):                       # error: first line indented
    for i in range(len(l)):             # error: not indented
        s = l[:i] + l[i+1:]
            p = perm(l[:i] + l[i+1:])   # error: unexpected indent
            for x in p:
                    r.append(l[i:i+1] + x)
                return r                # error: inconsistent dedent
    
## Membuat Program Sederhana

Buatlah program untuk mengecek apakah sebuah bilangan itu genap atau ganjil. Uploadlah file *.ipynb * nya

