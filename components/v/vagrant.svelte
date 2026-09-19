<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0vyxlb-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":508,"height":512};
const content = `<path class="y0vyxlb-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:vagrant" {...props}></Icon>
