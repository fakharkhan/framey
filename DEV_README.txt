To release a new version of the framey gem:

1. make your code changes
2. change VERSION in lib/framey.rb
3. change VERSION in lib/framey/configuration.rb
4. change p.version in Rakefile
5. think about consolidating all these version strings to one place...
6. update README.md to reflect your changes
7. push to git
8. rake release VERSION=[YOUR NEW VERSION NUMBER]
9. rake publish_docs

RubyForge Login:
  username: qlabs
  password: [qlabs password]

RubyGems Login:
  username: qlabs
  password: [qlabs password]