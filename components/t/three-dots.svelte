<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irmh0zbps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="irmh0zbps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:three-dots" {...props}></Icon>
