<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbiwgmbyr.css';
import '../../css/h/hbyu2bdtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jbiwgmbyr"/><path class="hbyu2bdtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wrench-48" {...props}></Icon>
