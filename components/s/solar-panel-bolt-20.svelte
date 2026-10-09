<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwg6nmvzy.css';
import '../../css/k/k1o0uibpr.css';
import '../../css/a/a2v302bpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wwg6nmvzy"/><path class="k1o0uibpr"/><path class="a2v302bpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-panel-bolt-20" {...props}></Icon>
