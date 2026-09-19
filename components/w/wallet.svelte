<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8vkeubrv.css';
import '../../css/k/k18o02rhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q8vkeubrv"/><path class="k18o02rhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:wallet" {...props}></Icon>
