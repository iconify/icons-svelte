<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xupi7pbch.css';
import '../../css/p/pdl1bhbxu.css';
import '../../css/l/l4cuvtbmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xupi7pbch"/><path clip-rule="evenodd" class="pdl1bhbxu"/><path class="l4cuvtbmt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:video-play-h-filled" {...props}></Icon>
