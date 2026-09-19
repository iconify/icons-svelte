<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/try1-1biq.css';
import '../../css/i/io3h1rboq.css';
import '../../css/v/v6uy02bwj.css';
import '../../css/y/ywoad4akh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="try1-1biq"/><path clip-rule="evenodd" class="io3h1rboq"/><path class="v6uy02bwj"/><path clip-rule="evenodd" class="ywoad4akh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sun-1-outline" {...props}></Icon>
