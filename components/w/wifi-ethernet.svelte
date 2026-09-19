<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfz1t-ffx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="bfz1t-ffx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:wifi-ethernet" {...props}></Icon>
