<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzn-x-bxq.css';
import '../../css/j/j-3o0026v.css';
import '../../css/x/x9mz11vee.css';
import '../../css/w/w34yq1bdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bzn-x-bxq"/><path class="j-3o0026v"/><ellipse class="x9mz11vee"/><path class="w34yq1bdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:thermometer" {...props}></Icon>
