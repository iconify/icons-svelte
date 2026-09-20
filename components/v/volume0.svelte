<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj90b9bcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wj90b9bcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:volume0" {...props}></Icon>
