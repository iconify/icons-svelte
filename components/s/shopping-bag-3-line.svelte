<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcq1nd9yz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dcq1nd9yz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:shopping-bag-3-line" {...props}></Icon>
