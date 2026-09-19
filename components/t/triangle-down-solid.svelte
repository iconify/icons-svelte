<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwc4woboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vwc4woboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:triangle-down-solid" {...props}></Icon>
