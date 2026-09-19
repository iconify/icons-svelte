<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdvk-d6wd.css';
import '../../css/x/xplmzjmbs.css';
import '../../css/e/e12p8hb9v.css';
import '../../css/a/ax8o968nq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<g class="gdvk-d6wd"><ellipse class="xplmzjmbs"/><path class="e12p8hb9v"/><path class="ax8o968nq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:server-outline" {...props}></Icon>
