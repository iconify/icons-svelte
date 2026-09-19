<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pz2c466ij.css';
import '../../css/u/unw0i2xbo.css';
import '../../css/x/xtn16ws4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="pz2c466ij"/><path class="unw0i2xbo"/><path class="xtn16ws4v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:snooze" {...props}></Icon>
