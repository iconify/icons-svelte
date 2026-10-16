<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwtlcbcgl.css';
import '../../css/c/cbw46ub7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":298.961,"height":300};
const content = `<path class="pwtlcbcgl"/><path class="cbw46ub7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tautulli" {...props}></Icon>
