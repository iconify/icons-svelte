<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awek-epgl.css';
import '../../css/b/brfai6b9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="awek-epgl"/><path class="brfai6b9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:soldering-iron-48" {...props}></Icon>
