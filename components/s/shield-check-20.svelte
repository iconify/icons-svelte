<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emhcgzbmm.css';
import '../../css/q/q2v_q547a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="emhcgzbmm"/><path class="q2v_q547a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shield-check-20" {...props}></Icon>
