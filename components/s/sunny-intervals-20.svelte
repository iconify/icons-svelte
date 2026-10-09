<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iitjuzooh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="iitjuzooh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sunny-intervals-20" {...props}></Icon>
