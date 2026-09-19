<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/g/gj7mgbb6o.css';
import '../../css/e/efeuc0qbu.css';
import '../../css/b/bzs_6oz_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="gj7mgbb6o"/><path class="efeuc0qbu"/><path class="bzs_6oz_t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:shield-add" {...props}></Icon>
