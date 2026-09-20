<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqd3_w6nh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="eqd3_w6nh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:tag-arrow-left" {...props}></Icon>
