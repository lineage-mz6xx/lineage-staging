# LineageOS 11.0 for Motorola Xoom

```
1. mkdir -p kitkat

2. cd kitkat

3. Initialize your local repository using the Lineage trees, use a command
  repo init -u git://github.com/LineageOS/android.git -b cm-11.0

4. Clone my repo:
  git clone https://github.com/lineage-everest/lineage-staging.git -b primary .repo/local_manifests

5. Sync the repo:
  repo sync --no-tags --no-clone-bundle --force-sync -c

6. To build:
  . build/envsetup.sh
  lunch lineage_everest-userdebug
  brunch everest
```


Credits
-------
* [**Schischu**](https://github.com/Schischu)
* [**LineageOS**](https://github.com/LineageOS)
