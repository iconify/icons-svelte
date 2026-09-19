<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uv7qrfb2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uv7qrfb2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:uikit" {...props}></Icon>
