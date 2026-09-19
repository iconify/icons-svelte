<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d44248blx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d44248blx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:stencil" {...props}></Icon>
