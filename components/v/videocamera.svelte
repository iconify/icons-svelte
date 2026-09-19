<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/p/psxdx4bcl.css';
import '../../css/n/nvevodjmo.css';
import '../../css/s/s7b7bgbvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><rect class="psxdx4bcl"/><circle class="nvevodjmo"/><path class="s7b7bgbvx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:videocamera" {...props}></Icon>
