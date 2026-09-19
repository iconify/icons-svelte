<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4-jhn-gz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="m4-jhn-gz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:social-smashing-mag" {...props}></Icon>
