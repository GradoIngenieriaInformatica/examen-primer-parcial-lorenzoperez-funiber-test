db.cursos.aggregate([
{$group:{_id:"$nivel",creditosTotales:{$sum:"$creditos"}}}
])

