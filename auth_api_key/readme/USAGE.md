To apply this authentication system to your http request you must set
'bearer' as value for the 'auth' parameter of your route definition
into your controller.

``` python
class MyController(Controller):

    @route('/my_service', auth='bearer', ...)
    def my_service(self, *args, **kwargs):
        pass
```
