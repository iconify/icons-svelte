<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvi4p0sbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="lvi4p0sbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:wave-square" {...props}></Icon>
