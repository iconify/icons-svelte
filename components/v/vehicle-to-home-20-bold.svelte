<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sflgm1xrv.css';
import '../../css/a/awkb24b_h.css';
import '../../css/y/y6syetncv.css';
import '../../css/c/c3totsbmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sflgm1xrv"/><path class="awkb24b_h"/><path class="y6syetncv"/><path class="c3totsbmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:vehicle-to-home-20-bold" {...props}></Icon>
