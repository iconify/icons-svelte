<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evs_ze2wt.css';
import '../../css/r/rge2six-h.css';
import '../../css/y/ycgbuscwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="evs_ze2wt"/><path class="rge2six-h"/><path class="ycgbuscwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:spicedb" {...props}></Icon>
