<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp9j1o_0y.css';
import '../../css/u/uf_f1g_xb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tp9j1o_0y"/><path class="uf_f1g_xb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:toilet" {...props}></Icon>
