<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvqg8kbji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="jvqg8kbji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:watermill-11" {...props}></Icon>
