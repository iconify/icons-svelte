<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3_17eb5m.css';
import '../../css/n/nknwp425q.css';
import '../../css/b/bzswhqb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w3_17eb5m"/><path class="nknwp425q"/><path class="bzswhqb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:winter-warning" {...props}></Icon>
