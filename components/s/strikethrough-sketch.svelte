<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/za-y1svgo.css';
import '../../css/k/khw2__bqg.css';
import '../../css/l/lo43kub9k.css';
import '../../css/b/bstijcuuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k za-y1svgo"/><path class="khw2__bqg wm-a"/><path class="lo43kub9k wm-k"/><path class="bstijcuuk wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:strikethrough-sketch" {...props}></Icon>
