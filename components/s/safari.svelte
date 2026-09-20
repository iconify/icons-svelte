<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkz44uchn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kkz44uchn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:safari" {...props}></Icon>
