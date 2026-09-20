<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gip2fsogj.css';
import '../../css/h/hhrevwgtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gip2fsogj"/><path class="hhrevwgtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tubetimeout-light" {...props}></Icon>
