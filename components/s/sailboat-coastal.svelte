<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vat4d3csq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vat4d3csq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:sailboat-coastal" {...props}></Icon>
