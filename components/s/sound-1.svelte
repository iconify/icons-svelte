<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obco2vbqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="obco2vbqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:sound-1" {...props}></Icon>
