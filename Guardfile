# A sample Guardfile
guard 'phpunit2', cli: '--colors', tests_path: 'tests', all_on_start: true, keep_failed: true, all_after_pass: true, command: './vendor/bin/phpunit', realtime: true do
  watch (%r{^tests/.+Test.php$})
  watch (%r{^src/(.+).php$}) { |m| "tests/#{m[1]}Test.php" }
end
