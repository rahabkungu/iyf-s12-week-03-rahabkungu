# Day 2 : find command mastery

1. Find all css files in project folder: `find . -type f -name "*.css"`
2. Find all files modified in the last 7 days : ` find . -type f -mtime  -7"`
3. search for "flex" in all css files: `gerp -rnw . -e "flex" --include="*css"`
4. Count occurences of "div" in HTML files: `grep -o -i "div" $(find . -type f -name "*.html") | wc -l`