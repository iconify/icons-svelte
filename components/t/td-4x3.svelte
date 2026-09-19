<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/m/mqs-w65-h.css';
import '../../css/o/o7m9e7b2j.css';
import '../../css/t/tldp9ccxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<g class="d2kvgvbvc"><path class="mqs-w65-h"/><path class="o7m9e7b2j"/><path class="tldp9ccxd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:td-4x3" {...props}></Icon>
