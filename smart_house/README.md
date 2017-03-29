# SmartHouseAPI

<br>redesign of exposed URI's: 

/House <br>
/House/{id}<br>
/House/{id}/User<br>
/House/{id}/User/{id}<br>
/House/{id}/Room<br>
/House/{id}/Room/{id}<br>
/House/{id}/Room/{id}/Device<br>
/House/{id}/Room/{id}/Device/{id}<br>
/House/{id}/Room/{id}/Environment<br>

<br>Abstracted baseclasses from the object-model
<br>ConcurrentHashMap typemigrated to Collection because of marchalling problems. 
