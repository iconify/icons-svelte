<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbwlt8bjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="pbwlt8bjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:vala-wordmark" {...props}></Icon>
