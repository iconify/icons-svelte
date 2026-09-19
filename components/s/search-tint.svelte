<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/whkshnk2k.css';
import '../../css/a/av-7svb0x.css';
import '../../css/b/b7d5grbrs.css';
import '../../css/a/aniouw7ao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="whkshnk2k"/><path class="av-7svb0x"/><path class="b7d5grbrs"/><path class="aniouw7ao"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:search-tint" {...props}></Icon>
