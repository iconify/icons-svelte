<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg5hyabrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="zg5hyabrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:ruby" {...props}></Icon>
