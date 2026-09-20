<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l4k2nwwaz.css';
import '../../css/o/ouzepdbve.css';
import '../../css/h/hbxrwe5kr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><circle class="l4k2nwwaz"/><ellipse class="ouzepdbve"/><path class="hbxrwe5kr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:users-filled" {...props}></Icon>
