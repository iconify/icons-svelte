<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgut2acps.css';
import '../../css/u/us_t0abnz.css';
import '../../css/q/q3zt_bcwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cgut2acps"/><path class="us_t0abnz"/><path class="q3zt_bcwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:strawberry" {...props}></Icon>
