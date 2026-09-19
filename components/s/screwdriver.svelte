<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0a9vkbzg.css';
import '../../css/a/arbmb7b9s.css';
import '../../css/t/tx6culb0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="a0a9vkbzg"><path class="arbmb7b9s"/><path class="tx6culb0f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:screwdriver" {...props}></Icon>
