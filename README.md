# created db 
    * createdb todos-dev
# set env 
    *   NODE_ENV=development
# seqlize commands 
    ```
        sequelize model:create --name Todo --attributes title:string

         sequelize model:create --name TodoItem --attributes content:string,complete:boolean
    ``