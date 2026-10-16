<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3ncbbc7h.css';
import '../../css/w/wtrttcq8m.css';
import '../../css/t/tcplxobio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c3ncbbc7h"/><path class="wtrttcq8m"/><path class="tcplxobio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tiny-house-20-bold" {...props}></Icon>
