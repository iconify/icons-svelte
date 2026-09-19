<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/db3bihb_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="db3bihb_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:zap" {...props}></Icon>
