make graphql server

appolo server - create server

to check api use
Apollo Explorer - client like postman

//review(id:ID):Review   - this varible query- use to find data by id
 type in graphql - int,float,string,boolean,ID
 ! means - required


  // this three argument parent,args,context
  method in resolver
        review(_,args,){
              return db.reviews.find((el)=>el.id ===args.id)
        },
