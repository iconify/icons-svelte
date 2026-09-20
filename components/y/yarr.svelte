<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6u949tnp.css';
import '../../css/u/uxjv9458g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w6u949tnp"/><path class="uxjv9458g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yarr" {...props}></Icon>
