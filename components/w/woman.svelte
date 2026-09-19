<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/j/j64jqwfra.css';
import '../../css/z/zgv3likpx.css';
import '../../css/b/bxtnlct1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="j64jqwfra"/><path class="zgv3likpx"/><path class="bxtnlct1k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:woman" {...props}></Icon>
