<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xr_5rabpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xr_5rabpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:shield-2" {...props}></Icon>
