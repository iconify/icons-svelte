<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/n/nin1__b8i.css';
import '../../css/w/wc7kqptyu.css';
import '../../css/i/i4_4y8x4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="nin1__b8i"/><path class="wc7kqptyu"/><path class="i4_4y8x4l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:table-lamp" {...props}></Icon>
