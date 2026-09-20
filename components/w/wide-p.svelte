<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kboz2db7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kboz2db7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:wide-p" {...props}></Icon>
