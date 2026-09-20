<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eylr1q3ho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="eylr1q3ho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:star2" {...props}></Icon>
