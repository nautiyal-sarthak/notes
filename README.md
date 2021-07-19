# notes

read json : 

val array =  new Gson().fromJson(f, classOf[Array[String]])
println(array.mkString(", "))
