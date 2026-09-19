<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5ewtco_s.css';
import '../../css/v/vpg-ykb3g.css';
import '../../css/a/axl75o_4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q5ewtco_s"/><path class="vpg-ykb3g"/><path class="axl75o_4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:soil-temperature-global" {...props}></Icon>
