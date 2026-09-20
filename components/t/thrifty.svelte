<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4-vtpbnb.css';
import '../../css/x/xtnibnbva.css';
import '../../css/h/hn9ztn5zb.css';
import '../../css/a/aszoa8b8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u4-vtpbnb"/><path class="xtnibnbva"/><path class="hn9ztn5zb"/><path class="aszoa8b8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:thrifty" {...props}></Icon>
