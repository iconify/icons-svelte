<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhxs1y3oh.css';
import '../../css/h/hvw76hbuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uhxs1y3oh"/><path class="hvw76hbuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:script" {...props}></Icon>
