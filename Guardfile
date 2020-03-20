group :reload do
  guard 'livereload' do
    watch /.*/
  end
end

group :build do
  guard 'jekyll-plus', serve: true do
    watch /.*/
    ignore /^_site/
  end
end
