<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue-hx7a2u.css';
import '../../css/r/r97zvfb6s.css';
import '../../css/c/c18_ysapx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ue-hx7a2u"/><path class="r97zvfb6s"/><path class="c18_ysapx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:taiga-dark" {...props}></Icon>
