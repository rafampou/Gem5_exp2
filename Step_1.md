# Βήμα 1ο - Ερωτήματα

Η σειρά αυτών των ερωτημάτων αναφέρεται στην προσομοίωση των 5 Benchmarks που μας δόθηκαν **_(401.bzip2, 429.mcf, 456.hmmer, 458.sjeng, 470.lbm)_** που αποτελούν μέρος ρων Benchmarks της σειράς **Spec_cpu2006**

## Ερώτημα 1ο

Στο πρώτο ερώτημα μας ζητάει να εντοπίσουμε στα αρχεία εξόδου των προσομοιώσεών τα μεγέθη των caches, το associativity κάθε μίας από αυτές και το μέγεθος της cache line.

- **Specbzip**

Μέγεθος | Τιμή | Αναφορά σε αρχείο
----------------- | ----- | ------------------
L1 instruction cache | 32kB  |  [size=32768 - [config.ini]](/Step1_files/specbzip/config.ini#L845)
L1 Data caches  | 64kB  | [size=65536 - [config.ini]](/Step1_files/specbzip/config.ini#L179)
L2 Data caches  | 2MB | [size=2097152 - [config.ini]](/Step1_files/specbzip/config.ini#L1050)
Associativity L1 instruction cache  | 2 | [assoc=2 - [config.ini]](/Step1_files/specbzip/config.ini#L832)
Associativity L1 data cache | 2 | [assoc=2 - [config.ini]](/Step1_files/specbzip/config.ini#L159)
Associativity L2 data cache | 2 | [assoc=8 - [config.ini]](/Step1_files/specbzip/config.ini#L1037)
Cacheline size  | 64kB |  [cache_line_size=65536 - [config.ini]](/Step1_files/specbzip/config.ini#L15)

- **Spechmmer**

Μέγεθος | Τιμή | Αναφορά σε αρχείο
----------------- | ----- | ------------------
L1 instruction cache | |
L1 Data caches  | |
L2 Data caches  | |
Associativity L1 instruction cache  | |
Associativity L1 data cache | |
Associativity L2 data cache | |
Cacheline size  | |

- **Speclibm**

Μέγεθος | Τιμή | Αναφορά σε αρχείο
----------------- | ----- | ------------------
L1 instruction cache | |
L1 Data caches  | |
L2 Data caches  | |
Associativity L1 instruction cache  | |
Associativity L1 data cache | |
Associativity L2 data cache | |
Cacheline size  | |

- **Specmcf**

Μέγεθος | Τιμή | Αναφορά σε αρχείο
----------------- | ----- | ------------------
L1 instruction cache | |
L1 Data caches  | |
L2 Data caches  | |
Associativity L1 instruction cache  | |
Associativity L1 data cache | |
Associativity L2 data cache | |
Cacheline size  | |

- **Specsjeng**

Μέγεθος | Τιμή | Αναφορά σε αρχείο
----------------- | ----- | ------------------
L1 instruction cache | |
L1 Data caches  | |
L2 Data caches  | |
Associativity L1 instruction cache  | |
Associativity L1 data cache | |
Associativity L2 data cache | |
Cacheline size  | |

- **Specbzip**

Μέγεθος | Τιμή | Αναφορά σε αρχείο
----------------- | ----- | ------------------
L1 instruction cache | |
L1 Data caches  | |
L2 Data caches  | |
Associativity L1 instruction cache  | |
Associativity L1 data cache | |
Associativity L2 data cache | |
Cacheline size  | |
