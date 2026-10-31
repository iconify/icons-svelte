<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp0oxifbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gp0oxifbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:send-gloss" {...props}></Icon>
