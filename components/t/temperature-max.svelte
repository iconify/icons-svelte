<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc9-iebck.css';
import '../../css/w/w2x3wnbjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fc9-iebck"/><path class="w2x3wnbjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:temperature-max" {...props}></Icon>
