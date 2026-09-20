<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4ysgrd8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b4ysgrd8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:vending-bottle-upside-down" {...props}></Icon>
