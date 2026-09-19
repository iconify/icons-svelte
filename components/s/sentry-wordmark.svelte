<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3a964bzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="l3a964bzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:sentry-wordmark" {...props}></Icon>
