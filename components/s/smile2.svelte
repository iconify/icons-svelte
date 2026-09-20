<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpps04-hx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dpps04-hx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:smile2" {...props}></Icon>
