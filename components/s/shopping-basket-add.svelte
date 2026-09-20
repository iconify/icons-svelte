<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7qb-gbjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="e7qb-gbjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:shopping-basket-add" {...props}></Icon>
