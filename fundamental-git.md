// GIT

- yaitu sebuah version control system untuk mencatat dan mengatur perubahan pada kode/program

- Git command (local):

  - $ git init
  - $ git add <file(s)>
  - $ git add . (untuk menambahkan seluruh file ke staging area)
  - $ git status
  - $ git commit
  - $ git config

  - $ git branch (melihat branch yg dimiliki)

    - $ git branch <nama_branch> (membuat new branch)
    - $ git checkout <nama_branch> (untuk berpindah antar branch)

  - $ git help
  - $ git log (untuk mentracking perubahan)

    - $ git log -2 (mentracking 2 perubahan terakhir)
    - git log --all --decorate --oneline --graph (memperlihatkan visualisasi branch dalam bentuk graph)
      - untuk memudahkan bisa memakai ini: alias graph="git log --all --decorate --oneline --graph"

  - git checkout (untuk mengembalikan file yg hilang)

    - git checkout 7982b -- <file(s)>
      - 7982b itu adalah hash yg dimiliki saat commit
        - diambil 5 huruf / angka pertama

  - Jika posisi file nya M / modified maka bisa langsung commit tanpa add dulu

    - git commit -a -m / git commit -am "message.."

  - Merge

    - Fast Forward

      - $ git merge <nama_branch> (untuk menyatukan branch satu dgn lainnya)
      - $ git branch --merged (untuk melihat branch mana yg sudah disatukan)
      - $ git branch -d <nama_branch> (untuk menghapus branch yg sudah di merge)
      - $ git branch -d <nama_branch> (untuk menghapus branch yg belum di merge)

    - Three-way Merge

- 3 Area pada repo Git:
  - Working tree
  - Staging area
  - History

// GITHUB

- platform online untuk menyimpan repository / folder berbasis cloud

// Hubungan antara Git dan Github

- Git itu mesinnya, sedangkan Github itu platformnya

// Istilah penting

- Repository (repo): wadah/project yang dilacak dengan Git.
- Commit: catatan perubahan kode.
- Branch: cabang kode (misal branch main, dev).
- Merge: gabung branch.
- Clone: download repo dari GitHub.
- Push: upload perubahan ke GitHub.
- Pull: ambil update dari GitHub.
- Fork: Copy repo orang lain ke akun GitHub lo. Berguna kalau mau kontribusi ke open source.
- Pull Request (PR): Permintaan buat ngegabungin perubahan branch (biasanya setelah fork/kerja tim).
