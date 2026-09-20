<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxvanubiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="kxvanubiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:volume-high" {...props}></Icon>
