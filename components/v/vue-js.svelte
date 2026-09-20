<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvmyrwbcs.css';
import '../../css/p/pvt38-bcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dvmyrwbcs"/><path class="pvt38-bcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vue-js" {...props}></Icon>
