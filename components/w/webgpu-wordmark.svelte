<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oftlmobpw.css';
import '../../css/a/aj9y6acmb.css';
import '../../css/b/br3smkx-y.css';
import '../../css/t/trga3dbka.css';
import '../../css/d/dvo9i08hu.css';
import '../../css/o/omcedhw0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="oftlmobpw"/><path class="aj9y6acmb"/><path class="br3smkx-y"/><path class="trga3dbka"/><path class="dvo9i08hu"/><path class="omcedhw0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:webgpu-wordmark" {...props}></Icon>
