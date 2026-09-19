<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd8ne7a8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="fd8ne7a8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:webgpu" {...props}></Icon>
