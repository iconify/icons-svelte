<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hb-f-i0ey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hb-f-i0ey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:stairs-fill" {...props}></Icon>
