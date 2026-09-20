<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fft8hptxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fft8hptxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vikunja-light" {...props}></Icon>
