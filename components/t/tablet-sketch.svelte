<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/mj7d6qdsu.css';
import '../../css/c/ctzae4bou.css';
import '../../css/b/b2gy1lb5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="mj7d6qdsu"/><path class="ctzae4bou wm-k"/><path class="b2gy1lb5d wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:tablet-sketch" {...props}></Icon>
