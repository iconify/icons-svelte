<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkje3ybpz.css';
import '../../css/u/u90tapbtx.css';
import '../../css/n/neiwdiudh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gkje3ybpz"/><path class="u90tapbtx"/><path class="neiwdiudh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:zoom-in-48" {...props}></Icon>
