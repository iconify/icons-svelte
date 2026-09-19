<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/l/lh8eyg1vb.css';
import '../../css/i/i061d9bsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<g class="d2kvgvbvc"><path class="lh8eyg1vb"/><path class="i061d9bsi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:unrealengine-wordmark" {...props}></Icon>
