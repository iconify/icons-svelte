<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqpblyxmw.css';
import '../../css/g/g49fs7bzv.css';
import '../../css/u/u-hmmubte.css';
import '../../css/m/mkzjpdbji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wqpblyxmw"/><path class="g49fs7bzv"/><path class="u-hmmubte"/><path class="mkzjpdbji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:satellite-dish-20" {...props}></Icon>
