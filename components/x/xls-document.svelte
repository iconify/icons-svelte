<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5yf_0fyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a5yf_0fyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:xls-document" {...props}></Icon>
