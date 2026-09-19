<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow9_qhf_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ow9_qhf_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:weight-hanging" {...props}></Icon>
