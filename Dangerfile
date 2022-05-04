warn("Big PR") if git.lines_of_code > 500
#
# #  junit_tests_dir
# junit_tests_dir = "**/test-results/**/*.xml"
# Dir[junit_tests_dir].each do |file_name|
#   junit.parse file_name
#   junit.report
# end
#
# # android_lint
# lint_dir = "**/reports/lint-results.xml"
# Dir[lint_dir].each do |file_name|
#   android_lint.skip_gradle_task = true
#   android_lint.filtering = true
#   android_lint.report_file = file_name
#   android_lint.lint
# end

# detekt
checkstyle_format.base_path = Dir.getwd
checkstyle_format.report 'app/build/reports/detekt/detekt.xml'
