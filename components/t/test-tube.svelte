<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkv48acbf.css';
import '../../css/d/dsbz12bru.css';
import '../../css/p/pg-j1evyr.css';
import '../../css/c/cfmykrbut.css';
import '../../css/f/fjsedw-yo.css';
import '../../css/t/tntr6ebzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="dsbz12bru"/><path class="pg-j1evyr wm-shine"/><path class="cfmykrbut wm-k"/><path class="fjsedw-yo wm-a"/><path class="tntr6ebzv wm-deco"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-kawaii:test-tube" {...props}></Icon>
