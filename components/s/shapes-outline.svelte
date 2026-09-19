<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jm9wa7blu.css';
import '../../css/w/wjj7p8alk.css';
import '../../css/z/z5wdhwbks.css';
import '../../css/x/xp86pvbjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="jm9wa7blu"/><path class="wjj7p8alk"/><path clip-rule="evenodd" class="z5wdhwbks"/><path class="xp86pvbjs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:shapes-outline" {...props}></Icon>
