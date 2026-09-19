<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8d0ypv4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l8d0ypv4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:yaml" {...props}></Icon>
