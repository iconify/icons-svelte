<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5tu_snlf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o5tu_snlf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:star-of-david-solid" {...props}></Icon>
