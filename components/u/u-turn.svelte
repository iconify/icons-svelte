<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdala_bsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gdala_bsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:u-turn" {...props}></Icon>
