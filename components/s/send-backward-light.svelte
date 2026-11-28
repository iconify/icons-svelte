<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_v203bkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="z_v203bkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:send-backward-light" {...props}></Icon>
