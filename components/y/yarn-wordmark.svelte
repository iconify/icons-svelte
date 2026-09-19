<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-ypg_i1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="q-ypg_i1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:yarn-wordmark" {...props}></Icon>
