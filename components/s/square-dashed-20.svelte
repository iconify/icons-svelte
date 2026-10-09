<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxvb6in6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rxvb6in6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:square-dashed-20" {...props}></Icon>
