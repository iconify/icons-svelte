<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8rrb8l5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="l8rrb8l5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:watermelon" {...props}></Icon>
