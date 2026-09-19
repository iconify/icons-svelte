<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy5l9cc_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="zy5l9cc_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:sulu-wordmark" {...props}></Icon>
