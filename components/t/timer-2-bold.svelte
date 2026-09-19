<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/ef2n8rbvn.css';
import '../../css/t/t6peypblt.css';
import '../../css/v/v53ihtb3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="ef2n8rbvn"/><path class="t6peypblt"/><path class="v53ihtb3e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:timer-2-bold" {...props}></Icon>
