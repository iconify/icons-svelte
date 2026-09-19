<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/r/rdgh0wbmt.css';
import '../../css/y/yqxucbc0n.css';
import '../../css/m/m4wir9t-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="rdgh0wbmt"/><path class="yqxucbc0n"/><path class="m4wir9t-b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:volume-notice" {...props}></Icon>
