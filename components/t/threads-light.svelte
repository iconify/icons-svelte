<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5ron5w_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p5ron5w_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:threads-light" {...props}></Icon>
