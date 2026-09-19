<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4-2nzkwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s4-2nzkwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:tilemap" {...props}></Icon>
