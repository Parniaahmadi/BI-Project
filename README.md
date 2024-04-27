In the picture below, I've created a model that shows the relationships between the tables.

![Screenshot 2024-04-27 112200](https://github.com/Parniaahmadi/BI-Project/assets/129201205/d47d9cbe-fbbe-4d34-9656-744008137b68)


Model Layouts: In next image, I've create custom views to show specific portions of models.

First picture, Shows the Sales model view

![Screenshot 2024-04-27 112230](https://github.com/Parniaahmadi/BI-Project/assets/129201205/1ae251ef-faba-43f1-8722-43df342be7f1)

On the Second picture, you will see Returns model view.

![Screenshot 2024-04-27 112244](https://github.com/Parniaahmadi/BI-Project/assets/129201205/f91f7d39-c11a-488a-95ef-20946f381b33)


Tips for bulding models:
- Make sure to start with building a normalized model.Ensure that each table plays a clear and distinct role by leveraging relationships.
- In the model, organize dimension tables above data tables.This serves as a visual cue that filters always flow "downstream".
- Unless it is absolutely necessary, avoid using complex relationships.Whenever possible, use 1-to-many table relationships and one-way filters.
- To prevent an invalid filter context, hide fields from the report view.This compels report users to filter using primary keys from dimension tables.
