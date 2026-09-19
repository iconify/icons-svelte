<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vr76icdak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vr76icdak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:scheme" {...props}></Icon>
