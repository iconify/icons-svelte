<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn4-zq4ny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rn4-zq4ny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:shutter-10" {...props}></Icon>
