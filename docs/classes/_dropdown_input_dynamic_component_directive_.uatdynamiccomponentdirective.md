# Class UATDynamicComponentDirective
## Index### Constructors* [constructor](_dropdown_input_dynamic_component_directive_.uatdynamiccomponentdirective.html#constructor)### Properties* [currentCompRef](_dropdown_input_dynamic_component_directive_.uatdynamiccomponentdirective.html#currentcompref)* [dccClasses](_dropdown_input_dynamic_component_directive_.uatdynamiccomponentdirective.html#dccclasses)* [resolver](_dropdown_input_dynamic_component_directive_.uatdynamiccomponentdirective.html#resolver)* [vcRef](_dropdown_input_dynamic_component_directive_.uatdynamiccomponentdirective.html#vcref)### Accessors* [componentData](_dropdown_input_dynamic_component_directive_.uatdynamiccomponentdirective.html#componentdata)### Methods* [createComponent](_dropdown_input_dynamic_component_directive_.uatdynamiccomponentdirective.html#createcomponent)## Constructors### new UATDynamicComponentDirective(vcRef: ViewContainerRef, resolver: ComponentFactoryResolver): [UATDynamicComponentDirective](_dropdown_input_dynamic_component_directive_.uatdynamiccomponentdirective.html)  * Defined in [dropdown-input/dynamic-component.directive.ts:26](https://github.com/tme321/Unopinionated-Angular/blob/16a724b/src/lib/dropdown-input/dynamic-component.directive.ts#L26)#### Parameters| Name | Type | Description || ---- | ---- | ---- || vcRef | ViewContainerRef|  || resolver | ComponentFactoryResolver|  |#### Returns: [UATDynamicComponentDirective](_dropdown_input_dynamic_component_directive_.uatdynamiccomponentdirective.html)## Properties### currentCompRef: ComponentRef<any>
* Defined in [dropdown-input/dynamic-component.directive.ts:20](https://github.com/tme321/Unopinionated-Angular/blob/16a724b/src/lib/dropdown-input/dynamic-component.directive.ts#L20)### dccClasses: any
* Defined in [dropdown-input/dynamic-component.directive.ts:22](https://github.com/tme321/Unopinionated-Angular/blob/16a724b/src/lib/dropdown-input/dynamic-component.directive.ts#L22)### Protected resolver: ComponentFactoryResolver
* Defined in [dropdown-input/dynamic-component.directive.ts:29](https://github.com/tme321/Unopinionated-Angular/blob/16a724b/src/lib/dropdown-input/dynamic-component.directive.ts#L29)### Protected vcRef: ViewContainerRef
* Defined in [dropdown-input/dynamic-component.directive.ts:28](https://github.com/tme321/Unopinionated-Angular/blob/16a724b/src/lib/dropdown-input/dynamic-component.directive.ts#L28)## Accessors### componentData* set (compData: [DynamicComponentData](../interfaces/_common_dynamic_component_data_interface_.dynamiccomponentdata.html)): void  * Defined in [dropdown-input/dynamic-component.directive.ts:24](https://github.com/tme321/Unopinionated-Angular/blob/16a724b/src/lib/dropdown-input/dynamic-component.directive.ts#L24)#### Parameters| Name | Type | Description || ---- | ---- | ---- || compData | [DynamicComponentData](../interfaces/_common_dynamic_component_data_interface_.dynamiccomponentdata.html)|  |#### Returns: void## Methods### Protected createComponent(compData: [DynamicComponentData](../interfaces/_common_dynamic_component_data_interface_.dynamiccomponentdata.html)): void  * Defined in [dropdown-input/dynamic-component.directive.ts:32](https://github.com/tme321/Unopinionated-Angular/blob/16a724b/src/lib/dropdown-input/dynamic-component.directive.ts#L32)#### Parameters| Name | Type | Description || ---- | ---- | ---- || compData | [DynamicComponentData](../interfaces/_common_dynamic_component_data_interface_.dynamiccomponentdata.html)|  |#### Returns: void
Generated using [TypeDoc](http://typedoc.io)