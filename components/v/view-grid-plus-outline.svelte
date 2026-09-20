<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0btk2rbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e0btk2rbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:view-grid-plus-outline" {...props}></Icon>
