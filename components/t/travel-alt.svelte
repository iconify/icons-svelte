<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/n5u5o1ykq.css';
import '../../css/l/lonii6b0k.css';
import '../../css/a/a7hds4b4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="n5u5o1ykq"/><path clip-rule="evenodd" class="lonii6b0k"/><path clip-rule="evenodd" class="a7hds4b4p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:travel-alt" {...props}></Icon>
