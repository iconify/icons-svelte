<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3au-5bor.css';
import '../../css/a/avg_k22jv.css';
import '../../css/i/ic5amcb4z.css';
import '../../css/d/d2wq1dhwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="l3au-5bor"/><path class="avg_k22jv"/><path class="ic5amcb4z"/><path class="d2wq1dhwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:servicenow-wordmark" {...props}></Icon>
