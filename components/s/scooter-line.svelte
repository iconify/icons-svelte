<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4_3rfb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4_3rfb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:scooter-line" {...props}></Icon>
