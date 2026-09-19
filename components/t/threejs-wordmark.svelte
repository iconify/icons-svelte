<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk1ju-bpp.css';
import '../../css/g/gn7jhi5kh.css';
import '../../css/j/jvodmxq9q.css';
import '../../css/q/q0ifr8ahi.css';
import '../../css/e/e-fhcwqwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="dk1ju-bpp"/><path class="gn7jhi5kh"/><path class="jvodmxq9q"/><path class="q0ifr8ahi"/><path class="e-fhcwqwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:threejs-wordmark" {...props}></Icon>
