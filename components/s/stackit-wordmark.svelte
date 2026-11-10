<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0pri_qum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="m0pri_qum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:stackit-wordmark" {...props}></Icon>
