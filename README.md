# FactoryGirl Snippets for Sublime Text 2/3

## Included Snippets

`fac` -> `factory :name, :class, :parent, :aliases do ... end`

`seq` -> `sequence(:attribute, initial value) { |n| "#{n}" }`

`fgaf` -> `attributes_for(:model, attributes)`

`fgc` -> `create(:model, attributes)`

`fgcl` -> `create_list(:model, 3, attributes)`

`fgb` -> `build(:model, attributes)`

`fgbs` -> `build_stubbed(:model, attributes)`

`fgbl` -> `build_list(:model, 3, attributes)`

`after` -> `after(:create|:build|:stub) { |resource| ... }`

`before` -> `before(:create) { |resource| ... }`
