<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd48whbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fd48whbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:vault" {...props}></Icon>
