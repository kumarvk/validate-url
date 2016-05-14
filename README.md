# validate-url

## Usage

### With ActiveRecord

```ruby    
class Post < ActiveRecord::Base
  validates :article_page, :url => true
end
