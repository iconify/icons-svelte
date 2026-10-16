<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsmnqk5do.css';
import '../../css/h/hqec9ivlc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nsmnqk5do"/><path class="hqec9ivlc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:voltage-tester-20-bold" {...props}></Icon>
