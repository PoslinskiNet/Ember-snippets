# ember-2-14-snippets README

# Method List
|Prefix|Method|
|-------:|-------|
|`impe→`|`import Ember from 'ember'`|
|`impj→`|`import ModuleName from 'module'`|
|`component→`|`Build component template`|
|`fcomponent→`|`Build component template with computed, inject`|
|`alrt→`|`alert()`|
|`inj→`|`const { inject } = Ember`|
|`servi→`|`ServiceName: inject.service('name')`|
|`actions→`|`actions block`|
# Component Lifecycle
|Prefix|Method|
|-------:|-------|
|`init→`|`Component lifecycle - Init`|
|`die→`|`Component lifecycle - didInsertElement`|
|`dr→`|`Component lifecycle - didRender`|
|`dra→`|`Component lifecycle - didReceiveAttrs`|

# Computed
|Prefix|Method|
|-------:|-------|
|`compdest→`|`const { computed } = Ember`|
|`comp→`|`computeName: computed('dependentKey', function() {})`|
|`alias→`|`computeName: computed.alias('dependentKey')`|
|`and→`|`computeName: computed.and('key', 'anotherKey')`|
|`bool→`|`computeName: computed.bool('dependentKey')`|
|`collect→`|`computeName: computed.collect('key', 'anotherKey')`|
|`empty→`|`computeName: computed.empty('dependentKey')`|
|`equal→`|`computeName: computed.equal('dependentKey', value)`|
|`filter→`|`computeName: computed.filter('key', function(item, index, array) {})`|
|`filterBy→`|`computeName: computed.filteBy('array', 'key', value)`|
|`gt→`|`computeName: computed.gt('key', value)`|
|`gte→`|`computeName: computed.gte('key', value)`|
|`lt→`|`computeName: computed.lt('key', value)`|
|`lte→`|`computeName: computed.lte('key', value)`|
|`intersect→`|`computeName: computed.intersect('arrayA', 'arrayB')`|
|`map→`|`computeName: computed.map('array', function(item, index) {})`|
|`mapBy→`|`computeName: computed.mapBy('array', 'key')`|
|`match→`|`computeName: computed.match('dependentKey', reqexp)`|
|`max→`|`computeName: computed.max('dependentKey')`|
|`min→`|`computeName: computed.min('dependentKey')`|
|`none→`|`computeName: computed.none('dependentKey')`|
|`not→`|`computeName: computed.not('dependentKey')`|
|`notEmpty→`|`computeName: computed.notEmpty('dependentKey')`|
|`oneWay→`|`computeName: computed.oneWay('dependentKey')`|
|`or→`|`computeName: computed.or('dependentKey')`|
|`sum→`|`computeName: computed.sum('dependentKey')`|
|`reads→`|`computeName: computed.reads('dependentKey')`|
|`setDiff→`|`computeName: computed.setDiff('arrayA', 'arrayB')`|
|`union→`|`computeName: computed.union('arrayA', 'arrayB')`|
|`uniq→`|`computeName: computed.uniq('array')`|
|`uniqBy→`|`computeName: computed.uniqBy('dependentKey', 'propertyKey')`|


# Store
|Prefix|Method|
|-------:|-------|
|`injstore`|`store: inject.service(),`|
|`gstore`|`this.get('store')`|
|`fall`|`this.get('store').findAll('model')`|
|`pall`|`this.get('store').peekAll('model')`|
|`query`|`this.get('store').query('model', {})`|
|`find`|`this.get('store').find('model', id)`|










