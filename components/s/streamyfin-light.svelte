<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djvfn5bwe.css';
import '../../css/i/ih2euw71h.css';
import '../../css/v/vvhqz38eo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="djvfn5bwe"/><path class="ih2euw71h"/><path class="vvhqz38eo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:streamyfin-light" {...props}></Icon>
