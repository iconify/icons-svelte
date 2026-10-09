<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d97ksobub.css';
import '../../css/q/qa7qb6t-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d97ksobub"/><path class="qa7qb6t-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sunrise-20" {...props}></Icon>
