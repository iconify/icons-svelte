<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8abvhbux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w8abvhbux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:sublime" {...props}></Icon>
