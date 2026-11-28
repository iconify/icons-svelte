<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mal05lbhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="mal05lbhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:send-backward-thin" {...props}></Icon>
