<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aaw774b1y.css';
import '../../css/b/bjy9zyb1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="aaw774b1y"/><path class="bjy9zyb1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:selenium" {...props}></Icon>
