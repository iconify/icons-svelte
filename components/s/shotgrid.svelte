<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otlbybqix.css';
import '../../css/n/nbsc69_8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<circle class="otlbybqix"/><path class="nbsc69_8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:shotgrid" {...props}></Icon>
