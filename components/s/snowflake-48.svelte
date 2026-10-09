<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcailpd3t.css';
import '../../css/k/k_y542bvu.css';
import '../../css/c/clrbi72ou.css';
import '../../css/o/o1-his81l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dcailpd3t"/><path class="k_y542bvu"/><path class="clrbi72ou"/><path class="o1-his81l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:snowflake-48" {...props}></Icon>
