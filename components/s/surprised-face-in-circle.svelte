<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td6u0lbzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="td6u0lbzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:surprised-face-in-circle" {...props}></Icon>
