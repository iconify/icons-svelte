<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2y0ofppi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z2y0ofppi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:school-line" {...props}></Icon>
