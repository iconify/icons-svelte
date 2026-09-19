<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/y/yhy_qabht.css';
import '../../css/u/uoathacvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="yhy_qabht"/><path class="uoathacvi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:tachometer-7" {...props}></Icon>
