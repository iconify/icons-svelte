<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpuek5b3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="wpuek5b3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:spring" {...props}></Icon>
