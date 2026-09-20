<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bmx8l16wx.css';
import '../../css/q/qr8ob5b7o.css';
import '../../css/y/y19q9r0gu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="bmx8l16wx"/><path clip-rule="evenodd" class="qr8ob5b7o"/><path class="y19q9r0gu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:sale" {...props}></Icon>
