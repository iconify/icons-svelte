<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lvo947bui.css';
import '../../css/w/wvxwsc-vy.css';
import '../../css/s/sleav579e.css';
import '../../css/z/zt1e34j_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="lvo947bui"/><path clip-rule="evenodd" class="wvxwsc-vy"/><path class="sleav579e"/><path clip-rule="evenodd" class="zt1e34j_a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:smile-beam-outline" {...props}></Icon>
