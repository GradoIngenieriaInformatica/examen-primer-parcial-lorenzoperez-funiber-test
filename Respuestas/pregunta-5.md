db.cursos.aggregate([
{$group:{_id:"nivel",total:{$avg:"$creditos"}}}
])

