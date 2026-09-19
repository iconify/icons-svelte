<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_rcn9b4y.css';
import '../../css/f/f-7sbkbnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v_rcn9b4y"/><path class="f-7sbkbnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:satisfy-usage" {...props}></Icon>
