<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc9mvj8qh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pc9mvj8qh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:upload-fail" {...props}></Icon>
