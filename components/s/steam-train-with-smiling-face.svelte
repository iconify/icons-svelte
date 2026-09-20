<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyl5n_bpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wyl5n_bpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:steam-train-with-smiling-face" {...props}></Icon>
