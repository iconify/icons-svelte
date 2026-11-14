<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol55nrnhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ol55nrnhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:tanstack" {...props}></Icon>
