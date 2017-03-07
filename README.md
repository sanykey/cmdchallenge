# cmdchallenge
The solution of exercises from the [cmdchallenge.com](https://cmdchallenge.com)

* hello_world: `echo 'hello world'`
* current_working_directory: `pwd`
* list_files: `ls`
* list_files_adv: `ls -aF`
* nested_dirs: `cat "./.../  /. .the flag.txt"`
* print_file_contents: `cat access.log`
* last_lines: `tail -n 5 access.log`
* find_string_in_a_file: `grep "GET" access.log`
* find_tabs_in_a_file: `grep -P "\t" file-with-tabs.txt | wc -l`
* search_for_files_containing_string: `grep -Rl "500" . | sed "s/.*\///"`
* search_for_files_by_extension: `ls access.log*`
* search_for_string_in_files_recursive: `grep -Rh "500" ./**/access.log*`
* extract_ip_addresses: `grep -REo "[0-9]+\.[0-9]+\.[0-9]+\.[0-9]+" ./**/access.log*`
* delete_files: `rm -r * .*`
* count_files: `ls | wc -l`
* simple_sort: `sort access.log`
* count_string_in_line: `grep "GET" access.log | wc -l`
* split_on_a_char: `sed "s/;/\n/g" split-me.txt`
* print_number_sequence: `for (( i=1; i<=100; i++ )); do echo -n "$i "; done`
* remove_files_with_a_dash: `rm ./-*`
* remove_files_with_extension: `rm ./**/*.doc`
* print_nth_line: `head -n 25 faces.txt | tail -n 1`
