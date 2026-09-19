<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r3nuceysm.css';
import '../../css/n/na_e5mbnk.css';
import '../../css/p/poz5v4vlw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="r3nuceysm"/><path class="na_e5mbnk"/><path clip-rule="evenodd" class="poz5v4vlw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:vomiting-outline" {...props}></Icon>
