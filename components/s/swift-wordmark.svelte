<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlm67jbrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="jlm67jbrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:swift-wordmark" {...props}></Icon>
