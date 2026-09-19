<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dxa8muzrd.css';
import '../../css/o/olpi3qujl.css';
import '../../css/a/a1myf2bxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="dxa8muzrd"/><path class="olpi3qujl"/><path class="a1myf2bxc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:tent-duo" {...props}></Icon>
