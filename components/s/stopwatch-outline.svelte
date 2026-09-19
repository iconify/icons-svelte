<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd6hptbdy.css';
import '../../css/y/ydx4aab2y.css';
import '../../css/p/pnj3j0bnr.css';
import '../../css/e/ejbf23bon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hd6hptbdy"/><path class="ydx4aab2y"/><circle class="pnj3j0bnr"/><path class="ejbf23bon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:stopwatch-outline" {...props}></Icon>
