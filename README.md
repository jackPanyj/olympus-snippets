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

2. opm: init a PanelMediator

``` ts
import { EgretMediatorClass } from '17zy_olympus-r-egret/egret/injector/Injector';
import PanelMediator from '17zy_olympus-r/engine/panel/PanelMediator';

@EgretMediatorClass('${filename}', 'skins.${filename}Skin')
export default class ${filename} extends PanelMediator {
    
}
```

3. om: init a Mediator

``` ts
import { EgretMediatorClass } from '17zy_olympus-r-egret/egret/injector/Injector';
import Mediator from '17zy_olympus-r/engine/mediator/Mediator';

@EgretMediatorClass('${filename}', 'skins.${filename}Skin')
export default class ${filename} extends Mediator {
    
}
```

4. omd: init a Model

``` ts
import { ModelClass } from '17zy_olympus-r/engine/injector/Injector';

@ModelClass
export default class ${filenam} {
    
}
```

5. olsa: init a listAssets

``` ts
public listAssets(): string[] {
    return [];
}
```

6. olsi: init a listInitRequests

``` ts
public listInitRequests(): RequestData[] {
    return [];
}
```