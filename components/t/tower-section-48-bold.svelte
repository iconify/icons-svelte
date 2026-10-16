<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0im2rdhh.css';
import '../../css/q/qa5f_6hbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="q0im2rdhh"/><path class="qa5f_6hbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tower-section-48-bold" {...props}></Icon>
