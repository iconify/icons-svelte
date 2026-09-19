<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-s4jxb4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="i-s4jxb4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:save" {...props}></Icon>
