<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftzkohw_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ftzkohw_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:super-collider" {...props}></Icon>
