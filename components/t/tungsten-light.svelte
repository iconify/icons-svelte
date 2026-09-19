<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gte8b1byc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gte8b1byc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:tungsten-light" {...props}></Icon>
