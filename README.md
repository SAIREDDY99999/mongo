# mongo
db.multiples.aggregate([
  {
    $addFields: {
      sum: { $add: ["$multiple1", "$multiple2"] }
    }
  }
])
