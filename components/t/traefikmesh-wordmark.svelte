<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/is3vjhbys.css';
import '../../css/w/wgy-1_e7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="is3vjhbys"/><path class="wgy-1_e7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:traefikmesh-wordmark" {...props}></Icon>
