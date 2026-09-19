<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhyaxmbtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1408,"height":1664};
const content = `<path class="rhyaxmbtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:xing" {...props}></Icon>
