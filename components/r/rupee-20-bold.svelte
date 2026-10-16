<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt3s35byo.css';
import '../../css/u/uby7xibdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rt3s35byo"/><path class="uby7xibdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rupee-20-bold" {...props}></Icon>
