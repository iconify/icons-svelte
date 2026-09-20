<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4iysw_ix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a4iysw_ix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:vending-bottle" {...props}></Icon>
