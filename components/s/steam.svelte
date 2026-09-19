<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsofbs0hl.css';
import '../../css/s/sl2chczps.css';
import '../../css/u/ub4ctds7g.css';
import '../../css/p/pj-urkbsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nsofbs0hl"/><g class="sl2chczps"><path class="ub4ctds7g"/><path class="pj-urkbsg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:steam" {...props}></Icon>
