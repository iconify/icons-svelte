<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/u/u1qtw7b2b.css';
import '../../css/u/u6t9lrs4u.css';
import '../../css/q/qqpblxf5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="u1qtw7b2b"/><path class="u6t9lrs4u"/><path class="qqpblxf5z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:stethoscope" {...props}></Icon>
