<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj9vjz3-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jj9vjz3-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:server-time-usage" {...props}></Icon>
