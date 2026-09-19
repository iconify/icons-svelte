<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuq3_flxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uuq3_flxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:upload" {...props}></Icon>
