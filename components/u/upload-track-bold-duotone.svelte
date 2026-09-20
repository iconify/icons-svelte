<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hxr3okbyi.css';
import '../../css/l/l2tvh_zrw.css';
import '../../css/g/gm3qr28eb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="hxr3okbyi"/><path class="l2tvh_zrw"/><path class="gm3qr28eb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:upload-track-bold-duotone" {...props}></Icon>
