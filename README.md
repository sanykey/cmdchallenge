# cmdchallenge
The solution of exercises from the [cmdchallenge.com](https://cmdchallenge.com)

* hello_world: `echo 'hello world'`
* current_working_directory: `pwd`
* list_files: `ls`
* nested_dirs: `cat "./.../  /. .the flag.txt"`
* print_file_contents: `cat access.log`
* last_lines: `tail -n 5 access.log`
* find_string_in_a_file: `grep "GET" access.log`
* find_tabs_in_a_file: `grep -P "\t" file-with-tabs.txt | wc -l`
* search_for_files_by_extension: `ls access.log*`
* search_for_string_in_files_recursive: `grep -Rh "500" ./**/access.log*`
* count_files: `ls | wc -l`
* simple_sort: `sort access.log`
* count_string_in_line: `grep "GET" access.log | wc -l`
* remove_files_with_a_dash: `rm ./-*`
* remove_files_with_extension: `rm ./**/*.doc`
