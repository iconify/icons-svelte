<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-xkcdijr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="i-xkcdijr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:rounded-triangle-down" {...props}></Icon>
