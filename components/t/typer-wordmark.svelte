<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9_00hbai.css';
import '../../css/l/l_m-ojccy.css';
import '../../css/i/ib-739bah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<rect class="z9_00hbai"/><rect class="l_m-ojccy"/><path class="ib-739bah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:typer-wordmark" {...props}></Icon>
