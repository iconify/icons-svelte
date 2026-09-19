<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eed8x_bnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eed8x_bnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:unity" {...props}></Icon>
