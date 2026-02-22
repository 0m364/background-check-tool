# Merge Instructions

The contents of this repository have been prepared for merging into `0s1nt-checker`.

A patch file `0s1nt-checker-merge.patch` has been created in this repository.

To merge the changes into `0s1nt-checker`, please follow these steps:

1.  Clone `0s1nt-checker` locally:
    ```bash
    git clone https://github.com/0m364/0s1nt-checker.git
    cd 0s1nt-checker
    ```
2.  Download `0s1nt-checker-merge.patch` from this repository.
3.  Apply the patch:
    ```bash
    git am /path/to/0s1nt-checker-merge.patch
    ```
4.  Push the changes:
    ```bash
    git push origin main
    ```

After merging, you can delete this repository.
