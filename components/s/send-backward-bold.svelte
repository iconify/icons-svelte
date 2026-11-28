<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9revib3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="l9revib3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:send-backward-bold" {...props}></Icon>
