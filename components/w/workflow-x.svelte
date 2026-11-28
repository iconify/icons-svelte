<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7_y0l8bv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m7_y0l8bv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:workflow-x" {...props}></Icon>
