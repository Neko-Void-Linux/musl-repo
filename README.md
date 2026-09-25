# MUSL REPO OF TEMPLATES FOR NEKO VOID
A collection of NEKO VOID templates for xbps-src
### x86_64 REPO
example

``` 
sudo xbps-install  -S --repository=https://github.com/Neko-Void-Linux/musl-repo/releases/download/packages Neko-Wizard
```
### Run on void-packages for compile (goverlay-bin and mangowc-latest)
```
echo "#nothing" >> common/build-style/none.sh
echo "libscenefx-0.5.so scenefx-latest-0.5_1" >> common/shlibs
echo "libQt6Pas.so.6 libqt6pas-bin-6.2.10_1" >> common/shlibs
```  
### FOR UPDATE OR ADD PACKAGES IN REPO RUN ACTION WORKFLOW  (USE GITHUB MIGRATION PLEASE) 
https://github.com/Neko-Void-Linux/repo-neko/actions/workflows/musl-repo.yml
