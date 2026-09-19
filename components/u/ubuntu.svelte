<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwe8t-bzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="gwe8t-bzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:ubuntu" {...props}></Icon>
