<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/d/d_-x11bji.css';
import '../../css/t/tnn9fxbxj.css';
import '../../css/s/sq4bxibhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="d_-x11bji"/><path class="tnn9fxbxj"/><circle transform="rotate(-180 12 10)" class="sq4bxibhc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:s-turn-left" {...props}></Icon>
