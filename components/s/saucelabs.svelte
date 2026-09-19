<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xr1w4fuup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xr1w4fuup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:saucelabs" {...props}></Icon>
