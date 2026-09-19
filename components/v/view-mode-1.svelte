<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/synbksvac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="synbksvac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:view-mode-1" {...props}></Icon>
