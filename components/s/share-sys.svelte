<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/q/qxewtxvch.css';
import '../../css/t/thamupbae.css';
import '../../css/h/h9b_txtlj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="qxewtxvch"/><path class="thamupbae"/><path class="h9b_txtlj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:share-sys" {...props}></Icon>
