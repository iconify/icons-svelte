<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eio6mwq-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="eio6mwq-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:sad-face-with-tear-in-circle-outline" {...props}></Icon>
