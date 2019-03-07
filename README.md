# 17zuoye Olympus Snippets

# usage

1. osm: init a SceneMediator

``` ts
import { EgretMediatorClass } from '17zy_olympus-r-egret/egret/injector/Injector';
import SceneMediator from '17zy_olympus-r/engine/scene/SceneMediator';

@EgretMediatorClass('${filename}', 'skins.${filename}Skin')
export default class ${filename} extends SceneMediator {
    
}
```

2. om: init a Mediator

``` ts
import { EgretMediatorClass } from '17zy_olympus-r-egret/egret/injector/Injector';
import Mediator from '17zy_olympus-r/engine/mediator/Mediator';

@EgretMediatorClass('${filename}', 'skins.${filename}Skin')
export default class ${filename} extends Mediator {
    
}
```

3. omd: init a Model

``` ts
import { ModelClass } from '17zy_olympus-r/engine/injector/Injector';

@ModelClass
export default class ${filenam} {
    
}
```

4. olsa: init a listAssets

``` ts
public listAssets(): string[] {
    return [];
}
```

5. olsi: init a listInitRequests

``` ts
public listInitRequests(): RequestData[] {
    return [];
}
```