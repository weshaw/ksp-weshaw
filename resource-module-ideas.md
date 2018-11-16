#Resource Converstion

## Moules

### Wast Storage
* Source Part: MK2 Tank
* Type: Storage
	* WasteWater, Waste

### Molten Salt Heat Storage
* Source Part: MK2 Tank
* Type: Storage
	* WasteHeat

### Septic/Recycle Plant
* Source Part: MK2 Tank
* Type: ModuleResourceConverter
	* Proccess Waste
		* Intake - Waste, Electricity
		* Output - Fertilizer, WasteHeat

### Greenhouse - (coupila)
* Source Part: Coupila
* Type: ModuleResourceConverter
	* Grow Plants
		* intake - Water, CarbonDioxide, Fertilizer,  electric
		* output - Waste Water, Waste, Oxygen, Organics
* Type: Storage
	* Wast
	* Water
	* Wastewater
	* Organics
	* CO2
	* Fertilizer

### Water Filtration System
* Source Part: MK2 Tank
* Type: ModuleResourceConverter
	* Filter Waste Water
		* intake - Waste Water, Electricity
		* output - Water

### Electrolysis Plant
* Source Part: MK2 Tank
* Type: ModuleResourceConverter
	* Electrolysis
		* intake - Water, Electricity
		* output - Hydrogen, Oxygen

### CO2 Scrubber - (?)
* Source Part: ?
* Type: ModuleResourceConverter
	* Scrub CO2
		* intake - CO2, electricity
		* output -  Oxygen, Carbon

### Solar Wind Collector
* Source Part: Solar Panel / Radiator
* Type: ModuleResourceConverter
	* Collect Wind
		* intake - Solar Wind
		* output - Hydrogen, Helium, Chemicals

### Chemical Plant - (?)
* Source Part: ?
* Type: ModuleResourceConverter
	* Deconstruct Chemicals
		* intake - Chemicals, Electricity
		* output - Carbon, Oxygen, Waste, Metals, Minerals
	* Produce CarbonDioxide
		* intake - Carbon, Oxygen, Electricity
		* output - CarbonDioxide

### Kitchen
Turn organics into rations

### Factory
turn metals into rocket parts

### EM Drive
propultion from energy :(
