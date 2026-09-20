<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/annqv0bpq.css';
import '../../css/m/myp8yacpy.css';
import '../../css/x/xmx92ictg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="annqv0bpq"/><path class="myp8yacpy"/><path clip-rule="evenodd" class="xmx92ictg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sticker-smile-circle-outline" {...props}></Icon>
