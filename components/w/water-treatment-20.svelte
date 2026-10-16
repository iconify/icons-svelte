<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kj4vzjb5q.css';
import '../../css/v/vnif4gbyf.css';
import '../../css/a/ads4cuuck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kj4vzjb5q"/><path class="vnif4gbyf"/><path class="ads4cuuck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:water-treatment-20" {...props}></Icon>
