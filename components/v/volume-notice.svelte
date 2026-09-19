<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/g/g9w75jc3n.css';
import '../../css/y/yqxucbc0n.css';
import '../../css/m/m4wir9t-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="g9w75jc3n"/><path class="yqxucbc0n"/><path class="m4wir9t-b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:volume-notice" {...props}></Icon>
