<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tewnblb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tewnblb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:shopping-bag-with-ruble" {...props}></Icon>
