<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to1a0gb8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="to1a0gb8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:shopping-bag-with-info-i" {...props}></Icon>
