<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/x/xdqh4gbub.css';
import '../../css/l/ly55e3b8j.css';
import '../../css/m/mlwpmpkcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><rect class="xdqh4gbub"/><path class="ly55e3b8j"/><circle class="mlwpmpkcx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:stereo-one" {...props}></Icon>
