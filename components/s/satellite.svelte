<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/k/kgugpibha.css';
import '../../css/o/os5b4vbrt.css';
import '../../css/s/sj1g9qbqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="kgugpibha"/><path class="os5b4vbrt"/><path class="sj1g9qbqm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:satellite" {...props}></Icon>
