<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3g_w1qsa.css';
import '../../css/k/klsk1sb8v.css';
import '../../css/h/hvfwvmb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="t3g_w1qsa"><rect class="klsk1sb8v"/><rect class="hvfwvmb8r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:zero-key" {...props}></Icon>
