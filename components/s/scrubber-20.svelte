<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iypo-rqra.css';
import '../../css/y/y2-zu1b4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="iypo-rqra"/><path class="y2-zu1b4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:scrubber-20" {...props}></Icon>
