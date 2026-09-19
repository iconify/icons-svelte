<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/l/l8xk6kbgp.css';
import '../../css/b/bd13yxb1u.css';
import '../../css/e/eyowyccos.css';
import '../../css/n/n74rnsbwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="l8xk6kbgp"/><path class="bd13yxb1u"/><path class="eyowyccos"/><path class="n74rnsbwl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:trumpet" {...props}></Icon>
