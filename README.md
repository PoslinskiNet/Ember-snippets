# ember-snippets README

# Method List
|Prefix|Method|
|-------:|-------|
|`import Ember→`|`import Ember from 'ember'`|
|`import module→`|`import ModuleName from 'module'`|
|`ember component→`|`Build component template`|
|`full component→`|`Build component template with computed, inject`|
|`alert→`|`alert()`|
|`inject→`|`const { inject } = Ember`|
|`service inject→`|`ServiceName: inject.service('name')`|
|`actions→`|`actions block`|
# Component Lifecycle
|Prefix|Method|
|-------:|-------|
|`init→`|`Component lifecycle - Init`|
|`didInsertElement→`|`Component lifecycle - didInsertElement`|
|`didRender→`|`Component lifecycle - didRender`|
|`didReceiveAttrs→`|`Component lifecycle - didReceiveAttrs`|
|`didUpdateAttrs→`|`Component lifecycle - didUpdateAttrs`|

# Computed imports
|Prefix|Method|
|-------:|-------|
|`alias import→`|`import { alias } from '@ember/object/computed';`|
|`and import→`|`import { and } from '@ember/object/computed';`|
|`bool import→`|`import { bool } from '@ember/object/computed';`|
|`collect import→`|`import { collect } from '@ember/object/computed';`|
|`empty import→`|`import { empty } from '@ember/object/computed';`|
|`equal import→`|`import { equal } from '@ember/object/computed';`|
|`filter import→`|`import { filter } from '@ember/object/computed';`|
|`filterBy import→`|`import { filterBy } from '@ember/object/computed';`|
|`gt import→`|`import { gt } from '@ember/object/computed';`|
|`gte import→`|`import { gte } from '@ember/object/computed';`|
|`intersect import→`|`import { intersect } from '@ember/object/computed';`|
|`map import→`|`import { map } from '@ember/object/computed';`|
|`mapBy import→`|`import { mapBy } from '@ember/object/computed';`|
|`match import→`|`import { match } from '@ember/object/computed';`|
|`max import→`|`import { max } from '@ember/object/computed';`|
|`min import→`|`import { min } from '@ember/object/computed';`|
|`none import→`|`import { none } from '@ember/object/computed';`|
|`notEmpty import→`|`import { notEmpty } from '@ember/object/computed';`|
|`oneWay import→`|`import { oneWay } from '@ember/object/computed';`|
|`or import→`|`import { or } from '@ember/object/computed';`|
|`readOnly import→`|`import { readOnly } from '@ember/object/computed';`|
|`reads import→`|`import { reads } from '@ember/object/computed';`|
|`setDiff import→`|`import { setDiff } from '@ember/object/computed';`|
|`sort import→`|`import { sort } from '@ember/object/computed';`|
|`sum import→`|`import { sum } from '@ember/object/computed';`|
|`union import→`|`import { union } from '@ember/object/computed';`|
|`uniq import→`|`import { uniq } from '@ember/object/computed';`|
|`uniqBy import→`|`import { uniqBy } from '@ember/object/computed';`|


# Computed
|Prefix|Method|
|-------:|-------|
|`computed→`|`computeName: computed('dependentKey', function() {})`|
|`alias→`|`computeName: alias('dependentKey')`|
|`and→`|`computeName: and('key', 'anotherKey')`|
|`bool→`|`computeName: bool('dependentKey')`|
|`collect→`|`computeName: collect('key', 'anotherKey')`|
|`empty→`|`computeName: empty('dependentKey')`|
|`equal→`|`computeName: equal('dependentKey', value)`|
|`filter→`|`computeName: filter('key', function(item, index, array) {})`|
|`filterBy→`|`computeName: filteBy('array', 'key', value)`|
|`gt→`|`computeName: gt('key', value)`|
|`gte→`|`computeName: gte('key', value)`|
|`lt→`|`computeName: lt('key', value)`|
|`lte→`|`computeName: lte('key', value)`|
|`intersect→`|`computeName: intersect('arrayA', 'arrayB')`|
|`map→`|`computeName: map('array', function(item, index) {})`|
|`mapBy→`|`computeName: mapBy('array', 'key')`|
|`match→`|`computeName: match('dependentKey', reqexp)`|
|`max→`|`computeName: max('dependentKey')`|
|`min→`|`computeName: min('dependentKey')`|
|`none→`|`computeName: none('dependentKey')`|
|`not→`|`computeName: not('dependentKey')`|
|`notEmpty→`|`computeName: notEmpty('dependentKey')`|
|`oneWay→`|`computeName: oneWay('dependentKey')`|
|`or→`|`computeName: or('dependentKey')`|
|`sum→`|`computeName: sum('dependentKey')`|
|`reads→`|`computeName: reads('dependentKey')`|
|`setDiff→`|`computeName: setDiff('arrayA', 'arrayB')`|
|`union→`|`computeName: union('arrayA', 'arrayB')`|
|`uniq→`|`computeName: uniq('array')`|
|`uniqBy→`|`computeName: uniqBy('dependentKey', 'propertyKey')`|


# Store
|Prefix|Method|
|-------:|-------|
|`store inject`|`store: inject.service(),`|
|`get store`|`this.get('store')`|
|`findAll`|`this.get('store').findAll('model')`|
|`peekAll`|`this.get('store').peekAll('model')`|
|`query`|`this.get('store').query('model', {})`|
|`find`|`this.get('store').find('model', id)`|










