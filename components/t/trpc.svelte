<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pqjg6_uxs.css';
import '../../css/q/qdb6ctypl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<g class="ft5dv1b6b"><rect class="pqjg6_uxs"/><path clip-rule="evenodd" class="qdb6ctypl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:trpc" {...props}></Icon>
