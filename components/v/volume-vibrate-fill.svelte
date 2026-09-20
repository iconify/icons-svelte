<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi2oy9bdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vi2oy9bdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:volume-vibrate-fill" {...props}></Icon>
