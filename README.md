# vuejs iran cities component

### Html:

```
<iran-cities-component :province-model.sync="province" :city-model.sync="city" default-province="تهران" default-city="تهران"></iran-cities-component>
```

### Vuejs
```
new Vue({
	data: {
		province: '',
		city:	  ''
	},
	components: {
		iranCitiesComponent: IranCitiesComponent
	}
});
```
