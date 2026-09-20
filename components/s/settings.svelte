<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d94zbcb-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d94zbcb-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:settings" {...props}></Icon>
