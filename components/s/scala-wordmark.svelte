<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4vvvyndn.css';
import '../../css/l/lrvq4dd-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="x4vvvyndn"/><path class="lrvq4dd-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:scala-wordmark" {...props}></Icon>
