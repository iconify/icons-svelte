<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhtb0ij6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="nhtb0ij6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:unix" {...props}></Icon>
