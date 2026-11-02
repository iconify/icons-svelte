<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3r9fnbzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l3r9fnbzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:volume-mute-line" {...props}></Icon>
