<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izdfergmo.css';
import '../../css/v/vwvszy4rp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="izdfergmo"/><path class="vwvszy4rp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:sourceengine" {...props}></Icon>
