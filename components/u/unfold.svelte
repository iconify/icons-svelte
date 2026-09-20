<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fx_r_-bpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fx_r_-bpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:unfold" {...props}></Icon>
