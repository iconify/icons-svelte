<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ax3i4wbrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ax3i4wbrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:yarn" {...props}></Icon>
