<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-rjfpb9o.css';
import '../../css/x/xyso4-t-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":24};
const content = `<path class="i-rjfpb9o"/><path class="xyso4-t-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:swarm" {...props}></Icon>
