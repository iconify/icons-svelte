<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hb_xljp9g.css';
import '../../css/e/erkje89et.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="hb_xljp9g"/><path class="erkje89et"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:sunbehindcloud" {...props}></Icon>
