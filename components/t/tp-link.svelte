<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzam9lb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hzam9lb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tp-link" {...props}></Icon>
