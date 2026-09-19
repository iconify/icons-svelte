<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvvs-6bny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lvvs-6bny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:shapes" {...props}></Icon>
