# Making this site static

Site: ar-cities.survey.okfn.org

## Script to make the site static

We run

```
wget \
     -P $domain \
     --recursive \
     --no-clobber \
     --page-requisites \
     --html-extension \
     --convert-links \
     --restrict-file-names=windows \
     --domains ar-cities.survey.okfn.org \
     --no-parent https://ar-cities.survey.okfn.org
```
