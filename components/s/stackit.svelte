<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ju3_qt3um.css';
import '../../css/j/jlb1dbrgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ju3_qt3um"/><path class="jlb1dbrgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:stackit" {...props}></Icon>
