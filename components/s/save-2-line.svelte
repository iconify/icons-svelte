<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vn3ahzsej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vn3ahzsej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:save-2-line" {...props}></Icon>
