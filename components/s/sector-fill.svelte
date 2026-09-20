<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muf2sjrtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="muf2sjrtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sector-fill" {...props}></Icon>
