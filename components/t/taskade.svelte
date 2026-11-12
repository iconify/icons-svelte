<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz934u5vg.css';
import '../../css/n/ny4gz8bqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="pz934u5vg"/><path class="ny4gz8bqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:taskade" {...props}></Icon>
