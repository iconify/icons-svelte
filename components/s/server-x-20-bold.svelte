<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2oo1d9_b.css';
import '../../css/e/ebjb9jbbr.css';
import '../../css/x/xak2o0bmu.css';
import '../../css/k/k6sa60boh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w2oo1d9_b"/><path class="ebjb9jbbr"/><path class="xak2o0bmu"/><path class="k6sa60boh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:server-x-20-bold" {...props}></Icon>
