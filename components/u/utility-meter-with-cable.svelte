<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl6vbkbqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yl6vbkbqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:utility-meter-with-cable" {...props}></Icon>
