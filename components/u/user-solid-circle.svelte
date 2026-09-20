<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgtnslbsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vgtnslbsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:user-solid-circle" {...props}></Icon>
