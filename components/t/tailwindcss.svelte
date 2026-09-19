<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv5vrn7kp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="nv5vrn7kp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:tailwindcss" {...props}></Icon>
