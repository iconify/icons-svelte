<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d99lr5agc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d99lr5agc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:za-sort-ascending-letters-line" {...props}></Icon>
