<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7fgkjtnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h7fgkjtnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:volume-vibrate-line" {...props}></Icon>
