# PYDANTIC

Pydantic is a framework in pythan that allows the creation of custom data types, kind of like classes but only properties, e.g:
class:
Class Dog()
self.name =
self.color =
self.address =

Pydantic:
Class: Dog(BaseModel):
name: str
color: str
address: str

The difference between pydantic and classes is that python will let you by default do:
Dog(name = 'heathman', color = 2, address = '26 ya mums house' ) at runtime, pydantic will error out
