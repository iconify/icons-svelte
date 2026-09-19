<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bngkp7yhv.css';
import '../../css/o/o9rdwyb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bngkp7yhv"/><path class="o9rdwyb_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:windy-snow" {...props}></Icon>
