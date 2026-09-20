<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tigutsb4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tigutsb4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:volume3" {...props}></Icon>
