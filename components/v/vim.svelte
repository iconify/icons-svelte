<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0akgfb4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e0akgfb4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:vim" {...props}></Icon>
