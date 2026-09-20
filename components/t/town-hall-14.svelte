<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6j897b2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="s6j897b2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:town-hall-14" {...props}></Icon>
