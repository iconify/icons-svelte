<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/ha3f25bxe.css';
import '../../css/i/iksb9rpzr.css';
import '../../css/n/n13mhtbfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ha3f25bxe"/><path class="iksb9rpzr"/><path clip-rule="evenodd" class="n13mhtbfz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:user-plus-outline" {...props}></Icon>
