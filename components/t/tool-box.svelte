<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p37056bvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p37056bvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:tool-box" {...props}></Icon>
