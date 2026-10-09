<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmjqnac7l.css';
import '../../css/w/w4wlpvbuu.css';
import '../../css/i/i31k85bxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fmjqnac7l"/><path class="w4wlpvbuu"/><path class="i31k85bxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:socket-20" {...props}></Icon>
