<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0asflb7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="a0asflb7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:view-carousel" {...props}></Icon>
