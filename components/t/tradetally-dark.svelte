<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgttro11x.css';
import '../../css/d/dl8utqb_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qgttro11x"/><path class="dl8utqb_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tradetally-dark" {...props}></Icon>
