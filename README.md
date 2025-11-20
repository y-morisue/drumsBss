# マイクロフォンアレイを用いたドラムセット音源分離のためのデータセット

## 概要
このデータセットは，マイクロフォンを用いてドラムセットの演奏を録音したものです．演奏に使用した楽器は，バスドラム(BD)，スネアドラム(SD)，ハイハットシンバル(HH)，クラッシュシンバル(CC)の4つです．マイクロフォンアレイでの録音に加え，各音源に1本ずつ近接モノラルマイクを設置しました．各マイクロフォンアレイと近接モノラルマイクは全て完全同期されています．

## フォルダ構成
~~~
drumsBss/
├── dataset/  # Folder to store input WAV files
│   └── drums1
│       └── take1
│           └── (64 files)
│       └── take2
│           └── (64 files)
│       └── take3
│           └── (64 files)
│   └── drums2
│       └── take1
│           └── (80 files)
│       └── take2
│           └── (80 files)
│       └── take3
│           └── (80 files)
│   └── drums3
│       └── take1
│           └── (80 files)
│       └── take2
│           └── (80 files)
│       └── take3
│           └── (80 files)
│   └── drums4
│       └── take1
│           └── (80 files)
│       └── take2
│           └── (80 files)
│       └── take3
│           └── (80 files)
├── score/
│    └── (4 files)
└── README.md
~~~

