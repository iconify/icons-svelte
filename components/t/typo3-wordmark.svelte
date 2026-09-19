<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxln9bcuq.css';
import '../../css/g/gcac09b7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="lxln9bcuq"/><path class="gcac09b7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:typo3-wordmark" {...props}></Icon>
