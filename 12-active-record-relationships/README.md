# ActiveRecord Relationships

## SWBATs
- [ ] Use ActiveRecord to implement a many-to-many relationship
- [ ] Build a join model 
- [ ] Execute ActiveRecord commands to get data through the join model


## Notes

- Migrations 
  - Ruby files that will be used to build your tables
  - Create a migration: `rake db:create_migration NAME=create_dragons`
  - Migrate: `rake db:migrate`

    
  ### 1-to-many ERD
  ![1-to-many ERD](./pics/IMG_1941.jpg)

  ### many-to-many ERD
  ![may-to-many ERD](./pics/IMG_1942.jpg)