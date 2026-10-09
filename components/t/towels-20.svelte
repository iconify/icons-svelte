<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fabazvbbq.css';
import '../../css/c/c8jp6n-8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fabazvbbq"/><path class="c8jp6n-8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:towels-20" {...props}></Icon>
