<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iy7uj0bjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iy7uj0bjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-bar-chart-horizontal-end-fill" {...props}></Icon>
