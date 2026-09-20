<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3_0h0bee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h3_0h0bee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:terminal" {...props}></Icon>
