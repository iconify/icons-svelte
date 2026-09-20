<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swi8b0bzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="swi8b0bzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:triangle-up" {...props}></Icon>
