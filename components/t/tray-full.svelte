<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fb14r95-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fb14r95-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tray-full" {...props}></Icon>
