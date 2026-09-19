<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbk4gmbom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="sbk4gmbom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:trpc-wordmark" {...props}></Icon>
