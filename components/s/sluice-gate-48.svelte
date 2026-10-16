<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmzb4zr4b.css';
import '../../css/l/lbvcveb9f.css';
import '../../css/z/z2zx3vbyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hmzb4zr4b"/><path class="lbvcveb9f"/><path class="z2zx3vbyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sluice-gate-48" {...props}></Icon>
