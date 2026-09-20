<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g18t66qmd.css';
import '../../css/l/lf_du3q8d.css';
import '../../css/j/jcogv-28d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g18t66qmd"/><path class="lf_du3q8d"/><path class="jcogv-28d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:window-grid" {...props}></Icon>
