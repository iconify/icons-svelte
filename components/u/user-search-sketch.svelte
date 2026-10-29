<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/yi6lqbb5x.css';
import '../../css/u/urp_3vpiq.css';
import '../../css/r/r-718ec7i.css';
import '../../css/z/zer89gupx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k yi6lqbb5x"/><path class="urp_3vpiq wm-k"/><path class="r-718ec7i wm-s"/><path class="wm-s zer89gupx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:user-search-sketch" {...props}></Icon>
