<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4kx72bov.css';
import '../../css/n/n-zjmmulx.css';
import '../../css/q/q4l9ctu0n.css';
import '../../css/u/uq78lkwmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c4kx72bov"/><path class="n-zjmmulx"/><path class="q4l9ctu0n"/><path class="uq78lkwmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:vacuum-48-bold" {...props}></Icon>
