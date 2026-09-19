<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/ebsul_bxa.css';
import '../../css/b/bqarpxbaq.css';
import '../../css/c/cc2hh2ugt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="ebsul_bxa"/><path class="bqarpxbaq"/><path class="cc2hh2ugt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:wallet-duo" {...props}></Icon>
