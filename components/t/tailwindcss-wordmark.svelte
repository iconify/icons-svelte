<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/js7pf5byf.css';
import '../../css/i/iv3gg9_op.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="js7pf5byf"/><path class="iv3gg9_op"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:tailwindcss-wordmark" {...props}></Icon>
