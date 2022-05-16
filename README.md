# Sabbath School Lessons Archive and Website

A static website with search built with jekyll for github pages. Migrated from `csycms`.

## Usage
```bash
bundle clean --force
bundle install
jekyll serve
```

## todo
- [ ] New Phase
- [ ] Further Info
- [ ] Downloads page
- [ ] coverpage
- [X] uneditted lessons  whole
- [X] Add lessons which are still missing (***Resolved. Note and add later***)
- [ ] Remove redundant data from template
- [X] Change favicon.
- [X] Analytics
- [X] Site verification
- [X] fix copyright (footer)
- [X] Fix search (algolia) [Ref](https://mmistakes.github.io/minimal-mistakes/docs/configuration/)
- [ ] Fix search (try google) [Ref](https://cse.google.com/cse?cx=5b4b52d25ed2f2d48) [Ref1](https://cse.google.com/cse/create/getcode?cx=c5c90b4a01058b7cc)
- [ ] Sharing links
- [ ] Adiso codename
- [ ] fix colors
- [ ] Fix breadcrumbs
- [ ] SEO
- [ ] Start adding quotes
- [ ] Proof-reading and Editing
- [ ] scripts to make whole quartely from individual lessons and scripts to do the reverse
- [ ] Change all favicons
- [ ] navigation scripts
- [ ] Do the same for AH


[Ref 1](https://www.cross-validated.com/Personal-website-with-Minimal-Mistakes-Jekyll-Theme-HOWTO-Part-IV/)


### Missing Lessons
- ./02.1888-1890/02.1889/04.quarter4/00-chapter.md=>1889:::4=> ===13
- ./11.1971-1980/03.1973/04.quarter4/00-chapter.md=>1973:::4=> ===13
- ./12.1981-1990/03.1983/04.quarter4/00-chapter.md=>1983:::4=>SS19831001-04.txt ===13
- ./12.1981-1990/03.1983/02.quarter2/00-chapter.md=>1983:::2=>SS19830401-02.txt ===13
- ./12.1981-1990/03.1983/03.quarter3/00-chapter.md=>1983:::3=>SS19830701-03.txt ===13
- ./12.1981-1990/03.1983/01.quarter1/00-chapter.md=>1983:::1=>SS19830101-01.txt ===13
- ./12.1981-1990/06.1986/04.quarter4/00-chapter.md=>1986:::4=> ===13


## Search
- We desire to use algolia. But since some of the pages are still whole quartelies which have not been divided into individual lessons, they can not be added to algolia index (free plan requires <= 10kb)

- Lunr search_full_content has an index that is 82.6mb. Cannot work

***Resolved***: Use algolia and update as big files are broken down into smaller sizes